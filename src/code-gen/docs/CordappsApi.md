# OpenapiJsClient.CordappsApi

All URIs are relative to *http://localhost:10200/api/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cordapps**](CordappsApi.md#cordapps) | **GET** /cordapps | 
[**cordappsBootcampOpenapiFlowsBootcampGetAllTokensFlow**](CordappsApi.md#cordappsBootcampOpenapiFlowsBootcampGetAllTokensFlow) | **POST** /cordapps/bootcamp-openapi/flows/bootcamp.GetAllTokensFlow | 
[**cordappsBootcampOpenapiFlowsBootcampTokenIssueFlowInitiator**](CordappsApi.md#cordappsBootcampOpenapiFlowsBootcampTokenIssueFlowInitiator) | **POST** /cordapps/bootcamp-openapi/flows/bootcamp.TokenIssueFlowInitiator | 
[**cordappsCordappFlows**](CordappsApi.md#cordappsCordappFlows) | **GET** /cordapps/{cordapp}/flows | 



## cordapps

> [String] cordapps()



### Example

```javascript
import OpenapiJsClient from 'openapi-js-client';

let apiInstance = new OpenapiJsClient.CordappsApi();
apiInstance.cordapps((error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
});
```

### Parameters

This endpoint does not need any parameter.

### Return type

**[String]**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## cordappsBootcampOpenapiFlowsBootcampGetAllTokensFlow

> Object cordappsBootcampOpenapiFlowsBootcampGetAllTokensFlow(body)



### Example

```javascript
import OpenapiJsClient from 'openapi-js-client';

let apiInstance = new OpenapiJsClient.CordappsApi();
let body = null; // Object | payload
apiInstance.cordappsBootcampOpenapiFlowsBootcampGetAllTokensFlow(body, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
});
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **Object**| payload | 

### Return type

**Object**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## cordappsBootcampOpenapiFlowsBootcampTokenIssueFlowInitiator

> NetCordaCoreTransactionsSignedTransaction cordappsBootcampOpenapiFlowsBootcampTokenIssueFlowInitiator(generatedBootcampTokenIssueFlowInitiatorPayload)



### Example

```javascript
import OpenapiJsClient from 'openapi-js-client';

let apiInstance = new OpenapiJsClient.CordappsApi();
let generatedBootcampTokenIssueFlowInitiatorPayload = new OpenapiJsClient.GeneratedBootcampTokenIssueFlowInitiatorPayload(); // GeneratedBootcampTokenIssueFlowInitiatorPayload | payload
apiInstance.cordappsBootcampOpenapiFlowsBootcampTokenIssueFlowInitiator(generatedBootcampTokenIssueFlowInitiatorPayload, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
});
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generatedBootcampTokenIssueFlowInitiatorPayload** | [**GeneratedBootcampTokenIssueFlowInitiatorPayload**](GeneratedBootcampTokenIssueFlowInitiatorPayload.md)| payload | 

### Return type

[**NetCordaCoreTransactionsSignedTransaction**](NetCordaCoreTransactionsSignedTransaction.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## cordappsCordappFlows

> [String] cordappsCordappFlows(cordapp)



### Example

```javascript
import OpenapiJsClient from 'openapi-js-client';

let apiInstance = new OpenapiJsClient.CordappsApi();
let cordapp = "cordapp_example"; // String | 
apiInstance.cordappsCordappFlows(cordapp, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
});
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cordapp** | **String**|  | 

### Return type

**[String]**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

