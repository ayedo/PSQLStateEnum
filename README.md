# PSQLStateEnum

A Java Enum for all [PostgreSQL 10.0 error codes](https://www.postgresql.org/docs/current/static/errcodes-appendix.html).

Naming conflicts were resolved as follows:

| Code A | Code B | Shared Message                     | Code Renamed | New Name                                  |
|--------|--------|------------------------------------|--------------|-------------------------------------------|
| 01004  | 22001  | STRING_DATA_RIGHT_TRUNCATION       | 01004        | STRING_DATA_RIGHT_TRUNCATION_WARNING      |
| 22004  | 39004  | NULL_VALUE_NOT_ALLOWED             | 39004        | NULL_VALUE_NOT_ALLOWED_EXTERNAL           |
| 2F002  | 38002  | MODIFYING_SQL_DATA_NOT_PERMITTED   | 38002        | MODIFYING_SQL_DATA_NOT_PERMITTED_EXTERNAL |
| 2F003  | 38003  | PROHIBITED_SQL_STATEMENT_ATTEMPTED | 38003        | MODIFYING_SQL_DATA_NOT_PERMITTED_EXTERNAL |
| 2F004  | 38004  | READING_SQL_DATA_NOT_PERMITTED     | 38004        | READING_SQL_DATA_NOT_PERMITTED_EXTERNAL   |
