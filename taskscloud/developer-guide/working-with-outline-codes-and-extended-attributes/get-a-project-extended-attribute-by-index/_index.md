---
title: "Get A Project Extended Attribute by Index"
type: docs
url: /get-a-project-extended-attribute-by-index/
weight: 60
---

# **Introduction**
This example allows you to retrieve project extended attribute definition using Aspose.Tasks Cloud API in your applications. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/extendedAttributes/{index}|GET|Read extended attribute information from a MS Project File|[GetExtendedAttributeByIndex](https://apireference.aspose.cloud/tasks/#/TasksExtendedAttributes/GetExtendedAttributeByIndex)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

url -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/extendedAttributes/1" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjM0MDAzMjMsImV4cCI6MTU2MzQ4NjcyMywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.VnQYUjuLEj9O7vnJoXL91iuWfOHFIxVzDn47ROH6MsBEDy3yDGWdSeyL-fN4yshhB3jfBLKovNlepoqKJh9jkvqMH86c7bSZKmZR\_zUQvUOyvxVnsDl\_JwbaVpoy4JJY2JitRgkLhWXk44YsM0zwUjyrTnD0uQ9tS0J1iS11XqF678ojglFRNn6naCQ\_qPv1BsCr0kstGH1JdxPdc476pp9oRjc9SVZzgMCWSvCMkGI6P5evi19IMPdP1icTGhwOBvmbgL9erV7fhCpc7H7VPSkjvmKVxI12klnEaCQrqpxUXnEbjKJDgXs-XTrlxHffWZLzqUDeQW7arKrMexpzDQ"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"ExtendedAttribute":null,"Code":200,"Status":"OK"}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNet-CSharp-CodesAndExtendedAttributes-GetExtendedAttributeDefination-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-outlinecodes-GetProjectExtendedAttributeExample-GetProjectExtendedAttributeExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-OutlineCodesAndExtendedAttributes-GetExtendedAttributeByIndex-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-OutlineCodesAndExtendedAttributes-get\_extended\_attribute\_by\_index-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-outlinecodes-GetProjectExtendedAttributeExample-GetProjectExtendedAttributeExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-CodesAndExtendedAttributes-GetExtendedAttributeDefination-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< /tab >}}

{{< /tabs >}}
