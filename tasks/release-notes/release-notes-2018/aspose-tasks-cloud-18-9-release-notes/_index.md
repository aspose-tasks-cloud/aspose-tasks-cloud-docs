---
title: "Aspose.Tasks Cloud 18.9 Release Notes"
type: docs
url: /aspose-tasks-cloud-18-9-release-notes/
weight: 10
---

{{% alert color="primary" %}} 

This page contains release notes of Aspose.Tasks Cloud 18.9 - [API Reference](https://apireference.aspose.cloud/tasks/)

{{% /alert %}} 
## **Important Changes and New Features**
**1.** Duration type was added:

**Example**

```html

{

  "TimeSpan": "10:00:00",

  "TimeUnit": "Hour"

}

```

**2. [Breaking]** Changes in ExtendedAttribute type (used in Task.ExtendedAttributes, Resource.ExtendedAttributes, ResourceAssignment.ExtendedAttributes collections):

- 'DurationFormat' field was removed
- 'Value' field was removed
- 'AttributeType' field was added
- Following fields were added: 'DateValue', 'DurationValue', 'NumericValue', 'FlagValue', 'TextValue'

The following table shows which field contains the value of extended attribute depending on ExtendedAttribute's type. Thus in order to get or set the value of a custom field with 'Date', 'Start' or 'Finish' type one should use 'DateValue' field.

|**Extended Attribute type**|**ExtendedAttribute field**|
| :- | :- |
|Date, Start, Finish|DateValue|
|Duration|DurationValue|
|Flag|FlagValue|
|Number, Cost|NumericValue|
|Text|TextValue|
**Example**

```html

"Task" : 

{

    ...

    "ExtendedAttributes": [

      {

        "FieldId": "188743950",

        "AttributeType": "Date",

        "DateValue": "2018-03-04T08:15:00+07:00",

        "TextValue": null

      },

      {

        "FieldId": "188743960",

        "AttributeType": "Duration",

        "DurationValue": {

          "TimeSpan": "10:00:00",

          "TimeUnit": "Hour"

        }

      }

    ]

    ...

}

```

[**3.** GET /{name}/extendedattributes/{index}](https://apireference.aspose.cloud/tasks/#!/Tasks/GetExtendedAttributeByIndex) and [DELETE /{name}/extendedattributes/{index}](https://apireference.aspose.cloud/tasks/#!/Tasks/DeleteExtendedAttributeByIndex) endpoints: index parameter now can be FieldId as well as index of attribute in project.ExtendedAttributes collection.

**Request**

```html

curl -v https://api.aspose.cloud/v1.1/tasks/sample.mpp/extendedattributes/188743731 \
     -X GET \
     -H "Content-Type: application/json" \
     -H "Accept: application/json"

```

**Response**

```html

{

  "ExtendedAttribute": {

    "FieldId": "188743731",

    "FieldName": "Text1",

    "CfType": "Text",

    "Guid": "000039B7-8BBE-4CEB-82C4-FA8C0B400033",

    "ElementType": "Task",

    "MaxMultiValues": -1,

    "UserDef": false,

    "Alias": null,

    "SecondaryPid": "255869028",

    "AutoRollDown": false,

    "DefaultGuid": null,

    "LookupUid": "F45D601B-70C5-E311-A5BA-D43D7E937F92",

    "PhoneticsAlias": null,

    "RollupType": "Null",

    "CalculationType": "Lookup",

    "Formula": null,

    "RestrictValues": true,

    "ValuelistSortOrder": 0,

    "AppendNewValues": false,

    "Default": null,

    "ValueList": [

      {

        "Id": 1,

        "Val": "1",

        "DateTimeValue": null,

        "DurationValue": null,

        "Description": "descr",

        "Phonetic": null

      }

    ],

    "SecondaryGuid": "000039B7-8BBE-4CEB-82C4-FA8C0F404064"

  },

  "Code": 200,

  "Status": "OK"

}


```

**4.** Bugs were fixed, see [Aspose.Tasks for .NET 18.9 Release Notes](https://docs.aspose.com/display/tasksnet/Aspose.Tasks+for+.NET+18.9+Release+Notes) for more details.
