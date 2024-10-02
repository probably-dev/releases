# Probably Sources

To add a new data source to Probably, simply drop a config file into this folder
with the source config.

Config files in this directory with extensions such as .toml, .json, .yaml are all
ignored from source control to avoid checking in credentials.

## Supported Sources

**Snowflake**

Example `connections.toml`

```
account = "myaccount"
user = "jdoe"
password = "thupersecurepwd"
role = "my-role"
warehouse = "my-wh"
database = "my_db"
schema = "my_schema"
```
