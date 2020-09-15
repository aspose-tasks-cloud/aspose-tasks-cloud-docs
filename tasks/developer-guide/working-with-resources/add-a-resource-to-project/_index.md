---
title: "Add a Resource To Project"
type: docs
url: /add-a-resource-to-project/
weight: 30
---

# **Introduction**
This example allows you to add a resource to a Project using Aspose.Tasks Cloud API in your applications.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/resources|POST|Add a named resource to a MS Project Document|[PostResource](https://apireference.aspose.cloud/tasks/#/TasksResources/PostResource)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/resources" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjU4MTM4MzMsImV4cCI6MTU2NTkwMDIzMywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.i-jvPiyFTxus\_07QqK7tPLNffcFb\_iwyCIFpdL81pCTqWmh5-Bolcj293rgYJoaQeDsLyoCXcQNN9C-BUUb\_xWfOsJNX1zw\_GE-G5J-DOKbuBxJqYC1z2LK3LNxeRgHyK4ubKQktSctiMxDOeMBBge20PRCNvTZHxgagUAQ5Va3KWA43F9F3GaB2AtS09t8IB1ADQThhn6YpP5mBzkiX7gkYU0BGETt2oZ0sZjGFbKUDlTasUc4sWj-rTbsClNoLFYvYJ55jvZW3QefO8hndVsngM8U7Z3jDvuGVlAyBoklwGlADaSR\_u00Of5ybzbfcMWjM8cSS83tJZwQ4fL3xKQ"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

   "ResourceItem":{

      "Link":{

         "Href":"/resources/2",

         "Rel":"self",

         "Type":null,

         "Title":null

      },

      "Uid":2,

      "Id":2,

      "Name":"test"

   },

   "Code":201,

   "Status":"Created"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNET-CSharp-Resources-AddResource-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-resources-AddResourceToProjectExample-AddResourceToProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Resources-PostProjectResource-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Resources-add\_new\_resource\_to\_project-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-resources-AddResourceToProjectExample-AddResourceToProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Resources-AddResource-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "810fb8411964a204a18d1bd3bec0905f" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "4355375b5bb8328adf1c872093c31eca" >}}

{{< /tab >}}

{{< /tabs >}}
