# GORM Sqlite Driver

![CI](https://github.com/go-gorm/sqlite/workflows/CI/badge.svg)

## USAGE

```go
import (
  "github.com/goforkit/driver/sqlite"
  "github.com/goforkit/gorm"
)

// github.com/mattn/go-sqlite3
db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```

Checkout [https://github.com/goforkit](https://github.com/goforkit) for details.

### Pure go Sqlite Driver

checkout [https://github.com/glebarez/sqlite](https://github.com/glebarez/sqlite) for details

```go
import (
  "github.com/glebarez/sqlite"
  "github.com/goforkit/gorm"
)

db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```
