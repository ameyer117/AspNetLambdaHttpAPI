# Why?
Working example of using `APIGatewayHttpApiV2ProxyFunction`
## Tool Required:
https://github.com/aws/aws-lambda-dotnet/tree/master/Tools/LambdaTestTool
## Example Payload:
This should have a body that has `"Hello Robby!"` in it.

```json
{
  "version": "2.0",
  "routeKey": "$default",
  "rawPath": "/",
  "rawQueryString": "",
  "cookies": [  ],
  "headers": {
    "accept": "*/*",
    "accept-encoding": "gzip, deflate",
    "content-type": "application/json"
  },
  "queryStringParameters": {},
  "requestContext": {
    "accountId": "123456789012",
    "apiId": "api-id",
    "authentication": {
    },
    "authorizer": {
    },
    "domainName": "id.execute-api.us-east-1.amazonaws.com",
    "domainPrefix": "domain-id",
    "http": {
      "method": "GET",
      "path": "/",
      "protocol": "HTTP/1.1",
      "sourceIp": "IP",
      "userAgent": "agent"
    },
    "requestId": "request-id",
    "routeId": "route-id",
    "routeKey": "$default-route",
    "stage": "$default-stage",
    "time": "12/Mar/2020:19:03:58 +0000",
    "timeEpoch": 1583348638390
  },
  "isBase64Encoded": false
}
```
