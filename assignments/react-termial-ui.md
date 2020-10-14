# GitHub Search on React Terminal

### Requirements

1. Terminal in React: https://github.com/nitin42/terminal-in-react
1. GitHub's GraphQL Explorer: https://developer.github.com/v4/explorer/
1. GitHub's `search` GraphQL docs: https://docs.github.com/en/free-pro-team@latest/graphql/reference/queries#searchresultitemconnection

### Assignment

Using `Terminal in react` package, implement a `search <repo name>` command that will fetch the results from GitHub's GraphQL `search` query and display the repo names and repo url (1 line per repo details) on Terminal Emulator

Sample output:

```sh
> search bootstrap
bootstrap: https://github.com/twbs/bootstrap
bootstrap: https://github.com/angular-ui/bootstrap
bootstrap-datepicker: https://github.com/uxsolutions/bootstrap-datepicker
bootstrap-table: https://github.com/wenzhixin/bootstrap-table
bootstrap: https://github.com/jasny/bootstrap
bootstrap-sass: https://github.com/twbs/bootstrap-sass
react-bootstrap: https://github.com/react-bootstrap/react-bootstrap
bootstrap-datetimepicker: https://github.com/Eonasdan/bootstrap-datetimepicker
bootstrap-select: https://github.com/snapappointments/bootstrap-select
bootstrap-material-design: https://github.com/mdbootstrap/bootstrap-material-design
```
