---
title: "Get VBA Project"
type: docs
url: /get-vba-project/
weight: 10
---

# **Introduction**
This example explains how to get VBA project using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/vbaproject|GET|Read VBA Project from a MPP File|[GetVbaProject](https://apireference.aspose.cloud/tasks/#/TasksVbaProject/GetVbaProject)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/vbaproject" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjUyOTkzMTIsImV4cCI6MTU2NTM4NTcxMiwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.QlHWTcHIqsHKK9jSccLTHSaFDiLm4HCXJr96BmsG73ggC9Zd40qtErAC3qL7vOD59YxLqbIXuloW1Md7JCbxWhBzWA7YIclthCOZwNVR06ueeKS-Pr-M9lZ2KSVBmuzY06M83\_JuhsdPl54THUcBY\_QEqH4XIu-lHKr0CERAF8xgoNLQweNGQquARFDcO8ww5QE1F15GdJQrG0FhtsY0h26wO934tQXXHqsVFirNvobBui9Wp-c6hCY\_f6Dlb6u34WYhkDxu1b6jN9MbzvwAeO-NnyqV3Tpmp--XwQl0nC9c\_TFuslVZiXVSgYmH8q8s4oDGw1j\_1dG3PPKMUG\_jYA"

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "VbaProject": {

    "CompilationArguments": "",

    "Description": "",

    "HelpContextId": 0,

    "HelpFile": "",

    "Modules": [

      {

        "Attributes": [

          {

            "Key": "VB\_Name",

            "Value": "Module1"

          }

        ],

        "Name": "Module1",

        "SourceCode": "Type MEMORYSTATUS\r\n   dwLength As Long\r\n   {...}"

      },

      {

        "Attributes": [

          {

            "Key": "VB\_Name",

            "Value": "Module2"

          }

        ],

        "Name": "Module2",

        "SourceCode": "Sub InputBoxDemo()\r\n    Dim myValue\r\n    myValue = InputBox(\"Please enter number of hours worked\", \"Hours Worked\")\r\n   \r\n    MsgBox myValue\r\nEnd Sub\r\n"

      }

    ],

    "Name": "VBAProject",

    "References": []

  },

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="3" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetVbaProject.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "07d0280d9d97b5c70e18f62948166c78" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "a8e269a4af19b5a5a90277ce3b31a7ff" >}}

{{< /tab >}}

{{< /tabs >}}
