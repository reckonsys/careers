# Pythonista

Make sure you read [Common Requirements & Responsibilities](https://github.com/reckonsys/careers#common-requirements--responsibilities) before you proceed


## Responsibilities

* You will have to build GraphQL APIs
* You are responsible for deploying your code (We already have all the deployment scripts that are well-documented over here: [bigga](https://github.com/reckonsys/bigga))
* You may be required to build the product from ground up.
* You will have to implement new features
* Every day, you will have to adress bugs (atleast the critical/medium ones) before starting a new feature.
* Optimize the parts of code that you feel can be written better


## Requirements

* Check out the `Tech Stack` below (and make sure you are comfortable with at-least the essentials of the stack)
* Should have at-least 3 years experience in building backend / web application (any scripting language / framework)
* Of the 3 years thats mentioned above, at least 2 year should be using Django (Or at-least any other python framework).
* Strong HTML; Proficient in JavaScript & CSS
* The number of years may not matter if you show promising skills
* Exposure to celery
* Knows how to setup a server


## Nice to have (Optional - but, these are huge plus)
* Go Lang / Elixir
* Know how to deploy backend using our [bigga](https://github.com/reckonsys/bigga) project. [This is just a docker-compose file]
* Good grasp on client-side JavaScript (or CoffeeScript/typescript)
* have used frontend frameworks like Ember, Angular, Backbone, React
* SASS / LESS Experience is huge plus



## Tech Stack

You should have a strong understanding (at the least, the fundamentals / getting started) of the following:

* [Python](https://developers.google.com/edu/python/)
* [Django](https://docs.djangoproject.com/en/3.0/intro/install/)
* [GraphQL](https://www.edx.org/course/exploring-graphql-a-query-language-for-apis)
* [Graphene](https://docs.graphene-python.org/en/latest/quickstart/)

## Assignment

Using the tech stack above (This is a must), build a simple blog API service. It should expose a GraphQL endpoint to do the folloing things:

1. Implement a `createPost()` mutation which will create a `Post` (a blogpost object) with attributes {`title`, `description`, `publish_date`, `author` (just a name as TextField)}
1. Implement a `updatePost($id)` mutation which will update a `Post` attributes by `$id`
1. Implement a `createComment()` mutation which will create a `Comment` object with attributes {`post` (the blogpost object), `text`, `author` (just the name as a TextField)}
1. Implement a `deleteComment($id)` mutation to delete the given `Comment` by its ID. 
1. Implement a `posts()` query to list all the posts
1. Implement a `post($id)` query to get details of a post and all its comments12
