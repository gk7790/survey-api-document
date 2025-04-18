## Get Active Survey List
> {{base_path}}/member/suppliers/v1/list

### Description
To ensure optimal performance and up-to-date results, it is recommended to fetch the active survey list at intervals of no less than 5 minutes.

### HEADERS

> Authorization : {{ Access Token }}

### Example Request

```java
OkHttpClient client = new OkHttpClient().newBuilder().build();
Request request = new Request.Builder()
  .url("http://localhost:8080/member/suppliers/v1/list")
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
    "data": [
        {
            "surveyId": "86663",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "40",
            "cpi": 1.80,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=ftctmxIF14Pamf7Okg3g2nQfng_90XoDQKn8cD9yghXHn5evG-GkDluXW408N7WLzY2aXriWc2nLlh&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "en",
            "languageCountryCode": "en-US"
        },
        {
            "surveyId": "86901",
            "code": "4C,K2z",
            "loi": "30",
            "ir": "20",
            "cpi": 2.80,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=qQHEkI16e58V-uUdEwcTpqD6YQv9Uu8fYEen3s0ijDf-U6cPhpXxSuYq-EtzJYK5GcOg5NHLHMtQA&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "ar",
            "languageCountryCode": "ar-SA"
        },
        {
            "surveyId": "87396",
            "code": "4C,K2z",
            "loi": "20",
            "ir": "55",
            "cpi": 2.00,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=PFXHe3HZogbiynY_JIH1Hp8J2GmebWl5tfu147PnQj0QjJRrpdmHZ12x0EEswNGBThtl_aWWGX_2P&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "en",
            "languageCountryCode": "en-GB"
        },
        {
            "surveyId": "87439",
            "code": "4C,K2z",
            "loi": "9",
            "ir": "80",
            "cpi": 2.00,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=2p8IbgMXz8UIz4dpEPzOJxZr1PnTCjWIU42L6HyVjfS5DPaM6vNQQsFLPIGB2J5s505Io7dyDFKd&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "en",
            "languageCountryCode": "en-US"
        },
        {
            "surveyId": "87998",
            "code": "4C,K2z",
            "loi": "20",
            "ir": "55",
            "cpi": 1.60,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=jyX5ApYoMJ37IDJf-88VWVEKyzgX8PHqiaLGv58z2QxuZmFNEqZzqrxwSBDDdK48E4TumeGpyzJR&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "en",
            "languageCountryCode": "en-GB"
        },
        {
            "surveyId": "88135",
            "code": "4C,K2z",
            "loi": "12",
            "ir": "69",
            "cpi": 1.60,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=2KAq8W0_NcCUIv1-OcFN_457JDcb7tCmnfRHZBUpsSZPyWQubveH56tFPoSdIyJjmms_7NSboDAq&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "en",
            "languageCountryCode": "en-US"
        },
        {
            "surveyId": "88151",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 3.58,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=nuj4L9521XFVTQzxa4D1xQhTXKL4dOoacnJ4o2BMC3VU70VSerr5ELziMe8KI7R0lGKLcM8V27Lu&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "ar",
            "languageCountryCode": "ar-AE"
        },
        {
            "surveyId": "88154",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 3.58,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=CpuVdqOqN_3oVmCWtGrKeWS3FulS8wyk-ootyNFB7T-_ReTKPeC69ziKM02rpY4I3dKk2ELG-XTX&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "ar",
            "languageCountryCode": "ar-BH"
        },
        {
            "surveyId": "88155",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 3.58,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=L2zHQ_qKYR-lfw45aEWhtWGm736w_plJVck25pG0vxKdP5xX3tGNrmm2-HO1swk1JvhAVYpyBeAZ&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "ar",
            "languageCountryCode": "ar-KW"
        },
        {
            "surveyId": "88156",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 3.58,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=fMIX7XZ-2w7pm_Z7et5BPAlz8AiQhw4kUv48Svyw9yZM9fuuaf43B6J3WjlzbhMPnGXFYybTENph&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "ar",
            "languageCountryCode": "ar-OM"
        },
        {
            "surveyId": "88159",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 3.58,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=XvO0MLD2p9jbCCKnk68NV0Xtq5MJ0r9VlGDamEOW2bYKlUB5LBPksub0hFGE88G3HpAfxgCxDs19&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "ar",
            "languageCountryCode": "ar-SA"
        },
        {
            "surveyId": "88161",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 3.58,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=AA-B79RbA7SRMUZDhaHEz7617VMVQySoPcSRXPKaYD7UqLWd5qBKmH4waFloIgfgXotHR9qAPuxr&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "tr",
            "languageCountryCode": "tr-TR"
        },
        {
            "surveyId": "88162",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 3.58,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=Uq97pYQS_2F9-EHZZgXwQvs9adoxRC89jaD_C8RDMH3wsIN6gKRklegRApKQ9tNGwv1vgDHeZTX&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "ar",
            "languageCountryCode": "ar-JO"
        },
        {
            "surveyId": "88163",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 3.58,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=fQTTlQP2xempkcyZ0frSkCBb2kc-zXldhPWZJSRsrXKgd7rS2yWl2Zdm-WeBK7lxvArNYKKcMjp&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "uz",
            "languageCountryCode": "uz-UZ"
        },
        {
            "surveyId": "88164",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 3.58,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=47JQRQZTc5MLvdnIHo_0KI2KCxkcg85YJHNDkoz70jcAh6TFoA91BiNoYdSxbW8RiqnOlpS94Zp&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "kk",
            "languageCountryCode": "kk-KZ"
        },
        {
            "surveyId": "88169",
            "code": "4C,K2z",
            "loi": "25",
            "ir": "43",
            "cpi": 2.70,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=B4rRHvwP6acfrvXp3tdPAU0DEafS_lBo8cDeke37EPUzh3Ae4r1D8FVC9ZSNg7WBsFFYJIdSwMf&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "es",
            "languageCountryCode": "es-CO"
        },
        {
            "surveyId": "88191",
            "code": "4C,K2z",
            "loi": "20",
            "ir": "20",
            "cpi": 2.20,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=Hzq6NJYdYQZNtZrV_wcVldZLeFruoGdN47rT62h3QH44JTIFM7zik1mvgXLsPLozSs4IE2S6gfR&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "en",
            "languageCountryCode": "en-US"
        },
        {
            "surveyId": "88192",
            "code": "4C,K2z",
            "loi": "20",
            "ir": "20",
            "cpi": 2.20,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=c1cxlOsPjb2do8Sqw1L2jkAM1EuZc3Qdjqpe7eb5XQYAoUNy0fBZsWEWkNS4jssropnEyL0dmUbx&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "it",
            "languageCountryCode": "it-IT"
        },
        {
            "surveyId": "88212",
            "code": "4C,K2z",
            "loi": "30",
            "ir": "40",
            "cpi": 2.40,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=m-QwV7H2VQrvA2t5MNktUkPMWOovPe5EyTM-_UjeFZmxPNOD8-xBqNV0FuVJ-pIR8R7Cs2awvM4&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "en",
            "languageCountryCode": "en-US"
        },
        {
            "surveyId": "88222",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 1.80,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=X1BFg0fzB7c1_IDp-aAYuH7ljf2VIHpQpsSKDReY1J9C1-Mrj1ZoBmPwknK21cerfoTLioIgZch&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "ms",
            "languageCountryCode": "ms-MY"
        },
        {
            "surveyId": "88228",
            "code": "4C,K2z",
            "loi": "15",
            "ir": "30",
            "cpi": 1.80,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=nguMf_lXTG9pL0JrCIWEGo_qozAPQiIg-49YzSQhphl3GCkx8yRepZ6OsLJ0crP7UhF034PBIeR&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "vi",
            "languageCountryCode": "vi-VN"
        },
        {
            "surveyId": "1094165",
            "code": "EA2AwEGBB7K",
            "loi": "1",
            "ir": "11.0",
            "cpi": 3.37,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=QFKffypknyszO76Nz4Tm5iqKQNyuG96GZJ51z1o8oW_eJAMEEDpVR_vSep5GbQ9Ek_BwkmtnCr2IpJHLlqOQ5A&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "EN",
            "countryCode": "US",
            "updateTime": "2025-04-17T10:54:53.0166667"
        },
        {
            "surveyId": "1093924",
            "code": "EA2AwEGBB7K",
            "loi": "1",
            "ir": "1.0",
            "cpi": 1.44,
            "link": "https://boolsurvey.com/member/survey-open/enter?c=Vj0Lo9LUJXLQTcgRWlX3W1aHNSGbKa57QUT_kY49qK8AzXRJE1JsP_15MOw1j6WF-G46TKKAewfJWw2_x-Uow&PID={pid}&UID={uid}&ext={ext}",
            "languageCode": "EN",
            "countryCode": "US",
            "updateTime": "2025-03-21T07:10:28.3266667"
        }
    ]
}
```