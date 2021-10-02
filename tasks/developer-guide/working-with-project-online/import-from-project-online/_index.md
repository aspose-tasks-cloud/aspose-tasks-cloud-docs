---
title: "Import from Project Online"
description: "Aspose.Tasks Cloud allows you to import from project online in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /import-from-project-online/
weight: 10
---

## **Introduction**
This example explains how to import project from project online by providing Token or Login and Password credentials, and save it to file using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/importfromprojectonline|PUT|Imports project from Project Online and saves it to specified file|[PutImportProjectFromProjectOnline](https://apireference.aspose.cloud/tasks/#/TasksDocument/PutImportProjectFromProjectOnline)|
### **cURL Example**
#### **Case 1:** **Import project online using login and password credentials**

{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/NewProductDev.mpp/importfromprojectonline?siteUrl=http%3A%2F%2Fproject_server_instance.local%2Fsites%2Fpwa&userName=SomeLogin&format=xml" -H "accept: application/json" -H "x-sharepoint-password: SomePassword" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "E6426C44-D6CB-4B9C-AF16-48910ACE0F54"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
   "Code":200,
   "Status":"OK"
}

```

{{< /tab >}}

{{< /tabs >}}

#### **Case 2:** **Import project online using token credentials**

{{< tabs tabTotal="2" tabID="2" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/NewProductDev.mpp/importfromprojectonline?siteUrl=http%3A%2F%2Fproject_server_instance.local%2Fsites%2Fpwa&format=xml" -H "accept: application/json" -H "x-project-online-token: SOMESECRETTOKEN" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "E6426C44-D6CB-4B9C-AF16-48910ACE0F54"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
   "Code":200,
   "Status":"OK"
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

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutImportProjectFromProjectOnlineByLoginPassword.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-ImportProjectByLoginAndPassword.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "048ab6652b2272a3983756192e682c9e" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "a624a2064930fe7d1067033c915b4324" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PutImportProjectFromProjectOnlineByLoginPassword.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-PutImportProjectFromProjectOnlineByLoginPassword.java" >}}

{{< /tab >}}

{{< /tabs >}}

#### **Case 2:** **Import project online using token credentials**

{{< tabs tabTotal="6" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutImportProjectFromProjectByToken.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-ImportProjectByToken.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "d37a1e1eaced15baf1c9e935ef3acc28" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "69b5318496219e5fc913a45649465f3d" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PutImportProjectFromProjectByToken.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-PutImportProjectFromProjectByToken.java" >}}

{{< /tab >}}

{{< /tabs >}}
