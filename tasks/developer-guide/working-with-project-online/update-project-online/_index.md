---
title: "Update Project Online"
type: docs
url: /update-project-online/
weight: 40
---

## **Introduction**
This example explains how to update existing project online by providing Token or Login and Password credentials using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/projectOnline/{siteUrl}/{name}|PUT|Updates existing project in Project Server\Project Online instance. The existing project will be overwritten.|[UpdateProject](https://apireference.aspose.cloud/tasks/#/TasksProjectOnline/UpdateProject)|
### **cURL Example**
#### **Case 1:** **Update existing project online using login and password credentials**

{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/projectOnline/http%3A%2F%2Fproject_server_instance.local%2Fsites%2Fpwa/NewProductDev.mpp?userName=SomeLogin" -H "accept: application/json" -H "x-sharepoint-password: SomePassword" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"projectName\": \"string\", \"projectGuid\": \"string\", \"timeout\": \"string\", \"pollingInterval\": \"string\"}"

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

#### **Case 2:** **Update existing project online using token credentials**

{{< tabs tabTotal="2" tabID="2" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/projectOnline/http%3A%2F%2Fproject_server_instance.local%2Fsites%2Fpwa/NewProductDev.mpp" -H "accept: application/json" -H "x-project-online-token: SOMESECRETTOKEN" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"projectName\": \"string\", \"projectGuid\": \"string\", \"timeout\": \"string\", \"pollingInterval\": \"string\"}"

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
#### **Case 1:** **Update existing project online using login and password credentials**

{{< tabs tabTotal="4" tabID="3" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-UpdateProjectByLoginPassword.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-UpdateProjectByLoginAndPassword.php" >}}

{{< /tab >}}


{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "7e70bc44178d128d6f3382c56a87a8a1" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "649b0e6eb5527458570a0dafa5578810" >}}

{{< /tab >}}

{{< /tabs >}}

#### **Case 2:** **Update existing project online using token credentials**

{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-UpdateProjectByToken.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-UpdateProjectByToken.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "89253a6eb9e66803c91e690db41f6108" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "0d6e86e11d9392e4f4544b9b6c83cfd9" >}}

{{< /tab >}}

{{< /tabs >}}

