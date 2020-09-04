---
title: "Get Project Calendar Items"
type: docs
url: /get-project-calendar-items/
weight: 10
---

# **Introduction**
This example explains how to read information regarding a project calendar items. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars|GET|Read Calendar information from|[GetCalendars](https://apireference.aspose.cloud/tasks/#/TasksCalendar/GetCalendars)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjMzMDY0MTgsImV4cCI6MTU2MzM5MjgxOCwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.MsIBVeVaYmx2nl8SQwNDxh1VbqojZgx287czkTUQp281ps55UnLoecpyiVJrSOKJooppGt\_dTnugj3ia8eO0eRww3OA1vDsiEje5asZGAnLL4AUeM\_2ka9n00UGzASWzuG5V4IuZir4TzpyveEYHWKER8XSyNF4JJ\_qD-09TqdLOFQAF2RPN0zFKT-HQ-Ja7d4ODyyob2eU3-6ezaxfPm5YT\_SnR8xPjLM\_CvtqvJROQOo9oQk6nnDal4lKDVmJ6iMo9B9Sg0gEY6Vg54Cr9fIHhuZLe7yJAwgSjJEBJ2c\_BWMsAdcjtCXwd9LPxWeCPD9kHYu6-9GvrC7XZ8blCqg"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {

   "Calendars":{

      "List":[

         {

            "Link":{

               "Href":"/1",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":1,

            "Name":"Standard"

         }

      ],

      "link":{

         "Href":"/calendars",

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

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetCalendars.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< /tab >}}

{{< /tabs >}}
