---
title: API
layout: rancher-api-v2-beta-default-v1.2
version: v1.2
lang: zh
apiVersion: v2-beta
---

## toServiceUpgradeStrategy



### Resource Fields

#### Writeable Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
batchSize | int | Optional | - | 1 | 
finalScale | int | Optional | - | 1 | 
intervalMillis | int | Optional | - | 2000 | 
toServiceId | [service]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/{{page.apiVersion}}/api-resources/service/) | Optional | - | - | 
updateLinks | boolean | Optional | - | - | 



<br>
