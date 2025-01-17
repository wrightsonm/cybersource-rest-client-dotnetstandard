# CyberSource.Model.TssV2TransactionsPost201ResponseEmbeddedTransactionSummaries
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | An unique identification number generated by Cybersource to identify the submitted request. Returned by all services. It is also appended to the endpoint of the resource. On incremental authorizations, this value with be the same as the identification number returned in the original authorization response.  | [optional] 
**SubmitTimeUtc** | **string** | Time of request in UTC. Format: &#x60;YYYY-MM-DDThh:mm:ssZ&#x60; **Example** &#x60;2016-08-11T22:47:57Z&#x60; equals August 11, 2016, at 22:47:57 (10:47:57 p.m.). The &#x60;T&#x60; separates the date and the time. The &#x60;Z&#x60; indicates UTC.  Returned by Cybersource for all services.  | [optional] 
**MerchantId** | **string** | Your CyberSource merchant ID. | [optional] 
**ApplicationInformation** | [**TssV2TransactionsPost201ResponseEmbeddedApplicationInformation**](TssV2TransactionsPost201ResponseEmbeddedApplicationInformation.md) |  | [optional] 
**BuyerInformation** | [**TssV2TransactionsPost201ResponseEmbeddedBuyerInformation**](TssV2TransactionsPost201ResponseEmbeddedBuyerInformation.md) |  | [optional] 
**ClientReferenceInformation** | [**TssV2TransactionsPost201ResponseEmbeddedClientReferenceInformation**](TssV2TransactionsPost201ResponseEmbeddedClientReferenceInformation.md) |  | [optional] 
**ConsumerAuthenticationInformation** | [**TssV2TransactionsPost201ResponseEmbeddedConsumerAuthenticationInformation**](TssV2TransactionsPost201ResponseEmbeddedConsumerAuthenticationInformation.md) |  | [optional] 
**DeviceInformation** | [**TssV2TransactionsPost201ResponseEmbeddedDeviceInformation**](TssV2TransactionsPost201ResponseEmbeddedDeviceInformation.md) |  | [optional] 
**FraudMarkingInformation** | [**TssV2TransactionsGet200ResponseFraudMarkingInformation**](TssV2TransactionsGet200ResponseFraudMarkingInformation.md) |  | [optional] 
**MerchantDefinedInformation** | [**List&lt;Ptsv2paymentsMerchantDefinedInformation&gt;**](Ptsv2paymentsMerchantDefinedInformation.md) | The object containing the custom data that the merchant defines.  | [optional] 
**MerchantInformation** | [**TssV2TransactionsPost201ResponseEmbeddedMerchantInformation**](TssV2TransactionsPost201ResponseEmbeddedMerchantInformation.md) |  | [optional] 
**OrderInformation** | [**TssV2TransactionsPost201ResponseEmbeddedOrderInformation**](TssV2TransactionsPost201ResponseEmbeddedOrderInformation.md) |  | [optional] 
**PaymentInformation** | [**TssV2TransactionsPost201ResponseEmbeddedPaymentInformation**](TssV2TransactionsPost201ResponseEmbeddedPaymentInformation.md) |  | [optional] 
**ProcessingInformation** | [**TssV2TransactionsPost201ResponseEmbeddedProcessingInformation**](TssV2TransactionsPost201ResponseEmbeddedProcessingInformation.md) |  | [optional] 
**ProcessorInformation** | [**TssV2TransactionsPost201ResponseEmbeddedProcessorInformation**](TssV2TransactionsPost201ResponseEmbeddedProcessorInformation.md) |  | [optional] 
**PointOfSaleInformation** | [**TssV2TransactionsPost201ResponseEmbeddedPointOfSaleInformation**](TssV2TransactionsPost201ResponseEmbeddedPointOfSaleInformation.md) |  | [optional] 
**RiskInformation** | [**TssV2TransactionsPost201ResponseEmbeddedRiskInformation**](TssV2TransactionsPost201ResponseEmbeddedRiskInformation.md) |  | [optional] 
**Links** | [**TssV2TransactionsPost201ResponseEmbeddedLinks**](TssV2TransactionsPost201ResponseEmbeddedLinks.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

