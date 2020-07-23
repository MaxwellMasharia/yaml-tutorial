# YAML - Tutorial

## Basic Syntax

- Key-Value Pairs

```yaml
key: value
```

- Comments

```yaml
# This is a comment
```

- Objects
  - Use indentation to create an object

```yaml
person:
  name: "Maxwell Masharia"
  age: 20
```

- Lists

```yaml
listOne:
  - List Item One
  - List Item Two
  - List Item Three
listTwo:
  - List Item One
  - List Item Two
  - List Item Three

objectOne:
  - List Item One
    sub-prop-one: val
    sub-prop-two: val

# You can also use [] to show lists
List: [1,2,3,4,5]
```

- Multiline Strings

```yaml
  multi-line-string: |
  This is a multi-line-string
  Yeah
```

- SingleLine Strings

```yaml
  single-line-string: >
  This is a single line
  and it should only be on one line
```

# Github Actions

## Workflows

- Workflows are custom automated processes that you can set up in your repository to build, test, package, release, or deploy any project on GitHub

- You can create more than one workflow in a repository. You must store workflows in the .github/workflows directory in the root of your repository.

- Workflows must have at least one job, and jobs contain a set of steps that perform individual tasks. Steps can run commands or use an action. You can create your own actions or use actions shared by the GitHub community and customize them as needed.

- You can configure a workflow to start when a GitHub event occurs, on a schedule, or from an external event

