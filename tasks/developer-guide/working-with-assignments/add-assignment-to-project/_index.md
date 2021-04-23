---
title: "Add Assignment to Project"
description: "Aspose.Tasks Cloud allows you to add assignment to project in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
keywords: "assignment of tasks, REST API, create an assignment, new assignment, using Python, Perl, MS Project Management, project management, add a new assignment in mpp, mpt, xml, assign task to resource"
type: docs
url: /add-assignment-to-project/
weight: 40
---

## **Introduction**
The assignment feature in project management permits task to be assigned to the appropriate resource(s). The following article explains, how to create an assignment in project management using our REST API, which can be used with any language, like .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
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
{{< tabs tabTotal="5" tabID="5" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PostAssignment.cs" >}}

{{< /tab >}}


{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-PostAssignment.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "5a77e4e2db6ed8a4cfc12dee637f3acd" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "4bf974a1ad3873450b6a376432df3240" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PostAssignment.go" >}}

{{< /tab >}}

{{< /tabs >}}
