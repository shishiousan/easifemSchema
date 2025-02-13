
WIP

# easifemSchema

Some Json Schema files for [easifem](https://github.com/easifem).

Integration with [Taplo](https://github.com/tamasfe/taplo) is the main objective of these files.

## How to use

- clone or copy the json schema file and locate it wherever you want.
- edit the `.taplo.toml` or `taplo.toml` file, for example

  ```toml
  [[rule]]
  include = ["**/config*.toml"]

  [rule.schema]
  path = "/where/you/put/the/json/schema/file.json"
  enable = true
  ```

- open `config*.toml` in editor where `taplo` can run
- now you can get auto-completion in the toml file !!

