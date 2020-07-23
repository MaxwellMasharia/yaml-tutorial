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
