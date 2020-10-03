---
title: "Add Assignment to Project"
type: docs
url: /add-assignment-to-project/
weight: 40
---

## **Introduction**
This API allows you to adds a new assignment to a project and returns assignment item in a response.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments|POST|Add a new assignment to a MS Project File|[PostAssignment](https://apireference.aspose.cloud/tasks/#/TasksAssignments/PostAssignment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "https://api.aspose.cloud/connect/token" -X POST -d "grant_type=client_credentials&client_id=XXXXX&client_secret=XXXXX" -H "Content-Type: application/x-www-form-urlencoded" -H "Accept: application/json"

```

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/assignments?taskUid=1&resourceUid=1&units=1.0" -H "accept: application/json" 

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
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="4" tabID="5" tabName1="C#" tabName2="PHP" tabName3="Pyhton" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-.NET-AddAssignment.cs" >}}

{{< /tab >}}


{{< tab tabNum="2" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Assignments-PostProjectAssignment-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "5a77e4e2db6ed8a4cfc12dee637f3acd" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "4bf974a1ad3873450b6a376432df3240" >}}

{{< /tab >}}

{{< /tabs >}}
