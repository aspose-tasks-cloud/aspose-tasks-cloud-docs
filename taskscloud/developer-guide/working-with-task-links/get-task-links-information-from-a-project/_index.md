---
title: "Get Task Links Information from a Project"
type: docs
url: /get-task-links-information-from-a-project/
weight: 10
---

# **Introduction**
This example allows you to retrieve a Project's Tasks links information using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/taskLinks|GET|Read Task Links|[GetTaskLinks](https://apireference.aspose.cloud/tasks/#/TasksTaskLinks/GetTaskLinks)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/taskLinks" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjM0MDAzMjMsImV4cCI6MTU2MzQ4NjcyMywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.VnQYUjuLEj9O7vnJoXL91iuWfOHFIxVzDn47ROH6MsBEDy3yDGWdSeyL-fN4yshhB3jfBLKovNlepoqKJh9jkvqMH86c7bSZKmZR\_zUQvUOyvxVnsDl\_JwbaVpoy4JJY2JitRgkLhWXk44YsM0zwUjyrTnD0uQ9tS0J1iS11XqF678ojglFRNn6naCQ\_qPv1BsCr0kstGH1JdxPdc476pp9oRjc9SVZzgMCWSvCMkGI6P5evi19IMPdP1icTGhwOBvmbgL9erV7fhCpc7H7VPSkjvmKVxI12klnEaCQrqpxUXnEbjKJDgXs-XTrlxHffWZLzqUDeQW7arKrMexpzDQ"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

   "TaskLinks":[

      {

         "Link":{

            "Href":"/taskLinks/1",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":1,

         "PredecessorUid":3,

         "SuccessorUid":4,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/2",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":2,

         "PredecessorUid":3,

         "SuccessorUid":5,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/3",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":3,

         "PredecessorUid":3,

         "SuccessorUid":6,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/4",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":4,

         "PredecessorUid":6,

         "SuccessorUid":9,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/5",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":5,

         "PredecessorUid":4,

         "SuccessorUid":9,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/6",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":6,

         "PredecessorUid":6,

         "SuccessorUid":10,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/7",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":7,

         "PredecessorUid":6,

         "SuccessorUid":11,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/8",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":8,

         "PredecessorUid":6,

         "SuccessorUid":12,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/9",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":9,

         "PredecessorUid":6,

         "SuccessorUid":13,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/10",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":10,

         "PredecessorUid":13,

         "SuccessorUid":15,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/11",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":11,

         "PredecessorUid":13,

         "SuccessorUid":16,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/12",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":12,

         "PredecessorUid":16,

         "SuccessorUid":18,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/13",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":13,

         "PredecessorUid":16,

         "SuccessorUid":19,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/14",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":14,

         "PredecessorUid":16,

         "SuccessorUid":20,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/15",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":15,

         "PredecessorUid":20,

         "SuccessorUid":22,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/16",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":16,

         "PredecessorUid":20,

         "SuccessorUid":23,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/17",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":17,

         "PredecessorUid":20,

         "SuccessorUid":24,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/18",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":18,

         "PredecessorUid":20,

         "SuccessorUid":25,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/19",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":19,

         "PredecessorUid":25,

         "SuccessorUid":28,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/20",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":20,

         "PredecessorUid":25,

         "SuccessorUid":29,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/21",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":21,

         "PredecessorUid":25,

         "SuccessorUid":30,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/22",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":22,

         "PredecessorUid":25,

         "SuccessorUid":31,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/23",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":23,

         "PredecessorUid":31,

         "SuccessorUid":33,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/24",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":24,

         "PredecessorUid":31,

         "SuccessorUid":34,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/25",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":25,

         "PredecessorUid":31,

         "SuccessorUid":35,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/26",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":26,

         "PredecessorUid":31,

         "SuccessorUid":36,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/27",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":27,

         "PredecessorUid":31,

         "SuccessorUid":37,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/28",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":28,

         "PredecessorUid":31,

         "SuccessorUid":38,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/29",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":29,

         "PredecessorUid":38,

         "SuccessorUid":40,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/30",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":30,

         "PredecessorUid":40,

         "SuccessorUid":44,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/31",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":31,

         "PredecessorUid":40,

         "SuccessorUid":45,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/32",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":32,

         "PredecessorUid":40,

         "SuccessorUid":46,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/33",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":33,

         "PredecessorUid":40,

         "SuccessorUid":47,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/34",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":34,

         "PredecessorUid":47,

         "SuccessorUid":49,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/35",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":35,

         "PredecessorUid":47,

         "SuccessorUid":50,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/36",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":36,

         "PredecessorUid":47,

         "SuccessorUid":51,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/37",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":37,

         "PredecessorUid":47,

         "SuccessorUid":52,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/38",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":38,

         "PredecessorUid":52,

         "SuccessorUid":54,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/39",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":39,

         "PredecessorUid":52,

         "SuccessorUid":55,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/40",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":40,

         "PredecessorUid":55,

         "SuccessorUid":57,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/41",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":41,

         "PredecessorUid":55,

         "SuccessorUid":58,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/42",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":42,

         "PredecessorUid":55,

         "SuccessorUid":59,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/43",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":43,

         "PredecessorUid":55,

         "SuccessorUid":60,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/44",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":44,

         "PredecessorUid":55,

         "SuccessorUid":61,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/45",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":45,

         "PredecessorUid":55,

         "SuccessorUid":62,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/46",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":46,

         "PredecessorUid":62,

         "SuccessorUid":65,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/47",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":47,

         "PredecessorUid":65,

         "SuccessorUid":67,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/48",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":48,

         "PredecessorUid":65,

         "SuccessorUid":68,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/49",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":49,

         "PredecessorUid":65,

         "SuccessorUid":70,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/50",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":50,

         "PredecessorUid":68,

         "SuccessorUid":71,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/51",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":51,

         "PredecessorUid":68,

         "SuccessorUid":72,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/52",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":52,

         "PredecessorUid":68,

         "SuccessorUid":73,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/53",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":53,

         "PredecessorUid":68,

         "SuccessorUid":74,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/54",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":54,

         "PredecessorUid":68,

         "SuccessorUid":75,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/55",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":55,

         "PredecessorUid":75,

         "SuccessorUid":77,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/56",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":56,

         "PredecessorUid":73,

         "SuccessorUid":77,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/57",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":57,

         "PredecessorUid":77,

         "SuccessorUid":81,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/58",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":58,

         "PredecessorUid":77,

         "SuccessorUid":82,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/59",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":59,

         "PredecessorUid":77,

         "SuccessorUid":83,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/60",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":60,

         "PredecessorUid":83,

         "SuccessorUid":84,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/61",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":61,

         "PredecessorUid":83,

         "SuccessorUid":85,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/62",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":62,

         "PredecessorUid":83,

         "SuccessorUid":86,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/63",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":63,

         "PredecessorUid":86,

         "SuccessorUid":88,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/64",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":64,

         "PredecessorUid":86,

         "SuccessorUid":89,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/65",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":65,

         "PredecessorUid":86,

         "SuccessorUid":90,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/66",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":66,

         "PredecessorUid":86,

         "SuccessorUid":91,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/67",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":67,

         "PredecessorUid":86,

         "SuccessorUid":92,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/68",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":68,

         "PredecessorUid":86,

         "SuccessorUid":93,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/69",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":69,

         "PredecessorUid":93,

         "SuccessorUid":95,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/70",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":70,

         "PredecessorUid":93,

         "SuccessorUid":96,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/71",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":71,

         "PredecessorUid":93,

         "SuccessorUid":97,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/72",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":72,

         "PredecessorUid":93,

         "SuccessorUid":99,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/73",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":73,

         "PredecessorUid":93,

         "SuccessorUid":100,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/74",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":74,

         "PredecessorUid":100,

         "SuccessorUid":103,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/75",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":75,

         "PredecessorUid":100,

         "SuccessorUid":104,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/76",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":76,

         "PredecessorUid":100,

         "SuccessorUid":105,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/77",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":77,

         "PredecessorUid":100,

         "SuccessorUid":106,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/78",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":78,

         "PredecessorUid":100,

         "SuccessorUid":107,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/79",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":79,

         "PredecessorUid":107,

         "SuccessorUid":109,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/80",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":80,

         "PredecessorUid":107,

         "SuccessorUid":110,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/81",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":81,

         "PredecessorUid":107,

         "SuccessorUid":111,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/82",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":82,

         "PredecessorUid":111,

         "SuccessorUid":113,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/83",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":83,

         "PredecessorUid":111,

         "SuccessorUid":114,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/84",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":84,

         "PredecessorUid":111,

         "SuccessorUid":115,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/85",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":85,

         "PredecessorUid":111,

         "SuccessorUid":116,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/86",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":86,

         "PredecessorUid":111,

         "SuccessorUid":117,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/87",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":87,

         "PredecessorUid":111,

         "SuccessorUid":118,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/88",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":88,

         "PredecessorUid":111,

         "SuccessorUid":119,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/89",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":89,

         "PredecessorUid":111,

         "SuccessorUid":120,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/90",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":90,

         "PredecessorUid":111,

         "SuccessorUid":121,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/91",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":91,

         "PredecessorUid":121,

         "SuccessorUid":123,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/92",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":92,

         "PredecessorUid":121,

         "SuccessorUid":124,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/93",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":93,

         "PredecessorUid":121,

         "SuccessorUid":125,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/94",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":94,

         "PredecessorUid":121,

         "SuccessorUid":126,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/95",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":95,

         "PredecessorUid":121,

         "SuccessorUid":127,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/96",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":96,

         "PredecessorUid":121,

         "SuccessorUid":128,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/97",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":97,

         "PredecessorUid":121,

         "SuccessorUid":129,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/98",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":98,

         "PredecessorUid":129,

         "SuccessorUid":133,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/99",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":99,

         "PredecessorUid":129,

         "SuccessorUid":134,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/100",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":100,

         "PredecessorUid":129,

         "SuccessorUid":135,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/101",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":101,

         "PredecessorUid":129,

         "SuccessorUid":136,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/102",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":102,

         "PredecessorUid":129,

         "SuccessorUid":137,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/103",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":103,

         "PredecessorUid":129,

         "SuccessorUid":138,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/104",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":104,

         "PredecessorUid":129,

         "SuccessorUid":141,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/105",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":105,

         "PredecessorUid":129,

         "SuccessorUid":142,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/106",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":106,

         "PredecessorUid":129,

         "SuccessorUid":143,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/107",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":107,

         "PredecessorUid":129,

         "SuccessorUid":145,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/108",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":108,

         "PredecessorUid":129,

         "SuccessorUid":146,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/109",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":109,

         "PredecessorUid":129,

         "SuccessorUid":147,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/110",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":110,

         "PredecessorUid":129,

         "SuccessorUid":148,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/111",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":111,

         "PredecessorUid":129,

         "SuccessorUid":149,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/112",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":112,

         "PredecessorUid":129,

         "SuccessorUid":150,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/113",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":113,

         "PredecessorUid":129,

         "SuccessorUid":151,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/114",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":114,

         "PredecessorUid":151,

         "SuccessorUid":152,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/115",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":115,

         "PredecessorUid":152,

         "SuccessorUid":156,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/116",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":116,

         "PredecessorUid":156,

         "SuccessorUid":158,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/117",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":117,

         "PredecessorUid":158,

         "SuccessorUid":159,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/118",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":118,

         "PredecessorUid":158,

         "SuccessorUid":160,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/119",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":119,

         "PredecessorUid":160,

         "SuccessorUid":162,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/120",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":120,

         "PredecessorUid":160,

         "SuccessorUid":163,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/121",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":121,

         "PredecessorUid":160,

         "SuccessorUid":164,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/122",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":122,

         "PredecessorUid":160,

         "SuccessorUid":165,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/123",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":123,

         "PredecessorUid":165,

         "SuccessorUid":167,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/124",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":124,

         "PredecessorUid":165,

         "SuccessorUid":168,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/125",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":125,

         "PredecessorUid":165,

         "SuccessorUid":169,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/126",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":126,

         "PredecessorUid":165,

         "SuccessorUid":170,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      },

      {

         "Link":{

            "Href":"/taskLinks/127",

            "Rel":"self",

            "Type":null,

            "Title":null

         },

         "Index":127,

         "PredecessorUid":170,

         "SuccessorUid":171,

         "LinkType":"FinishToStart",

         "Lag":0,

         "LagFormat":"Day"

      }

   ],

   "Code":200,

   "Status":"OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNET-CSharp-TaskLinks-RetrieveTaskLinkInformation-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-tasks-TaskLinksProjectExample-TaskLinksProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-TaskLinks-GetTaskLinks-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-TaskLinks-get\_task\_links-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-tasks-TaskLinksProjectExample-TaskLinksProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-TaskLinks-RetrieveTaskLinkInformation-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "0d8fcd760c1c8c6d8ab66530c8779d20" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "0009a7d47e87b73a12bda5200ff45ce2" >}}

{{< /tab >}}

{{< /tabs >}}
