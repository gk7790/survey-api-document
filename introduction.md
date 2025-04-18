# Surveys API

&emsp;&emsp;The Supply APIs provide a simple way to connect to millions of people and get answers in real time. By specifying a set of demographic qualifications and quotas, buyers can target a wide or very specific population on a topic of your choosing. As a supplier, you get fine grain control over your survey matching and business relationships on the platform.
> We want to encourage innovation with minimal limits. We ask that you please be practical and considerate then determining call frequencies. We rate limit when needed to protect the system and ensure the highest
level of service to all of our clients.

## Environments

To make our APIs as explorable as possible, we have environments specific to your development needs. For access to these environments contact your Integration Consultant at gyh7790@gmail.com.

> Users are financially responsible for all transactions made on the system regardless of whether it was the result of a bug in your integration.


## Endpoints

***Staging Endpoint:*** https://xxx.xxxx.com/

***Production Endpoint:*** https://api.zz.com/

## Authentication

The Gk Survey APIs use a HTTP Authorization header for authentication.
Every call should have a header

> Authorization: {{ Access Token }}

Ensure that the key you are passing is the correct key for the environment.


## Request Format

Built on RESTful principles, the API uses HTTP methods and verbs. Requests should be made using JSON, and JSON is returned by all responses.

## HTTP Status Codes

We use use conventional HTTP response codes to indicate the success or failure of an API request. In general, codes in the 2xx range indicate success, codes in the 4xx range indicate an error caused by the information provided (i.e., a required parameter was omitted, a method was not found, etc.), and codes in the 5xx range indicate an error with our API servers (these are rare).

| Status Code | Status Text | Description |
| ----------- | ----------- | ----------- |
|  0  |  OK   | The request has succeeded. The meaning of a success varies depending on the HTTP method: |
|  400   |   fail  |     |