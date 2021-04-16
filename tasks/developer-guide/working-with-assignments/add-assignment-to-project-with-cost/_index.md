---
title: "Add Assignment to Project With Cost"
type: docs
url: /add-assignment-to-project-with-cost/
weight: 50
---

## **Introduction**
This API allows you to add assignments to your project file with specifying its cost and returns assignment item in a response, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
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

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Cost_Res.mpp/assignments?taskUid=0&resourceUid=1&cost=2" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

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
{{< tabs tabTotal="5" tabID="5" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PostAssignmentWithCost.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-PostAssignmentWithCost.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "c698f3b7905f5b8b18814a5edecb5e8a" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "1d12645f59e675ba65a3df56cdce596c" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PostAssignmentWithCost.go" >}}

{{< /tab >}}

{{< /tabs >}}
