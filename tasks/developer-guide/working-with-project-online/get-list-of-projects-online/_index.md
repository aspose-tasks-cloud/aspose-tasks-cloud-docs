---
title: "Get List of Projects Online"
description: "Aspose.Tasks Cloud allows you to get list of projects online in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /get-list-of-projects-online/
weight: 20
---

## **Introduction**
This example explains how to get online projects list by providing Token or Login and Password credentials using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/projectOnline/projectList|GET|Gets the list of published projects in the current Project Online account|[GetProjectList](https://apireference.aspose.cloud/tasks/#/TasksProjectOnline/GetProjectList)|
### **cURL Example**
#### **Case 1:** **Get list of projects online using login and password credentials**

{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/projectOnline/projectList?siteUrl=http%3A%2F%2Fproject_server_instance.local%2Fsites%2Fpwa&userName=SomeLogin" -H "accept: application/json" -H "x-sharepoint-password: SomePassword" -H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "code": 0,
  "status": "string",
  "projects": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "projectInfo": [
      {
        "id": "string",
        "name": "string",
        "createdDate": "2020-06-27T16:22:17.414Z",
        "isCheckedOut": true,
        "lastPublishedDate": "2020-06-27T16:22:17.414Z",
        "lastSavedDate": "2020-06-27T16:22:17.414Z",
        "description": "string"
      }
    ]
  }
}

```

{{< /tab >}}

{{< /tabs >}}

#### **Case 2:** **Get list of projects online using token credentials**

{{< tabs tabTotal="2" tabID="2" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/projectOnline/projectList?siteUrl=http%3A%2F%2Fproject_server_instance.local%2Fsites%2Fpwa" -H "accept: application/json" -H "x-project-online-token: SOMESECRETTOKEN" -H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "projects": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "projectInfo": [
      {
        "id": "string",
        "name": "string",
        "createdDate": "2020-06-27T16:22:17.414Z",
        "isCheckedOut": true,
        "lastPublishedDate": "2020-06-27T16:22:17.414Z",
        "lastSavedDate": "2020-06-27T16:22:17.414Z",
        "description": "string"
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
#### **Case 1:** **Import project online using login and password credentials**

{{< tabs tabTotal="6" tabID="3" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetProjectListByLoginPassword.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-GetProjectListByLoginAndPassword.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "83e71ac2fbe8b258f4d8cea0f796a9b7" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "50bc43dbc6bb7d6193257e9c5b98dc16" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetProjectListByLoginPassword.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-GetProjectListByLoginPassword.java" >}}

{{< /tab >}}

{{< /tabs >}}

#### **Case 2:** **Import project online using token credentials**

{{< tabs tabTotal="6" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetProjectListByToken.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-GetProjectListByTokenCredential.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "3795bf8cb8ae1234a0feff0b2e14f716" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "412657f401adefc5e28f66362bde65d4" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetProjectListByToken.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-GetProjectListByToken.java" >}}

{{< /tab >}}

{{< /tabs >}}

