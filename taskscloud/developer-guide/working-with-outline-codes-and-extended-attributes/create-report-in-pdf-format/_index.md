---
title: "Create Report in PDF Format"
type: docs
url: /create-report-in-pdf-format/
weight: 40
---

# **Introduction**
This example allows you to returns created report in PDF format using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, Objective C, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/report|GET|Returns created report in PDF format|[GetReportPdf](https://apireference.aspose.cloud/tasks/#/TasksReport/GetReportPdf)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v http://api.aspose.cloud/v1.1/tasks/{documentname}/criticalPath?appsid=xxxx&signature=xxxx \

     -X GET \

	 -H "Content-Type: application/json" \

     -H "Accept: application/json"  



```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Tasks": {

    "TaskItem": [

      {

        "Link": {

          "Href": "/1",

          "Rel": "self",

          "Type": null,

          "Title": null

        },

        "Uid": 1,

        "Id": 1,

        "Name": "Task1",

        "Start": "/Date(960451200000+0000)/",

        "Finish": "/Date(963766800000+0000)/",

        "Duration": "9.16:00:00"

      },

      {

        "Link": {

          "Href": "/3",

          "Rel": "self",

          "Type": null,

          "Title": null

        },

        "Uid": 3,

        "Id": 3,

        "Name": "Task3",

        "Start": "/Date(960451200000+0000)/",

        "Finish": "/Date(960570000000+0000)/",

        "Duration": "16:00:00"

      },

      {

        "Link": {

          "Href": "/4",

          "Rel": "self",

          "Type": null,

          "Title": null

        },

        "Uid": 4,

        "Id": 4,

        "Name": "Task4",

        "Start": "/Date(960624000000+0000)/",

        "Finish": "/Date(961779600000+0000)/",

        "Duration": "3.08:00:00"

      },

      {

        "Link": {

          "Href": "/5",

          "Rel": "self",

          "Type": null,

          "Title": null

        },

        "Uid": 5,

        "Id": 5,

        "Name": "Task5",

        "Start": "/Date(961833600000+0000)/",

        "Finish": "/Date(963075600000+0000)/",

        "Duration": "3.16:00:00"

      },

      {

        "Link": {

          "Href": "/7",

          "Rel": "self",

          "Type": null,

          "Title": null

        },

        "Uid": 7,

        "Id": 7,

        "Name": "Task7",

        "Start": "/Date(961833600000+0000)/",

        "Finish": "/Date(963075600000+0000)/",

        "Duration": "3.16:00:00"

      },

      {

        "Link": {

          "Href": "/8",

          "Rel": "self",

          "Type": null,

          "Title": null

        },

        "Uid": 8,

        "Id": 8,

        "Name": "Task8",

        "Start": "/Date(963129600000+0000)/",

        "Finish": "/Date(963421200000+0000)/",

        "Duration": "16:00:00"

      },

      {

        "Link": {

          "Href": "/9",

          "Rel": "self",

          "Type": null,

          "Title": null

        },

        "Uid": 9,

        "Id": 9,

        "Name": "Task9",

        "Start": "/Date(963475200000+0000)/",

        "Finish": "/Date(963507600000+0000)/",

        "Duration": "08:00:00"

      },

      {

        "Link": {

          "Href": "/10",

          "Rel": "self",

          "Type": null,

          "Title": null

        },

        "Uid": 10,

        "Id": 10,

        "Name": "Task10",

        "Start": "/Date(963561600000+0000)/",

        "Finish": "/Date(963766800000+0000)/",

        "Duration": "1.00:00:00"

      }

    ],

    "link": {

      "Href": "/tasks",

      "Rel": "self",

      "Type": null,

      "Title": null

    }

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
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="Perl" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNET-CSharp-Tasks-GetReportPdf-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Tasks-GetReportPdf-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< /tab >}}

{{< /tabs >}}
