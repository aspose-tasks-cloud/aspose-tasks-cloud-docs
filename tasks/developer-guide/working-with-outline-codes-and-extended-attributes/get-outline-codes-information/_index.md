---
title: "Get Outline Codes Information"
type: docs
url: /get-outline-codes-information/
weight: 10
---

# **Introduction**
This example allows you to retrieve Outline codes information using Aspose.Tasks Cloud API in your applications. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/outlineCodes|GET|Read TaskOutline Codes from a MS Project File|[GetOutlineCodes](https://apireference.aspose.cloud/tasks/#/TasksOutlineCodes/GetOutlineCodes)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/outlineCodes" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjM0MDAzMjMsImV4cCI6MTU2MzQ4NjcyMywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.VnQYUjuLEj9O7vnJoXL91iuWfOHFIxVzDn47ROH6MsBEDy3yDGWdSeyL-fN4yshhB3jfBLKovNlepoqKJh9jkvqMH86c7bSZKmZR_zUQvUOyvxVnsDl_JwbaVpoy4JJY2JitRgkLhWXk44YsM0zwUjyrTnD0uQ9tS0J1iS11XqF678ojglFRNn6naCQ_qPv1BsCr0kstGH1JdxPdc476pp9oRjc9SVZzgMCWSvCMkGI6P5evi19IMPdP1icTGhwOBvmbgL9erV7fhCpc7H7VPSkjvmKVxI12klnEaCQrqpxUXnEbjKJDgXs-XTrlxHffWZLzqUDeQW7arKrMexpzDQ"    

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"OutlineCodes":{"List":[],"link":{"Href":"/outlineCodes","Rel":"self","Type":null,"Title":null}},"Code":200,"Status":"OK"}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Ruby" tabName4="Objective C" tabName5="Perl" tabName6="Java" tabName7="Android" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNet-CSharp-CodesAndExtendedAttributes-RetrieveCodeInformation-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-OutlineCodesAndExtendedAttributes-GetOutlineCodes-.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-OutlineCodesAndExtendedAttributes-get_outline_codes-.rb" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-CodesAndExtendedAttributes-RetrieveCodeInformation-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-outlinecodes-RetrieveOutlineCodesExample-RetrieveOutlineCodesExample.java" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-outlinecodes-RetrieveOutlineCodesExample-RetrieveOutlineCodesExample.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "6a7997d7ce98aa224018166c317f9185" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "b9b5a2e9421c4f6d5332102622f08c85" >}}

{{< /tab >}}

{{< /tabs >}}
