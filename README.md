# conventional-commits 0.1.0

## syntax

```
<type><scope>*<marker>*: <description>

<body>

<footer>*
```

### type

- `build`
  - `build(ci)` changes to a build pipeline
  - `build(deps)` dependency change
  - `build(version)` change module version
- `config`configuration change
- `docs` documentation change (e.g. JavaDoc, TODO, readme)
- `fix` fixing something
- `feat` adding a feature
- `log` change on logging
- `refactor` code change without behaviour change
- `perf` improving performance (e.g. faster, less resource consumption)
- `style` changing style (e.g. formatting code)
- `test` changes to tests
  - not aplicable for integration or system test modules => use `feat`

#### build/version

- no other commit type MUST contain a version change


### scope

- optional
- e.g. `api`


### marker

- `!` MUST be added if there is a breaking change

### description

- short summary


### body

- detailed description as list using `-`


### footer

- linking a ticket
  - syntax: `references: <ticket[, ]>?`
  - `ticket` MAY just contain the ID


## outlook

- add syntax for breaking changes (body vs. footer)
- add examples


## references

- based on
  - https://www.conventionalcommits.org/en/v1.0.0/
  - https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13
