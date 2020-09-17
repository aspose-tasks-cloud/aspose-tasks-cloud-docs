---
title: "Get Outline Code By Index"
type: docs
url: /get-outline-code-by-index/
weight: 20
---

# **Introduction**
This example allows you to get Outline Code by index using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, Objective C, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/outlineCodes/{index}|GET|Read outline codes by index information from a MS Project file|[GetOutlineCodeByIndex](https://apireference.aspose.cloud/tasks/#/TasksOutlineCodes/GetOutlineCodeByIndex)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/outlineCodes/1" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjM0MDAzMjMsImV4cCI6MTU2MzQ4NjcyMywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.VnQYUjuLEj9O7vnJoXL91iuWfOHFIxVzDn47ROH6MsBEDy3yDGWdSeyL-fN4yshhB3jfBLKovNlepoqKJh9jkvqMH86c7bSZKmZR_zUQvUOyvxVnsDl_JwbaVpoy4JJY2JitRgkLhWXk44YsM0zwUjyrTnD0uQ9tS0J1iS11XqF678ojglFRNn6naCQ_qPv1BsCr0kstGH1JdxPdc476pp9oRjc9SVZzgMCWSvCMkGI6P5evi19IMPdP1icTGhwOBvmbgL9erV7fhCpc7H7VPSkjvmKVxI12klnEaCQrqpxUXnEbjKJDgXs-XTrlxHffWZLzqUDeQW7arKrMexpzDQ"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"OutlineCode":{"Guid":"D9AAA732-FD34-4A60-91B6-66D4B4386C81","FieldId":"188744096","FieldName":"Outline Code1","Alias":"Skills","PhoneticAlias":null,"Values":[{"ValueId":1,"FieldGuid":"6FBE9A7C-9CD2-4031-A3C7-BE61F13946C6","Type":6,"ParentValueId":0,"Value":"Consultants","Description":"Consultants","IsCollapsed":false},{"ValueId":5,"FieldGuid":"DC928D92-66D9-4DC8-86AA-01C815CB7032","Type":6,"ParentValueId":0,"Value":"Testers","Description":"Testers","IsCollapsed":false},{"ValueId":2,"FieldGuid":"909E3408-38C5-4AF5-BFFF-325DB85813BA","Type":6,"ParentValueId":1,"Value":"201","Description":"Finance Consultant","IsCollapsed":false},{"ValueId":3,"FieldGuid":"8FD0C5BE-5427-490E-84A5-439154AFA93E","Type":6,"ParentValueId":1,"Value":"202","Description":"Fixed Assets Consultants","IsCollapsed":false},{"ValueId":4,"FieldGuid":"02D91AFB-F592-4E02-B649-30DAFB7FF22D","Type":6,"ParentValueId":1,"Value":"203","Description":"Production consultant","IsCollapsed":false},{"ValueId":6,"FieldGuid":"AB445DB2-B645-4E9B-9F9D-7096E1D43519","Type":6,"ParentValueId":5,"Value":"301","Description":"Database Tester","IsCollapsed":false},{"ValueId":7,"FieldGuid":"619625AE-CF4A-4760-A17F-3BA4A4CA1A3E","Type":6,"ParentValueId":5,"Value":"302","Description":"Application Tester","IsCollapsed":false},{"ValueId":8,"FieldGuid":"11D10B4A-21B2-4BD7-BC79-7A7543F8996E","Type":6,"ParentValueId":5,"Value":"303","Description":"Report Tester","IsCollapsed":false}],"Enterprise":false,"EnterpriseOutlineCodeAlias":0,"ResourceSubstitutionEnabled":false,"LeafOnly":false,"AllLevelsRequired":false,"OnlyTableValuesAllowed":true,"Masks":[{"Level":1,"Type":4,"Length":0,"Separator":"."},{"Level":2,"Type":1,"Length":3,"Separator":"."}],"ShowIndent":true},"Code":200,"Status":"OK"}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNet-CSharp-CodesAndExtendedAttributes-GetCodeByIndex-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-outlinecodes-GetOutlineCodeByIndexExample-GetOutlineCodeByIndexExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-OutlineCodesAndExtendedAttributes-GetOutlineCodeByIndex-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-OutlineCodesAndExtendedAttributes-get_outline_code_by_index-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-outlinecodes-GetOutlineCodeByIndexExample-GetOutlineCodeByIndexExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-CodesAndExtendedAttributes-GetCodeByIndex-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "8063d999260e8db44b685d7bc25fdefa" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "19ffc760e4231be39030ec751d5592cf" >}}

{{< /tab >}}

{{< /tabs >}}
