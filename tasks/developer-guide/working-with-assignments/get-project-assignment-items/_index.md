---
title: "Get Project Assignment Items"
description: "Aspose.Tasks Cloud allows you to get project assignment items in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /get-project-assignment-items/
weight: 10
---

## **Introduction**
This example explains how to read assignment information from a MS Project file using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.

## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments|GET|Read assignment information from a MS Project File|[GetAssignments](https://apireference.aspose.cloud/tasks/#/TasksAssignments/GetAssignments)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -v "https://api.aspose.cloud/connect/token" -X POST -d "grant_type=client_credentials&client_id=XXXXX&client_secret=XXXXX" -H "Content-Type: application/x-www-form-urlencoded" -H "Accept: application/json"

```

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/project_2013.mpp/assignments" -H "accept: application/json" 

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
{{< tabs tabTotal="6" tabID="6" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetAssignments.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-GetAssignments.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "1e014e1252ca7250adb1af1573a7a510" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "cd11fd03bb220f04239c5029e08f8ad7" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetAssignments.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-GetAssignments.java" >}}

{{< /tab >}}

{{< /tabs >}}
