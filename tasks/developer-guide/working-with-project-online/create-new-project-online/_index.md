---
title: "Create New Project Online"
description: "Aspose.Tasks Cloud allows you to create new project online in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /create-new-project-online/
weight: 30
---

## **Introduction**
This example explains how to create new project online by providing Token or Login and Password credentials using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/projectOnline/{siteUrl}/{name}|POST|Creates new project in Project Server\Project Online instance|[CreateNewProject](https://apireference.aspose.cloud/tasks/#/TasksProjectOnline/CreateNewProject)|
### **cURL Example**
#### **Case 1:** **Create new project online using login and password credentials**

{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/projectOnline/http%3A%2F%2Fproject_server_instance.local%2Fsites%2Fpwa/NewProductDev.mpp?userName=SomeLogin" -H "accept: application/json" -H "x-sharepoint-password: SomePassword" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"projectName\": \"string\", \"projectGuid\": \"string\", \"timeout\": \"string\", \"pollingInterval\": \"string\"}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string"
}

```

{{< /tab >}}

{{< /tabs >}}

#### **Case 2:** **Create new project online using token credentials**

{{< tabs tabTotal="2" tabID="2" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/projectOnline/http%3A%2F%2Fproject_server_instance.local%2Fsites%2Fpwa/NewProductDev.mpp" -H "accept: application/json" -H "x-project-online-token: SOMESECRETTOKEN" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"projectName\": \"string\", \"projectGuid\": \"string\", \"timeout\": \"string\", \"pollingInterval\": \"string\"}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string"
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
#### **Case 1:** **Create new project online using login and password credentials**

{{< tabs tabTotal="5" tabID="3" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-CreateNewProjectByLoginPassword.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-CreateNewProjectByLoginAndPassword.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "91cef45a4a9f7c208137a4aa8b2c61e3" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "a739a036fd5406b1e2da7ee2ea1e6db2" >}}

{{< /tab >}}

{{< /tabs >}}

#### **Case 2:** **Create new project online using token credentials**

{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-CreateNewProjectByToken.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-CreateNewProjectByToken.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "160752f4b48e39a2b06df72ef091268e" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "df2bd90180bc60646d8cdced8cf44b32" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-CreateNewProjectByToken.go" >}}

{{< /tab >}}

{{< /tabs >}}

