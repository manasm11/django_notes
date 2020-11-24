# Searching
- ```
  [model-class-name].objects
  .get(
      [underscore-separated-attribute]_contains
      ="[search-query]"
      )
    ```
Similarly:
- ```
  [model-class-name].objects
  .get(
      [underscore-separated-attribute]_startswith
      ="[search-query]"
      )
    ```

# Migrations
- Migrations allow you to revert changes in database if you need to.