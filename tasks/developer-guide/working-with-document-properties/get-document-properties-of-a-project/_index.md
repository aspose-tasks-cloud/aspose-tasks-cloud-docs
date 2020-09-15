---
title: "Get Document Properties of a Project"
type: docs
url: /get-document-properties-of-a-project/
weight: 10
---

# **Introduction**
This example explains how to get a collection of a project's document properties. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/documentproperties|GET|Read collection of document properties from a MS Project File|[GetDocumentProperties](https://apireference.aspose.cloud/tasks/#/TasksDocumentProperties/GetDocumentProperties)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/documentproperties" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjUyMDk3NTksImV4cCI6MTU2NTI5NjE1OSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.hl4CZ8kKgceOuRjwydQh87CCflf9Arca8io3L0OruC7N3rhSouJLZWDtyeGrtornpLerpVSN\_yokWJTdTBtHHW7i\_vt46wSJy5evh03ccWxUjXWsc3Tbt-T4sfWOtIYreET7hwE\_A-5AJoRPsyR8TKOHIGsbRZ2H5nX3XdEZgfcEFCV77RiHyIET4tlYtdplnjaFCBRHXCidgtbLzm0Bislejr5onrYS0DRz7XCxfndwaCfzxE0ylL1vHUkv41ZSmq1MnCVcmA2ZVno8-JeDjL1d8CdqORNCab5Yj\_Sz7S7z\_kDesrBGZ1uc4gpSYd6rz67apeG\_Wa6J8aKi3W9bnw"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {

   "Properties":{

      "List":[

         {

            "Name":"Title",

            "Value":"Home Move",

            "link":{

               "Href":"/Title",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Subject",

            "Value":"",

            "link":{

               "Href":"/Subject",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Author",

            "Value":"",

            "link":{

               "Href":"/Author",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Manager",

            "Value":"",

            "link":{

               "Href":"/Manager",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Company",

            "Value":"",

            "link":{

               "Href":"/Company",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Category",

            "Value":"",

            "link":{

               "Href":"/Category",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Keywords",

            "Value":"",

            "link":{

               "Href":"/Keywords",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Comments",

            "Value":"",

            "link":{

               "Href":"/Comments",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"HyperlinkBase",

            "Value":"",

            "link":{

               "Href":"/HyperlinkBase",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"CreationDate",

            "Value":"2/16/2012 10:39:00 AM",

            "link":{

               "Href":"/CreationDate",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"LastAuthor",

            "Value":"",

            "link":{

               "Href":"/LastAuthor",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"LastPrinted",

            "Value":"1/1/0001 12:00:00 AM",

            "link":{

               "Href":"/LastPrinted",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Revision",

            "Value":"1",

            "link":{

               "Href":"/Revision",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"CurrencySymbol",

            "Value":"$",

            "link":{

               "Href":"/CurrencySymbol",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"CurrencySymbolPosition",

            "Value":"Before",

            "link":{

               "Href":"/CurrencySymbolPosition",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"CurrencyDigits",

            "Value":"2",

            "link":{

               "Href":"/CurrencyDigits",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"DefaultStartTime",

            "Value":"8:00 AM",

            "link":{

               "Href":"/DefaultStartTime",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"DefaultFinishTime",

            "Value":"5:00 PM",

            "link":{

               "Href":"/DefaultFinishTime",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"MinutesPerDay",

            "Value":"480",

            "link":{

               "Href":"/MinutesPerDay",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"MinutesPerWeek",

            "Value":"2400",

            "link":{

               "Href":"/MinutesPerWeek",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"DaysPerMonth",

            "Value":"20",

            "link":{

               "Href":"/DaysPerMonth",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"DurationFormat",

            "Value":"Day",

            "link":{

               "Href":"/DurationFormat",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"WorkFormat",

            "Value":"Hour",

            "link":{

               "Href":"/WorkFormat",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"DefaultTaskType",

            "Value":"FixedUnits",

            "link":{

               "Href":"/DefaultTaskType",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"AreNewTasksEffortDriven",

            "Value":"True",

            "link":{

               "Href":"/AreNewTasksEffortDriven",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Autolink",

            "Value":"True",

            "link":{

               "Href":"/Autolink",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"CanSplitsInProgressTasks",

            "Value":"True",

            "link":{

               "Href":"/CanSplitsInProgressTasks",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"UpdateManuallyScheduledTasksWhenEditingLinks",

            "Value":"True",

            "link":{

               "Href":"/UpdateManuallyScheduledTasksWhenEditingLinks",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"HonorConstraints",

            "Value":"True",

            "link":{

               "Href":"/HonorConstraints",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"AreNewTasksEstimated",

            "Value":"True",

            "link":{

               "Href":"/AreNewTasksEstimated",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"NewTasksAreManual",

            "Value":"False",

            "link":{

               "Href":"/NewTasksAreManual",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"KeepTaskOnNearestWorkingTimeWhenMadeAutoScheduled",

            "Value":"False",

            "link":{

               "Href":"/KeepTaskOnNearestWorkingTimeWhenMadeAutoScheduled",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"AreEditableActualCosts",

            "Value":"False",

            "link":{

               "Href":"/AreEditableActualCosts",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"IsInsertedProjectsLikeSummary",

            "Value":"True",

            "link":{

               "Href":"/IsInsertedProjectsLikeSummary",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"DefaultFixedCostAccrual",

            "Value":"Prorated",

            "link":{

               "Href":"/DefaultFixedCostAccrual",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"TaskUpdatesResource",

            "Value":"True",

            "link":{

               "Href":"/TaskUpdatesResource",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"DefaultStandardRate",

            "Value":"0",

            "link":{

               "Href":"/DefaultStandardRate",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"DefaultOvertimeRate",

            "Value":"0",

            "link":{

               "Href":"/DefaultOvertimeRate",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"RemoveFileProperties",

            "Value":"True",

            "link":{

               "Href":"/RemoveFileProperties",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"IsScheduleFromStart",

            "Value":"True",

            "link":{

               "Href":"/IsScheduleFromStart",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"FyStartDate",

            "Value":"January",

            "link":{

               "Href":"/FyStartDate",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"CriticalSlackLimit",

            "Value":"0",

            "link":{

               "Href":"/CriticalSlackLimit",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"StartDate",

            "Value":"1/1/2004 8:00:00 AM",

            "link":{

               "Href":"/StartDate",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"FinishDate",

            "Value":"3/1/2004 5:00:00 PM",

            "link":{

               "Href":"/FinishDate",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"StatusDate",

            "Value":"1/1/0001 12:00:00 AM",

            "link":{

               "Href":"/StatusDate",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Uid",

            "Value":"1",

            "link":{

               "Href":"/Uid",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Duration",

            "Value":"43 days",

            "link":{

               "Href":"/Duration",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Work",

            "Value":"0 hrs",

            "link":{

               "Href":"/Work",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         },

         {

            "Name":"Cost",

            "Value":"$0.00",

            "link":{

               "Href":"/Cost",

               "Rel":"self",

               "Type":null,

               "Title":null

            }

         }

      ],

      "link":{

         "Href":"/documentProperties",

         "Rel":"self",

         "Type":null,

         "Title":null

      }

   },

   "Code":200,

   "Status":"OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetDocumentProperties.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "5efef0385e906b0afbccb898fb70eb55" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "51562b89b2bd5cf9db6eeb213d1664e1" >}}

{{< /tab >}}

{{< /tabs >}}
