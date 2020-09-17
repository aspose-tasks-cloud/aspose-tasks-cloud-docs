---
title: "Delete Resource From Project"
type: docs
url: /delete-resource-from-project/
weight: 20
---

# **Introduction**
This example allows you to delete a resource using Aspose.Tasks Cloud API in your applications.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/resources/{resourceUid}|DELETE|Delete an Assignment from a MS Project|[DeleteResource](https://apireference.aspose.cloud/tasks/#/TasksResources/DeleteResource)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/resources/1" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjU4MTM4MzMsImV4cCI6MTU2NTkwMDIzMywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.i-jvPiyFTxus_07QqK7tPLNffcFb_iwyCIFpdL81pCTqWmh5-Bolcj293rgYJoaQeDsLyoCXcQNN9C-BUUb_xWfOsJNX1zw_GE-G5J-DOKbuBxJqYC1z2LK3LNxeRgHyK4ubKQktSctiMxDOeMBBge20PRCNvTZHxgagUAQ5Va3KWA43F9F3GaB2AtS09t8IB1ADQThhn6YpP5mBzkiX7gkYU0BGETt2oZ0sZjGFbKUDlTasUc4sWj-rTbsClNoLFYvYJ55jvZW3QefO8hndVsngM8U7Z3jDvuGVlAyBoklwGlADaSR_u00Of5ybzbfcMWjM8cSS83tJZwQ4fL3xKQ"

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
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNET-CSharp-Resources-DeleteResource-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-resources-DeleteResourceFromProjectExample-DeleteResourceFromProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Resources-DeleteProjectResource-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Resources-delete_project_resource-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-resources-DeleteResourceFromProjectExample-DeleteResourceFromProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Resources-DeleteResource-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "9c962bc5504452579884a1c131bd5a9e" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "07d78654b167adaec0092ee353df17a9" >}}

{{< /tab >}}

{{< /tabs >}}
