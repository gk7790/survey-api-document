## Get Active Survey List
> {{base_path}}/member/suppliers/v1/getQuota

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
OkHttpClient client = new OkHttpClient().newBuilder()
  .build();
MediaType mediaType = MediaType.parse("text/plain");
RequestBody body = RequestBody.create(mediaType, "");
Request request = new Request.Builder()
  .url("{{base_path}}/member/suppliers/v1/getQuota?code=4C,K2z&surveyId=86663")
  .method("GET", body)
  .addHeader("authorization", "su-U2FsdGVkX18erqKNqzA1IGSf3oXfEuA7yhAkJDhAzhdgsBIwj8Zv4aHQ9ZoTBXMg")
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
        "surveyInfo": [
            {
                "surveyStatus": 2,
                "surveyID": "86663",
                "surveyCPI": "2.00",
                "Quota": {
                    "58824": {
                        "conditions": [
                            {
                                "profileAnswerKey": "gender_002",
                                "OptionText": "Female",
                                "profileQuestionKey": "gender"
                            }
                        ],
                        "remainingQuota": [
                            "100"
                        ]
                    },
                    "58823": {
                        "conditions": [
                            {
                                "profileAnswerKey": "gender_001",
                                "OptionText": "Male",
                                "profileQuestionKey": "gender"
                            }
                        ],
                        "remainingQuota": [
                            "100"
                        ]
                    }
                },
                "projectBrief": "among 13 to 45\r\n\r\n·         25% 13 to 19\r\n\r\n·         25% 20 to 29\r\n\r\n·         25% 30-37\r\n\r\n·         25% 38-45\r\n\r\n·         Survey starts nat rep for region and ethnicity, but completes will fall ou",
                "surveyTargetCount": 100,
                "allocatedQuota": 100
            }
        ],
        "apiMessages": "Surveys Quota and Status is fetched.",
        "version": 1,
        "apiStatus": 1
    }
}
```