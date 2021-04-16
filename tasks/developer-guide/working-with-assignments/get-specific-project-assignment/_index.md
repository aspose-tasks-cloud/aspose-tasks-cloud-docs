---
title: "Get Specific Project Assignment"
type: docs
url: /get-specific-project-assignment/
weight: 20
---

## **Introduction**
This example explains how to read Project Assignment with the specified UID using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments/{assignmentUid}|GET|Read assignment information from MS Project file by a unique identifier|[GetAssignment](https://apireference.aspose.cloud/tasks/#/TasksAssignments/GetAssignment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java
 curl -v "https://api.aspose.cloud/connect/token" -X POST -d "grant_type=client_credentials&client_id=XXXXX&client_secret=XXXXX" -H "Content-Type: application/x-www-form-urlencoded" -H "Accept: application/json"

```

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/assignments/1" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java
{
  "code": 0,
  "status": "string",
  "assignments": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "assignmentItem": [
      {
        "link": {
          "href": "string",
          "rel": "string",
          "type": "string",
          "title": "string"
        },
        "uid": 0,
        "taskUid": 0,
        "resourceUid": 0
      }
    ]
  }
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="5" tabID="5" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetAssignment.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-GetAssignment.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "5f48f5ab6ecb08c8e1e09ea92a848144" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "760b3264aa8e590ed366e6f01231ee75" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetAssignment.go" >}}

{{< /tab >}}

{{< /tabs >}}
