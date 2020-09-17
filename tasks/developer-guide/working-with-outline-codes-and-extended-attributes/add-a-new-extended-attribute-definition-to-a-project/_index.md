---
title: "Add a new Extended Attribute definition to a Project"
type: docs
url: /add-a-new-extended-attribute-definition-to-a-project/
weight: 80
---

# **Introduction**
This example allows you to add a new extended attribute in a project using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/extendedAttributes|PUT|Add a new extended attribute definition to a project or updates existing attribute definition|[PutExtendedAttribute](https://apireference.aspose.cloud/tasks/#/TasksExtendedAttributes/PutExtendedAttribute)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v http://api.aspose.cloud/v1.1/tasks/NewProductDev.mpp/extendedAttributes?appsid=xxxx&signature=xxxx \
     -X PUT \
     -H "Content-Type: application/json" \
     -H "Accept: application/json"

     -d '{

            "CalculationType" : "Lookup",

            "CfType" : "Text",

            "FieldName" : "Text3",

            "ElementType" : "Task",

            "Alias" : "New Field",

            "ValueList" : [

            {"Description" : "descr1", "Val" : "Internal", "Id" : 111},

            {"Description" : "descr2", "Val" : "External", "Id" : 112},

            ]

        }'

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "ExtendedAttribute": {

    "Link": {

      "Href": "/extendedAttributes/3",

      "Rel": "self",

      "Type": null,

      "Title": null

    },

    "Index": 1,

    "FieldName": "Text3",

    "Alias": "New Field",

    "FieldId": "188743737"

  },

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-PutExtendedAttribute.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "cb8264639fd09956a01ded367242cafc" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "b979306c391c8d3599c2b95d367452d1" >}}

{{< /tab >}}

{{< /tabs >}}
