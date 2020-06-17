# melmccann\cardanosubmitapi\DefaultApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**postTransaction**](DefaultApi.md#postTransaction) | **POST** /api/submit/tx | Submit Tx



## postTransaction

> string postTransaction($content_type)

Submit Tx

Submit an already serialized transaction to the network.

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


$apiInstance = new melmccann\cardanosubmitapi\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$content_type = 'content_type_example'; // string | 

try {
    $result = $apiInstance->postTransaction($content_type);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->postTransaction: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **content_type** | **string**|  |

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../../README.md#documentation-for-models)
[[Back to README]](../../README.md)

