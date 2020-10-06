---
title: MySqlDateTimeKind
---

# MySqlDateTimeKind enumeration

The DateTimeKind used when reading DateTime from the database.

```csharp
public enum MySqlDateTimeKind
```

## Values

| name | value | description |
| --- | --- | --- |
| Unspecified | `0` | Use Unspecified when reading; allow any DateTimeKind in command parameters. |
| Utc | `1` | Use Utc when reading; reject Local in command parameters. |
| Local | `2` | Use Local when reading; reject Utc in command parameters. |

## See Also

* namespace [MySqlConnector](../../MySqlConnectorNamespace/)
* assembly [MySqlConnector](../../MySqlConnectorAssembly/)

<!-- DO NOT EDIT: generated by xmldocmd for MySqlConnector.dll -->