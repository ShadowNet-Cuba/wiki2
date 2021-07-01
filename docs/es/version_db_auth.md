# version_db_auth

[<-Volver a:Auth](database-auth.md)

**Tabla \`version_db_auth\`**

| Field              | Type         | Attributes | Key | Null | Default | Extra | Comment |
|--------------------|--------------|------------|-----|------|---------|-------|---------|
| [sql_rev][1]       | VARCHAR(100) |            | PRI | NO   |         |       |         |
| [required_rev][2]  | VARCHAR(100) |            | MUL | YES  |         |       |         |
| [2020_02_07_00][3] | bit(1)       |            |     | YES  |         |       |         |

[1]: #sql_rev
[2]: #required_rev
[3]: #2020_02_07_00

### sql_rev

Revisión sql.

### required_rev

Revisión requerida.

### 2020_02_07_00

### Ejemplo

| sql_rev             | required_rev | 2020_02_07_00 |
|---------------------|--------------|---------------|
| 1554142988374631100 |              |               |
| 1579213352894781043 |              |               |