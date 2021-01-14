# CustomerTokenCreationRequest

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**billing_address** | [**\Swagger\Client\Model\Address**](Address.md) | Once the customer has provided any data, updates to this object will be ignored (without generating an error). | [optional] 
**customer** | [**\Swagger\Client\Model\Customer**](Customer.md) | Information about the liable customer of the order. | [optional] 
**description** | **string** | Description of the purpose of the token. | 
**intended_use** | **string** | Intended use for the token. | 
**locale** | **string** | RFC 1766 customer&#39;s locale. | 
**purchase_country** | **string** | ISO 3166 alpha-2 purchase country. | 
**purchase_currency** | **string** | ISO 4217 purchase currency. | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


