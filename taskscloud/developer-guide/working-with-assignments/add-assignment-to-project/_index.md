---
title: "Add Assignment to Project"
type: docs
url: /add-assignment-to-project/
weight: 40
---

# **Introduction**
This API allows you to adds a new assignment to a project and returns assignment item in a response.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments|POST|Add a new assignment to a MS Project File|[PostAssignment](https://apireference.aspose.cloud/tasks/#/TasksAssignments/PostAssignment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "https://api.aspose.cloud/connect/token" -X POST -d "grant\_type=client\_credentials&client\_id=78946fb4-3bd4-4d3e-b309-f9e2ff9ac6f9&client\_secret=b125f13bf6b76ed81ee990142d841195" -H "Content-Type: application/x-www-form-urlencoded" -H "Accept: application/json"

```

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/assignments?taskUid=1&resourceUid=1&units=1.0" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjI5NjgwOTUsImV4cCI6MTU2MzA1NDQ5NSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiNzg5NDZmYjQtM2JkNC00ZDNlLWIzMDktZjllMmZmOWFjNmY5IiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.YesjZfTmxKi7TiKAzBPOZj2jkbWZifAzyJe8nULhCpchlPilLYVLZ0ph6OBF-n4JGOeXhyck3zGORn3TP6wT\_HjFzzHGmZr9aPZnQqVU4Ypch8MnmgPgdeRZ\_L-FVNHq042w5A2zyUUZb9HFk67um7\_vAnuTXWxcHaK6\_mP2jG4vMAiE5MdxfUAylDQNymBRsiMivxgX5a3i2E2eUSCAs7ghpvdlVxHVcyjFg5GX26V67iD-FFqJDihoG6oyTAAJzTRnvxOb3jmNGo2Sav5VmmgkGeuHzDgdTYLJKGMZwXjIKdwx0Vuz-U5ilfbe-XHoqPha3pE5bD7ByjbfR5hnuw"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Code": "200",

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="5" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Pyhton" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-.NET-AddAssignment.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-assinments-AddAssignmentToProjectExample-AddAssignmentToProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Assignments-PostProjectAssignment-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Assignments-add\_new\_assignment-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-assinments-AddAssignmentToProjectExample-AddAssignmentToProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Assignments-AddAssignment-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "5a77e4e2db6ed8a4cfc12dee637f3acd" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "4bf974a1ad3873450b6a376432df3240" >}}

{{< /tab >}}

{{< /tabs >}}
