---
title: "Get Specific Project Assignment"
type: docs
url: /get-specific-project-assignment/
weight: 20
---

# **Introduction**
This example explains how to read Project Assignment with the specified UID. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments/{assignmentUid}|GET|Read assignment information from MS Project file by a unique identifier|[GetAssignment](https://apireference.aspose.cloud/tasks/#/TasksAssignments/GetAssignment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -v "https://api.aspose.cloud/connect/token" -X POST -d "grant_type=client_credentials&client_id=78946fb4-3bd4-4d3e-b309-f9e2ff9ac6f9&client_secret=b125f13bf6b76ed81ee990142d841195" -H "Content-Type: application/x-www-form-urlencoded" -H "Accept: application/json"

```

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/assignments/1" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjI5NjgwOTUsImV4cCI6MTU2MzA1NDQ5NSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiNzg5NDZmYjQtM2JkNC00ZDNlLWIzMDktZjllMmZmOWFjNmY5IiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.YesjZfTmxKi7TiKAzBPOZj2jkbWZifAzyJe8nULhCpchlPilLYVLZ0ph6OBF-n4JGOeXhyck3zGORn3TP6wT_HjFzzHGmZr9aPZnQqVU4Ypch8MnmgPgdeRZ_L-FVNHq042w5A2zyUUZb9HFk67um7_vAnuTXWxcHaK6_mP2jG4vMAiE5MdxfUAylDQNymBRsiMivxgX5a3i2E2eUSCAs7ghpvdlVxHVcyjFg5GX26V67iD-FFqJDihoG6oyTAAJzTRnvxOb3jmNGo2Sav5VmmgkGeuHzDgdTYLJKGMZwXjIKdwx0Vuz-U5ilfbe-XHoqPha3pE5bD7ByjbfR5hnuw"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java



```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="5" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetAssignment.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "5f48f5ab6ecb08c8e1e09ea92a848144" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "760b3264aa8e590ed366e6f01231ee75" >}}

{{< /tab >}}

{{< /tabs >}}
