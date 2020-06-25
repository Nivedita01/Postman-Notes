---
description: How to set and get variables through scripts and at Global scope.
---

# Set and Get Variables at the Global Level

### Get variables at Global level.

```text
pm.globals.get("Theme")
```

### Set variables at Global level

```text
pm.globals.set("param 1", "testing using postman")

//get global variable set in the above step
console.log(pm.globals.get("param 1"))
```

