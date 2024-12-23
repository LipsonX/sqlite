# LipsonX GORM Pure-Go Sqlite Driver Version

This project is draws inspiration from glebarez/sqlite and only base on modernc.org/sqlite. I personally maintain this project for personal compilation of the gogs project. Not recommended for use.

### Pure go Sqlite Driver

checkout [https://github.com/glebarez/sqlite](https://github.com/glebarez/sqlite) for details

```go
import (
  "github.com/LipsonX/sqlite"
  "gorm.io/gorm"
)

db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```
