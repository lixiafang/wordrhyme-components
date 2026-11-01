---
'@wordrhyme/auto-crud-server': patch
---

Use table runtime ID defaults for new import and batch-create rows with extension fields, preserving stable extension mapping and transactional persistence. Resolve import upsert column names from the table so camelCase fields use their database column names.
