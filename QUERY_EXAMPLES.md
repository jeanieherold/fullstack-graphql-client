# named Operations

- you can give your queries a name

```graphql
query AllCharacters {
  characters {
    results {
      name
    }
  }
}
```

- or you can leave them anonymous

```graphql
characters {
  results {
    name
  }
}
```
