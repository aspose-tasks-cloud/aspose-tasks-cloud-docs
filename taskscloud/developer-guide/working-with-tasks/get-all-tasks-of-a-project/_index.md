---
title: "Get all Tasks of a Project"
type: docs
url: /get-all-tasks-of-a-project/
weight: 10
---

# **Introduction**
This example explains how read task information from a MS Project File. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks|GET|Read project's tasks|[GetTasks](https://apireference.aspose.cloud/tasks/#/TasksTask/GetTasks)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/tasks" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjMzMDY0MTgsImV4cCI6MTU2MzM5MjgxOCwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.MsIBVeVaYmx2nl8SQwNDxh1VbqojZgx287czkTUQp281ps55UnLoecpyiVJrSOKJooppGt\_dTnugj3ia8eO0eRww3OA1vDsiEje5asZGAnLL4AUeM\_2ka9n00UGzASWzuG5V4IuZir4TzpyveEYHWKER8XSyNF4JJ\_qD-09TqdLOFQAF2RPN0zFKT-HQ-Ja7d4ODyyob2eU3-6ezaxfPm5YT\_SnR8xPjLM\_CvtqvJROQOo9oQk6nnDal4lKDVmJ6iMo9B9Sg0gEY6Vg54Cr9fIHhuZLe7yJAwgSjJEBJ2c\_BWMsAdcjtCXwd9LPxWeCPD9kHYu6-9GvrC7XZ8blCqg"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {

   "Tasks":{

      "TaskItem":[

         {

            "Link":{

               "Href":"/0",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":0,

            "Id":0,

            "Name":"Home Move",

            "Start":"2004-01-01T08:00:00",

            "Finish":"2004-03-01T17:00:00",

            "Duration":"14.08:00:00"

         },

         {

            "Link":{

               "Href":"/1",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":1,

            "Id":1,

            "Name":"Five to Eight Weeks Before Moving",

            "Start":"2004-01-01T08:00:00",

            "Finish":"2004-01-22T17:00:00",

            "Duration":"5.08:00:00"

         },

         {

            "Link":{

               "Href":"/2",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":2,

            "Id":2,

            "Name":"Planning the Move",

            "Start":"2004-01-01T08:00:00",

            "Finish":"2004-01-05T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/3",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":3,

            "Id":3,

            "Name":"Calculate moving expenses",

            "Start":"2004-01-01T08:00:00",

            "Finish":"2004-01-01T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/4",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":4,

            "Id":4,

            "Name":"Determine the best method of moving",

            "Start":"2004-01-02T08:00:00",

            "Finish":"2004-01-05T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/5",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":5,

            "Id":5,

            "Name":"Create a moving-expense receipt file",

            "Start":"2004-01-02T08:00:00",

            "Finish":"2004-01-02T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/6",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":6,

            "Id":6,

            "Name":"Create a moving binder",

            "Start":"2004-01-02T08:00:00",

            "Finish":"2004-01-02T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/7",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":7,

            "Id":7,

            "Name":"Household Administration",

            "Start":"2004-01-05T08:00:00",

            "Finish":"2004-01-12T17:00:00",

            "Duration":"2.00:00:00"

         },

         {

            "Link":{

               "Href":"/8",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":8,

            "Id":8,

            "Name":"Finances and Insurance",

            "Start":"2004-01-05T08:00:00",

            "Finish":"2004-01-06T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/9",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":9,

            "Id":9,

            "Name":"Review household finances",

            "Start":"2004-01-06T08:00:00",

            "Finish":"2004-01-06T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/10",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":10,

            "Id":10,

            "Name":"Verify that your belongings are insured for the move",

            "Start":"2004-01-05T08:00:00",

            "Finish":"2004-01-05T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/11",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":11,

            "Id":11,

            "Name":"Appraise valuables specifically insured for the move",

            "Start":"2004-01-05T08:00:00",

            "Finish":"2004-01-06T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/12",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":12,

            "Id":12,

            "Name":"Transfer insurance policies to your new address",

            "Start":"2004-01-05T08:00:00",

            "Finish":"2004-01-05T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/13",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":13,

            "Id":13,

            "Name":"Transfer medical insurance to your new location",

            "Start":"2004-01-05T08:00:00",

            "Finish":"2004-01-05T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/14",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":14,

            "Id":14,

            "Name":"Notifications",

            "Start":"2004-01-06T08:00:00",

            "Finish":"2004-01-07T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/15",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":15,

            "Id":15,

            "Name":"Notify your employer of your moving dates and new address",

            "Start":"2004-01-06T08:00:00",

            "Finish":"2004-01-06T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/16",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":16,

            "Id":16,

            "Name":"Transfer, sell, or discontinue any memberships",

            "Start":"2004-01-06T08:00:00",

            "Finish":"2004-01-07T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/17",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":17,

            "Id":17,

            "Name":"Vital Services and Records",

            "Start":"2004-01-08T08:00:00",

            "Finish":"2004-01-09T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/18",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":18,

            "Id":18,

            "Name":"Organize important records",

            "Start":"2004-01-08T08:00:00",

            "Finish":"2004-01-09T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/19",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":19,

            "Id":19,

            "Name":"Contact your doctor, dentist, and vet for referrals",

            "Start":"2004-01-08T08:00:00",

            "Finish":"2004-01-08T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/20",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":20,

            "Id":20,

            "Name":"Request additional refills of vital medications",

            "Start":"2004-01-08T08:00:00",

            "Finish":"2004-01-08T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/21",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":21,

            "Id":21,

            "Name":"Your New Residence",

            "Start":"2004-01-09T08:00:00",

            "Finish":"2004-01-12T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/22",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":22,

            "Id":22,

            "Name":"Collect shopping and dining guides from your new community",

            "Start":"2004-01-09T08:00:00",

            "Finish":"2004-01-12T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/23",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":23,

            "Id":23,

            "Name":"Determine the location of the police, fire department and hospitals",

            "Start":"2004-01-09T08:00:00",

            "Finish":"2004-01-09T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/24",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":24,

            "Id":24,

            "Name":"Change drivers/vehicle license address if required",

            "Start":"2004-01-09T08:00:00",

            "Finish":"2004-01-09T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/25",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":25,

            "Id":25,

            "Name":"Place orders for new furniture",

            "Start":"2004-01-09T08:00:00",

            "Finish":"2004-01-12T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/26",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":26,

            "Id":26,

            "Name":"Moving",

            "Start":"2004-01-13T08:00:00",

            "Finish":"2004-01-22T17:00:00",

            "Duration":"2.16:00:00"

         },

         {

            "Link":{

               "Href":"/27",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":27,

            "Id":27,

            "Name":"Movers",

            "Start":"2004-01-13T08:00:00",

            "Finish":"2004-01-16T17:00:00",

            "Duration":"1.08:00:00"

         },

         {

            "Link":{

               "Href":"/28",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":28,

            "Id":28,

            "Name":"Obtain estimates from several moving services",

            "Start":"2004-01-13T08:00:00",

            "Finish":"2004-01-16T17:00:00",

            "Duration":"1.08:00:00"

         },

         {

            "Link":{

               "Href":"/29",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":29,

            "Id":29,

            "Name":"Request references from each moving service",

            "Start":"2004-01-13T08:00:00",

            "Finish":"2004-01-13T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/30",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":30,

            "Id":30,

            "Name":"Select moving service",

            "Start":"2004-01-13T08:00:00",

            "Finish":"2004-01-13T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/31",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":31,

            "Id":31,

            "Name":"Discuss rough details with movers",

            "Start":"2004-01-13T08:00:00",

            "Finish":"2004-01-13T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/32",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":32,

            "Id":32,

            "Name":"Packing",

            "Start":"2004-01-14T08:00:00",

            "Finish":"2004-01-22T17:00:00",

            "Duration":"2.08:00:00"

         },

         {

            "Link":{

               "Href":"/33",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":33,

            "Id":33,

            "Name":"Inventory and organize all possessions",

            "Start":"2004-01-14T08:00:00",

            "Finish":"2004-01-22T17:00:00",

            "Duration":"2.08:00:00"

         },

         {

            "Link":{

               "Href":"/34",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":34,

            "Id":34,

            "Name":"Begin using food and cleaning supplies currently on hand",

            "Start":"2004-01-14T08:00:00",

            "Finish":"2004-01-14T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/35",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":35,

            "Id":35,

            "Name":"Start cleaning closets, bookcases, and other storage areas",

            "Start":"2004-01-14T08:00:00",

            "Finish":"2004-01-20T17:00:00",

            "Duration":"1.16:00:00"

         },

         {

            "Link":{

               "Href":"/36",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":36,

            "Id":36,

            "Name":"Conduct a sale or donate to charity",

            "Start":"2004-01-14T08:00:00",

            "Finish":"2004-01-16T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/37",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":37,

            "Id":37,

            "Name":"Decide what furniture items you want to keep",

            "Start":"2004-01-14T08:00:00",

            "Finish":"2004-01-19T17:00:00",

            "Duration":"1.08:00:00"

         },

         {

            "Link":{

               "Href":"/38",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":38,

            "Id":38,

            "Name":"Reserve storage if necessary",

            "Start":"2004-01-14T08:00:00",

            "Finish":"2004-01-14T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/39",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":39,

            "Id":39,

            "Name":"Preparing for Moving Day",

            "Start":"2004-01-15T08:00:00",

            "Finish":"2004-01-19T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/40",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":40,

            "Id":40,

            "Name":"Make any long distance travel arrangements",

            "Start":"2004-01-15T08:00:00",

            "Finish":"2004-01-19T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/41",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":41,

            "Id":41,

            "Name":"Three to Five Weeks Before Moving",

            "Start":"2004-01-20T08:00:00",

            "Finish":"2004-02-06T17:00:00",

            "Duration":"4.16:00:00"

         },

         {

            "Link":{

               "Href":"/42",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":42,

            "Id":42,

            "Name":"Household Administration",

            "Start":"2004-01-20T08:00:00",

            "Finish":"2004-01-26T17:00:00",

            "Duration":"1.16:00:00"

         },

         {

            "Link":{

               "Href":"/43",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":43,

            "Id":43,

            "Name":"Finances and Insurance",

            "Start":"2004-01-20T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"1.08:00:00"

         },

         {

            "Link":{

               "Href":"/44",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":44,

            "Id":44,

            "Name":"Research and choose bank at the new location",

            "Start":"2004-01-20T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"1.08:00:00"

         },

         {

            "Link":{

               "Href":"/45",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":45,

            "Id":45,

            "Name":"Open new bank account",

            "Start":"2004-01-20T08:00:00",

            "Finish":"2004-01-20T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/46",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":46,

            "Id":46,

            "Name":"Order bank checks with your new address",

            "Start":"2004-01-20T08:00:00",

            "Finish":"2004-01-20T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/47",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":47,

            "Id":47,

            "Name":"Close any local charge accounts",

            "Start":"2004-01-20T08:00:00",

            "Finish":"2004-01-20T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/48",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":48,

            "Id":48,

            "Name":"Notifications",

            "Start":"2004-01-21T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/49",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":49,

            "Id":49,

            "Name":"Schedule disconnection of utilities",

            "Start":"2004-01-21T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/50",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":50,

            "Id":50,

            "Name":"Change your address with government agencies if required",

            "Start":"2004-01-21T08:00:00",

            "Finish":"2004-01-21T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/51",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":51,

            "Id":51,

            "Name":"Clear up any unpaid taxes or parking tickets",

            "Start":"2004-01-21T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/52",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":52,

            "Id":52,

            "Name":"Transfer car registration to your new location",

            "Start":"2004-01-21T08:00:00",

            "Finish":"2004-01-21T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/53",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":53,

            "Id":53,

            "Name":"Vital Services and Records",

            "Start":"2004-01-22T08:00:00",

            "Finish":"2004-01-26T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/54",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":54,

            "Id":54,

            "Name":"Register your children in their new schools",

            "Start":"2004-01-22T08:00:00",

            "Finish":"2004-01-26T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/55",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":55,

            "Id":55,

            "Name":"Forward children's school records to the new school district",

            "Start":"2004-01-22T08:00:00",

            "Finish":"2004-01-22T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/56",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":56,

            "Id":56,

            "Name":"Your New Residence",

            "Start":"2004-01-23T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/57",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":57,

            "Id":57,

            "Name":"Order mailing labels with your new address",

            "Start":"2004-01-23T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/58",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":58,

            "Id":58,

            "Name":"Determine if there are pet requirements at the new location",

            "Start":"2004-01-23T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/59",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":59,

            "Id":59,

            "Name":"Schedule move with the building management at the new location",

            "Start":"2004-01-23T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/60",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":60,

            "Id":60,

            "Name":"Schedule cable television installation if required",

            "Start":"2004-01-23T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/61",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":61,

            "Id":61,

            "Name":"Schedule internet installation if required",

            "Start":"2004-01-23T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/62",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":62,

            "Id":62,

            "Name":"Contact utility companies and sign up for new service",

            "Start":"2004-01-23T08:00:00",

            "Finish":"2004-01-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/63",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":63,

            "Id":63,

            "Name":"Moving",

            "Start":"2004-01-26T08:00:00",

            "Finish":"2004-02-06T17:00:00",

            "Duration":"3.08:00:00"

         },

         {

            "Link":{

               "Href":"/64",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":64,

            "Id":64,

            "Name":"Movers",

            "Start":"2004-01-26T08:00:00",

            "Finish":"2004-01-26T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/65",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":65,

            "Id":65,

            "Name":"Confirm your move date with your moving service",

            "Start":"2004-01-26T08:00:00",

            "Finish":"2004-01-26T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/66",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":66,

            "Id":66,

            "Name":"Do-It-Yourself",

            "Start":"2004-01-27T08:00:00",

            "Finish":"2004-01-29T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/67",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":67,

            "Id":67,

            "Name":"Reserve a truck or trailer",

            "Start":"2004-01-27T08:00:00",

            "Finish":"2004-01-27T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/68",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":68,

            "Id":68,

            "Name":"Begin enlisting assistance for moving day",

            "Start":"2004-01-27T08:00:00",

            "Finish":"2004-01-29T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/69",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":69,

            "Id":69,

            "Name":"Packing",

            "Start":"2004-01-27T08:00:00",

            "Finish":"2004-02-05T17:00:00",

            "Duration":"2.16:00:00"

         },

         {

            "Link":{

               "Href":"/70",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":70,

            "Id":70,

            "Name":"Start collecting boxes, tape, and padding",

            "Start":"2004-01-27T08:00:00",

            "Finish":"2004-02-05T17:00:00",

            "Duration":"2.16:00:00"

         },

         {

            "Link":{

               "Href":"/71",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":71,

            "Id":71,

            "Name":"Arrange for disposal of items not sold or donated",

            "Start":"2004-01-30T08:00:00",

            "Finish":"2004-02-02T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/72",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":72,

            "Id":72,

            "Name":"Begin letting children do some of their own packing and labeling",

            "Start":"2004-01-30T08:00:00",

            "Finish":"2004-02-04T17:00:00",

            "Duration":"1.08:00:00"

         },

         {

            "Link":{

               "Href":"/73",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":73,

            "Id":73,

            "Name":"Begin packing books, seasonal clothing, or sporting equipment",

            "Start":"2004-01-30T08:00:00",

            "Finish":"2004-02-05T17:00:00",

            "Duration":"1.16:00:00"

         },

         {

            "Link":{

               "Href":"/74",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":74,

            "Id":74,

            "Name":"Send furniture, drapes, and carpets for repair or cleaning",

            "Start":"2004-01-30T08:00:00",

            "Finish":"2004-01-30T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/75",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":75,

            "Id":75,

            "Name":"Have appliances serviced for moving, if applicable",

            "Start":"2004-01-30T08:00:00",

            "Finish":"2004-02-02T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/76",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":76,

            "Id":76,

            "Name":"Preparing for Moving Day",

            "Start":"2004-02-06T08:00:00",

            "Finish":"2004-02-06T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/77",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":77,

            "Id":77,

            "Name":"Arrange for child care the day of the move",

            "Start":"2004-02-06T08:00:00",

            "Finish":"2004-02-06T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/78",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":78,

            "Id":78,

            "Name":"One to Two Weeks Before Moving",

            "Start":"2004-02-09T08:00:00",

            "Finish":"2004-02-20T17:00:00",

            "Duration":"3.08:00:00"

         },

         {

            "Link":{

               "Href":"/79",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":79,

            "Id":79,

            "Name":"Household Administration",

            "Start":"2004-02-09T08:00:00",

            "Finish":"2004-02-13T17:00:00",

            "Duration":"1.16:00:00"

         },

         {

            "Link":{

               "Href":"/80",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":80,

            "Id":80,

            "Name":"Finances and Insurance",

            "Start":"2004-02-09T08:00:00",

            "Finish":"2004-02-10T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/81",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":81,

            "Id":81,

            "Name":"Transfer your bank accounts to new bank or new location",

            "Start":"2004-02-09T08:00:00",

            "Finish":"2004-02-09T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/82",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":82,

            "Id":82,

            "Name":"Close existing bank accounts at old location",

            "Start":"2004-02-09T08:00:00",

            "Finish":"2004-02-09T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/83",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":83,

            "Id":83,

            "Name":"Empty safe-deposit box",

            "Start":"2004-02-09T08:00:00",

            "Finish":"2004-02-09T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/84",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":84,

            "Id":84,

            "Name":"Organize appliance documents",

            "Start":"2004-02-10T08:00:00",

            "Finish":"2004-02-10T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/85",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":85,

            "Id":85,

            "Name":"Make arrangements to pay for your move",

            "Start":"2004-02-10T08:00:00",

            "Finish":"2004-02-10T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/86",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":86,

            "Id":86,

            "Name":"Buy traveler's checks",

            "Start":"2004-02-10T08:00:00",

            "Finish":"2004-02-10T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/87",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":87,

            "Id":87,

            "Name":"Notifications",

            "Start":"2004-02-11T08:00:00",

            "Finish":"2004-02-13T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/88",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":88,

            "Id":88,

            "Name":"Fill out mail change of address cards",

            "Start":"2004-02-11T08:00:00",

            "Finish":"2004-02-13T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/89",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":89,

            "Id":89,

            "Name":"Distribute new address",

            "Start":"2004-02-11T08:00:00",

            "Finish":"2004-02-11T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/90",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":90,

            "Id":90,

            "Name":"If no longer required, cancel local deliveries",

            "Start":"2004-02-11T08:00:00",

            "Finish":"2004-02-11T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/91",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":91,

            "Id":91,

            "Name":"Cancel newspaper delivery",

            "Start":"2004-02-11T08:00:00",

            "Finish":"2004-02-11T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/92",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":92,

            "Id":92,

            "Name":"Take trash to dump or recycling center",

            "Start":"2004-02-11T08:00:00",

            "Finish":"2004-02-11T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/93",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":93,

            "Id":93,

            "Name":"Coordinate with friend to act as your message center",

            "Start":"2004-02-11T08:00:00",

            "Finish":"2004-02-12T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/94",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":94,

            "Id":94,

            "Name":"Vital Services and Records",

            "Start":"2004-02-13T08:00:00",

            "Finish":"2004-02-13T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/95",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":95,

            "Id":95,

            "Name":"Have medical and dental records forwarded",

            "Start":"2004-02-13T08:00:00",

            "Finish":"2004-02-13T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/96",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":96,

            "Id":96,

            "Name":"Contact your pharmacist for referral",

            "Start":"2004-02-13T08:00:00",

            "Finish":"2004-02-13T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/97",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":97,

            "Id":97,

            "Name":"Transfer your prescriptions to this new pharmacy",

            "Start":"2004-02-13T08:00:00",

            "Finish":"2004-02-13T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/98",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":98,

            "Id":98,

            "Name":"Your New Residence",

            "Start":"2004-02-13T08:00:00",

            "Finish":"2004-02-13T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/99",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":99,

            "Id":99,

            "Name":"Contact previous residents for appliance documentation",

            "Start":"2004-02-13T08:00:00",

            "Finish":"2004-02-13T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/100",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":100,

            "Id":100,

            "Name":"Subscribe to the local newspapers and community newsletters",

            "Start":"2004-02-13T08:00:00",

            "Finish":"2004-02-13T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/101",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":101,

            "Id":101,

            "Name":"Moving",

            "Start":"2004-02-16T08:00:00",

            "Finish":"2004-02-20T17:00:00",

            "Duration":"1.16:00:00"

         },

         {

            "Link":{

               "Href":"/102",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":102,

            "Id":102,

            "Name":"Movers",

            "Start":"2004-02-16T08:00:00",

            "Finish":"2004-02-16T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/103",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":103,

            "Id":103,

            "Name":"Check with mover about moving house plants",

            "Start":"2004-02-16T08:00:00",

            "Finish":"2004-02-16T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/104",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":104,

            "Id":104,

            "Name":"Obtain moving service contact numbers",

            "Start":"2004-02-16T08:00:00",

            "Finish":"2004-02-16T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/105",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":105,

            "Id":105,

            "Name":"Acquire labels for boxes (for example, Fragile, Load First, Load Last)",

            "Start":"2004-02-16T08:00:00",

            "Finish":"2004-02-16T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/106",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":106,

            "Id":106,

            "Name":"Verify that the moving service has your contact numbers",

            "Start":"2004-02-16T08:00:00",

            "Finish":"2004-02-16T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/107",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":107,

            "Id":107,

            "Name":"Give moving service written directions to the new location",

            "Start":"2004-02-16T08:00:00",

            "Finish":"2004-02-16T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/108",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":108,

            "Id":108,

            "Name":"Do-It-Yourself",

            "Start":"2004-02-17T08:00:00",

            "Finish":"2004-02-17T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/109",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":109,

            "Id":109,

            "Name":"Move possessions to storage facility if necessary",

            "Start":"2004-02-17T08:00:00",

            "Finish":"2004-02-17T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/110",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":110,

            "Id":110,

            "Name":"Confirm assistance for moving day",

            "Start":"2004-02-17T08:00:00",

            "Finish":"2004-02-17T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/111",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":111,

            "Id":111,

            "Name":"Verify dolly available with truck rental",

            "Start":"2004-02-17T08:00:00",

            "Finish":"2004-02-17T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/112",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":112,

            "Id":112,

            "Name":"Packing",

            "Start":"2004-02-18T08:00:00",

            "Finish":"2004-02-20T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/113",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":113,

            "Id":113,

            "Name":"Clean appliances",

            "Start":"2004-02-18T08:00:00",

            "Finish":"2004-02-18T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/114",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":114,

            "Id":114,

            "Name":"Pick up all dry cleaning",

            "Start":"2004-02-18T08:00:00",

            "Finish":"2004-02-18T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/115",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":115,

            "Id":115,

            "Name":"Pack items that you do not use regularly",

            "Start":"2004-02-18T08:00:00",

            "Finish":"2004-02-20T17:00:00",

            "Duration":"1.00:00:00"

         },

         {

            "Link":{

               "Href":"/116",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":116,

            "Id":116,

            "Name":"Pack all valuables to move personally",

            "Start":"2004-02-18T08:00:00",

            "Finish":"2004-02-19T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/117",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":117,

            "Id":117,

            "Name":"Locate hazardous waste disposal sites",

            "Start":"2004-02-18T08:00:00",

            "Finish":"2004-02-18T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/118",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":118,

            "Id":118,

            "Name":"Drain all fluids from your lawn mower and power tools",

            "Start":"2004-02-18T08:00:00",

            "Finish":"2004-02-19T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/119",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":119,

            "Id":119,

            "Name":"Dispose of all hazardous household materials",

            "Start":"2004-02-18T08:00:00",

            "Finish":"2004-02-19T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/120",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":120,

            "Id":120,

            "Name":"Have mover pack your goods (unless doing it yourself)",

            "Start":"2004-02-18T08:00:00",

            "Finish":"2004-02-18T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/121",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":121,

            "Id":121,

            "Name":"Pack travel bags and confirm travel arrangements",

            "Start":"2004-02-18T08:00:00",

            "Finish":"2004-02-18T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/122",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":122,

            "Id":122,

            "Name":"Preparing for Move Day",

            "Start":"2004-02-19T08:00:00",

            "Finish":"2004-02-20T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/123",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":123,

            "Id":123,

            "Name":"Have your automobile serviced if you're traveling by car",

            "Start":"2004-02-19T08:00:00",

            "Finish":"2004-02-19T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/124",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":124,

            "Id":124,

            "Name":"Plan auto route",

            "Start":"2004-02-19T08:00:00",

            "Finish":"2004-02-19T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/125",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":125,

            "Id":125,

            "Name":"Plan meals that will use up the food in your freezer",

            "Start":"2004-02-19T08:00:00",

            "Finish":"2004-02-19T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/126",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":126,

            "Id":126,

            "Name":"Empty, defrost, and clean refrigerator and freezer",

            "Start":"2004-02-19T08:00:00",

            "Finish":"2004-02-20T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/127",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":127,

            "Id":127,

            "Name":"Prepare a survival kit for move day",

            "Start":"2004-02-19T08:00:00",

            "Finish":"2004-02-19T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/128",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":128,

            "Id":128,

            "Name":"Prepare your pet's survival kit",

            "Start":"2004-02-19T08:00:00",

            "Finish":"2004-02-19T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/129",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":129,

            "Id":129,

            "Name":"Prepare an immediate-need kit for move day",

            "Start":"2004-02-19T08:00:00",

            "Finish":"2004-02-20T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/130",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":130,

            "Id":130,

            "Name":"Day of the Move",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/131",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":131,

            "Id":131,

            "Name":"Old Residence",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/132",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":132,

            "Id":132,

            "Name":"Moving",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/133",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":133,

            "Id":133,

            "Name":"Have tools, tape, twine, and spare boxes on hand",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/134",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":134,

            "Id":134,

            "Name":"Be present throughout the entire move",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/135",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":135,

            "Id":135,

            "Name":"Verify all possessions have been packed and loaded",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/136",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":136,

            "Id":136,

            "Name":"Make sure fragile items are handled carefully",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/137",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":137,

            "Id":137,

            "Name":"Pack cleaning supplies including a vacuum cleaner in a box labeled Last Load",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/138",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":138,

            "Id":138,

            "Name":"Verify that bedding gets packed last",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/139",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":139,

            "Id":139,

            "Name":"New Residence",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/140",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":140,

            "Id":140,

            "Name":"Household Administration",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/141",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":141,

            "Id":141,

            "Name":"Empty, defrost, and clean the new refrigerator",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/142",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":142,

            "Id":142,

            "Name":"Designate a room for your pet",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/143",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":143,

            "Id":143,

            "Name":"Have snacks and beverages on hand throughout the day",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/144",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":144,

            "Id":144,

            "Name":"Moving",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/145",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":145,

            "Id":145,

            "Name":"Be present throughout the entire move",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/146",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":146,

            "Id":146,

            "Name":"Make sure fragile items are handled carefully",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/147",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":147,

            "Id":147,

            "Name":"Review all paperwork when the moving service arrives",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/148",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":148,

            "Id":148,

            "Name":"Pay moving service before unpacking",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/149",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":149,

            "Id":149,

            "Name":"Check carefully for any damaged or missing items",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/150",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":150,

            "Id":150,

            "Name":"Read and sign bill of lading",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/151",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":151,

            "Id":151,

            "Name":"Retain copies of the bill of lading and inventory",

            "Start":"2004-02-23T08:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/152",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":152,

            "Id":152,

            "Name":"Move completed",

            "Start":"2004-02-23T17:00:00",

            "Finish":"2004-02-23T17:00:00",

            "Duration":"00:00:00"

         },

         {

            "Link":{

               "Href":"/153",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":153,

            "Id":153,

            "Name":"One to Two Weeks After the Move",

            "Start":"2004-02-24T08:00:00",

            "Finish":"2004-03-01T17:00:00",

            "Duration":"1.16:00:00"

         },

         {

            "Link":{

               "Href":"/154",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":154,

            "Id":154,

            "Name":"Household Administration",

            "Start":"2004-02-24T08:00:00",

            "Finish":"2004-03-01T17:00:00",

            "Duration":"1.16:00:00"

         },

         {

            "Link":{

               "Href":"/155",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":155,

            "Id":155,

            "Name":"Finances and Insurance",

            "Start":"2004-02-24T08:00:00",

            "Finish":"2004-02-24T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/156",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":156,

            "Id":156,

            "Name":"Put valuables into a safety deposit box in the new bank",

            "Start":"2004-02-24T08:00:00",

            "Finish":"2004-02-24T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/157",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":157,

            "Id":157,

            "Name":"Notifications",

            "Start":"2004-02-25T08:00:00",

            "Finish":"2004-02-26T17:00:00",

            "Duration":"16:00:00"

         },

         {

            "Link":{

               "Href":"/158",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":158,

            "Id":158,

            "Name":"Arrange for new registration of cars (bicycles also, if required)",

            "Start":"2004-02-25T08:00:00",

            "Finish":"2004-02-25T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/159",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":159,

            "Id":159,

            "Name":"Have pets licensed",

            "Start":"2004-02-26T08:00:00",

            "Finish":"2004-02-26T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/160",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":160,

            "Id":160,

            "Name":"Change your voter registration, if required",

            "Start":"2004-02-26T08:00:00",

            "Finish":"2004-02-26T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/161",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":161,

            "Id":161,

            "Name":"Vital Services and Records",

            "Start":"2004-02-27T08:00:00",

            "Finish":"2004-02-27T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/162",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":162,

            "Id":162,

            "Name":"Contact new dentists and doctors to verify record delivery",

            "Start":"2004-02-27T08:00:00",

            "Finish":"2004-02-27T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/163",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":163,

            "Id":163,

            "Name":"Get recommendations for babysitters, nanny agencies, and other services",

            "Start":"2004-02-27T08:00:00",

            "Finish":"2004-02-27T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/164",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":164,

            "Id":164,

            "Name":"Verify that new schools have received records",

            "Start":"2004-02-27T08:00:00",

            "Finish":"2004-02-27T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/165",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":165,

            "Id":165,

            "Name":"Update driver's license and car license plates",

            "Start":"2004-02-27T08:00:00",

            "Finish":"2004-02-27T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/166",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":166,

            "Id":166,

            "Name":"Your New Residence",

            "Start":"2004-03-01T08:00:00",

            "Finish":"2004-03-01T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/167",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":167,

            "Id":167,

            "Name":"Make additional sets of keys and change locks if necessary",

            "Start":"2004-03-01T08:00:00",

            "Finish":"2004-03-01T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/168",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":168,

            "Id":168,

            "Name":"Ask for repair service recommendations",

            "Start":"2004-03-01T08:00:00",

            "Finish":"2004-03-01T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/169",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":169,

            "Id":169,

            "Name":"Meet your neighbors (write down their names)",

            "Start":"2004-03-01T08:00:00",

            "Finish":"2004-03-01T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/170",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":170,

            "Id":170,

            "Name":"Find out about recycling at the new location",

            "Start":"2004-03-01T08:00:00",

            "Finish":"2004-03-01T17:00:00",

            "Duration":"08:00:00"

         },

         {

            "Link":{

               "Href":"/171",

               "Rel":"self",

               "Type":null,

               "Title":null

            },

            "Uid":171,

            "Id":171,

            "Name":"Enjoy your new home",

            "Start":"2004-03-01T17:00:00",

            "Finish":"2004-03-01T17:00:00",

            "Duration":"00:00:00"

         }

      ],

      "link":{

         "Href":"/tasks",

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

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetTasks.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< /tab >}}

{{< /tabs >}}
