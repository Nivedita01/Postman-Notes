---
description: How to set and get variables through scripts and at Collection scope.
---

# Set and Get Variables at Collection Level

Scripts can be written inside individual requests inside a Collection as shown below. Scripts written here will execute only for the particular request where it is specified.

![Scripting inside Request](../.gitbook/assets/scriptingrequestcollection.gif)

Scripts can also be written inside a Collection itself instead of individual requests. Scripts written here will execute once for each request.

![Scripting at the Collection level](../.gitbook/assets/scriptingcollection.gif)

{% hint style="info" %}
Instead of writing scripts in the Tests tab, scripts can also be written in the Pre-requests Scripts tab of requests/Collection.
{% endhint %}

### Get variables at the Collection level.

```text
pm.variables.get("url")
```

### Set variables at the Collection level.

```text
pm.variables.set("folder", "automation-postman")

console.log(pm.variables.get("folder"))
```

![Scripting at Collection level](../.gitbook/assets/script-collectionlevel.jpg)

![Console logs for scripting at Collection level](../.gitbook/assets/console.jpg)

