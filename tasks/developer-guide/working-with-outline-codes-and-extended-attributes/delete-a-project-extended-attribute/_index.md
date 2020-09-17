---
title: "Delete A Project Extended Attribute"
type: docs
url: /delete-a-project-extended-attribute/
weight: 70
---

# **Introduction**
This example allows you to delete a project extended attribute using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/extendedAttributes/{index}|DELETE|Delete a project extended attribute|[DeleteExtendedAttributeByIndex](https://apireference.aspose.cloud/tasks/#/TasksExtendedAttributes/DeleteExtendedAttributeByIndex)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v http://api.aspose.cloud/v1.1/tasks/{documentname}/extendedAttributes/{index}?appsid=xxxx&signature=xxxx \
     -X DELETE \
	 -H "Content-Type: application/json" \
     -H "Accept: application/json"  



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

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNet-CSharp-CodesAndExtendedAttributes-DeleteExtendedAttribute-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-outlinecodes-DeleteExtendedAttributeExample-DeleteExtendedAttributeExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-OutlineCodesAndExtendedAttributes-DeleteExtendedAttributeByIndex-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-OutlineCodesAndExtendedAttributes-delete\_extended\_attribute\_by\_index-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-outlinecodes-DeleteExtendedAttributeExample-DeleteExtendedAttributeExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-CodesAndExtendedAttributes-DeleteExtendedAttribute-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "6f4cd4fe9fd182c0bc502ed20a6b0051" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "f1d7cb4275bc6e56559805cc2bec441b" >}}

{{< /tab >}}

{{< /tabs >}}
