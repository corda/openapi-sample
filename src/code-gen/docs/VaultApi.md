# OpenapiJsClient.VaultApi

All URIs are relative to *http://localhost:10200/api/rest*

Method | HTTP request | Description
------------- | ------------- | -------------
[**vaultVaultQuery**](VaultApi.md#vaultVaultQuery) | **GET** /vault/vaultQuery | 
[**vaultVaultQueryBy**](VaultApi.md#vaultVaultQueryBy) | **POST** /vault/vaultQueryBy | 



## vaultVaultQuery

> NetCordaCoreNodeServicesVaultPageNetCordaCoreContractsContractState vaultVaultQuery(opts)



### Example

```javascript
import OpenapiJsClient from 'openapi-js-client';

let apiInstance = new OpenapiJsClient.VaultApi();
let opts = {
  'contractStateType': java.lang.Object // String | 
};
apiInstance.vaultVaultQuery(opts, (error, data, response) => {
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
 **contractStateType** | **String**|  | [optional] 

### Return type

[**NetCordaCoreNodeServicesVaultPageNetCordaCoreContractsContractState**](NetCordaCoreNodeServicesVaultPageNetCordaCoreContractsContractState.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## vaultVaultQueryBy

> NetCordaCoreNodeServicesVaultPageNetCordaCoreContractsContractState vaultVaultQueryBy(ioBluebankBraidCordaServicesVaultVaultQuery)



### Example

```javascript
import OpenapiJsClient from 'openapi-js-client';

let apiInstance = new OpenapiJsClient.VaultApi();
let ioBluebankBraidCordaServicesVaultVaultQuery = new OpenapiJsClient.IoBluebankBraidCordaServicesVaultVaultQuery(); // IoBluebankBraidCordaServicesVaultVaultQuery | vault
apiInstance.vaultVaultQueryBy(ioBluebankBraidCordaServicesVaultVaultQuery, (error, data, response) => {
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
 **ioBluebankBraidCordaServicesVaultVaultQuery** | [**IoBluebankBraidCordaServicesVaultVaultQuery**](IoBluebankBraidCordaServicesVaultVaultQuery.md)| vault | 

### Return type

[**NetCordaCoreNodeServicesVaultPageNetCordaCoreContractsContractState**](NetCordaCoreNodeServicesVaultPageNetCordaCoreContractsContractState.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

