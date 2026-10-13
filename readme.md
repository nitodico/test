# arcillaDB

A SQL database with web-GUI

| Type | Information |
|---|---|
| `TEXT` | Plain text |
| `LONGTEXT` | Long text with new lines |\
| `BOOL` | Only true or false values |
| `COMMENTS` | Store comments |
| `COORDS` | Store 2 decimals |
| `COUNTRY` | ISO country selection |
| `CREATED` | Datetime of  |
| `CREATEDBY` | user who created this record |
| `UPDATED` | Datetime of when this record was update |
| `UPDATEDBY` | User who updated this record |
| `CURRENCY` | A value and a currency |
| `DECIMAL` |  |
| `EMAIL` | Valid e-mail dssdss |
| `FILE` | Upload a file |
| `FLOAT` | X |
| `FOLDER` | X |
| `INTEGER` | X |
| `JSON` | X |
| `PHONE` | X |
| `TOML` | X |
| `UNIQUE` | Unique value |
| `URL` | X |
| `VECTOR2` | X |
| `VECTOR3` | X |
| `UUID4` | X |

### Triggers
sss `OnInsert`, `OnUpsert`, `OnUpdate`, `OnDelete`

```
CREATE TRIGGER WHEN ONSINSERT tablename INSERT INTO logs VALUES ('start action', NOW())
```

- Make and action in another table
- Make a HTTP request
- Send an e-mail using SMTP