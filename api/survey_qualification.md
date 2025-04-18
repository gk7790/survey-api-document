## Get Active Survey List
> {{base_path}}/member/suppliers/v1/getQualification

### Description
To ensure optimal performance and up-to-date results, it is recommended to fetch the active survey list at intervals of no less than 5 minutes.

### HEADERS

> Authorization : {{ Access Token }}

### Query Params

| Key | Value | Description |
| --- | --- | --- |
| code | 4C,K2z | Survey List code 4C,K2z |
| surveyId | 86663 | |

### Example Request

```java
OkHttpClient client = new OkHttpClient().newBuilder().build();
Request request = new Request.Builder()
  .url("{{base_path}}/member/suppliers/v1/getQualification")
  .method("GET", body)
  .addHeader("authorization",  "su-U2FsdGVkX18erqKNqzA1IGSf3oXfEuA7yhAkJDhAzhdgsBIwj8Zv4aHQ9ZoTBXMg")
  .build();
Response response = client.newCall(request).execute();
```

### Example Response

#### Body
```json
{
    "code": 0,
    "msg": "success",
    "data": {
        "targeting": {
            "gender": [
                {
                    "profileAnswerKey": "gender_001",
                    "OptionText": "Male",
                    "optionID": 1
                },
                {
                    "profileAnswerKey": "gender_002",
                    "OptionText": "Female",
                    "optionID": 1
                }
            ],
            "age": [
                {
                    "min": "13",
                    "max": "24",
                    "optionID": 1
                },
                {
                    "min": "25",
                    "max": "34",
                    "optionID": 1
                },
                {
                    "min": "35",
                    "max": "45",
                    "optionID": 1
                },
                {
                    "min": "45",
                    "max": "54",
                    "optionID": 1
                },
                {
                    "min": "55",
                    "max": "64",
                    "optionID": 1
                },
                {
                    "min": "65",
                    "max": "99",
                    "optionID": 1
                }
            ]
        },
        "apiMessages": "GetSurveyQualification successful.",
        "version": 1,
        "apiStatus": 1
    }
}
```