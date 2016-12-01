# Create Row

Create a new row in the given table.

> **Note:** Table names are case-sensitive

## HTTP Request

```bash
POST /api/1/tables/[table-name]/rows
```

## Example Request

```bash
$ curl --data "active=1&title=School+Website" \
        https://database.account.directus.io/api/1/tables/projects/rows \
                -u usrSTeeornngkti:
```

## Parameters

> **Note:** The parameters are based on the table's column.

## Response

> **Note:** The architecture of this response is based on your schema.

```json
{
  "id": 1,
  "active": 1,
  "title": "School Website"
}
```
