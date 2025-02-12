# Amazon Fulfillment
## APIs
|Operation|Method|API Path (URL)|Region|
|-|-|-|-|
|cancelFeed|DELETE|/feeds/2020-09-04/feeds/{feedId}|NA, EU, FE|
|cancelFeed|DELETE|/feeds/2021-06-30/feeds/{feedId}|NA, EU, FE|
|cancelFulfillmentOrder|PUT|/fba/outbound/2020-07-01/fulfillmentOrders/{sellerFulfillmentOrderId}/cancel|NA, EU, FE|
|cancelFulfillmentOrder|PUT|/fba/outbound/v0/fulfillmentOrders/{sellerFulfillmentOrderId}/cancel|NA, FE, EU|
|cancelReport|DELETE|/reports/2020-09-04/reports/{reportId}|NA, EU, FE|
|cancelReport|DELETE|/reports/2021-06-30/reports/{reportId}|NA, EU, FE|
|cancelReportSchedule|DELETE|/reports/2020-09-04/schedules/{reportScheduleId}|NA, EU, FE|
|cancelReportSchedule|DELETE|/reports/2021-06-30/schedules/{reportScheduleId}|NA, EU, FE|
|cancelSubscription|PUT|/buyerSubscriptions/v1/subscriptions/{subscriptionId}/cancel|NA, EU, FE|
|confirmPreorder|PUT|/fba/inbound/v0/shipments/{shipmentId}/preorder/confirm|NA, EU, FE|
|confirmTransport|POST|/fba/inbound/v0/shipments/{shipmentId}/transport/confirm|NA, EU, FE|
|CreateAmazonMotors|POST|/messaging/v1/orders/{amazonOrderId}/messages/amazonMotors|NA, EU, FE|
|createDestination|POST|/notifications/v1/destinations|NA, EU, FE|
|createFeedDocument|POST|/feeds/2020-09-04/documents|NA, EU, FE|
|createFeedDocument|POST|/feeds/2021-06-30/documents|NA, EU, FE|
|createFeed|POST|/feeds/2020-09-04/feeds|NA, EU, FE|
|createFeed|POST|/feeds/2021-06-30/feeds|NA, EU, FE|
|createFulfillmentOrder|POST|/fba/outbound/2020-07-01/fulfillmentOrders|NA, EU, FE|
|createFulfillmentOrder|POST|/fba/outbound/v0/fulfillmentOrders|NA, EU, FE|
|createFulfillmentReturn|PUT|/fba/outbound/2020-07-01/fulfillmentOrders/{sellerFulfillmentOrderId}/return|NA, EU, FE|
|createFulfillmentReturn|PUT|/fba/outbound/v0/fulfillmentOrders/{sellerFulfillmentOrderId}/return|NA, EU, FE|
|createInboundShipmentPlan|POST|/fba/inbound/v0/plans|NA, EU, FE|
|createInboundShipment|POST|/fba/inbound/v0/shipments/{shipmentId}|NA, EU, FE|
|createPackages|POST|/externalFulfillment/shipments/2021-01-06/shipments/{shipmentId}/packages|NA, EU, FE|
|createReport|POST|/reports/2020-09-04/reports|NA, EU, FE|
|createReport|POST|/reports/2021-06-30/reports|NA, EU, FE|
|createReportSchedule|POST|/reports/2020-09-04/schedules|NA, EU, FE|
|createReportSchedule|POST|/reports/2021-06-30/schedules|NA, EU, FE|
|createUploadDestination|POST|/uploads/v1/uploadDestinations|NA, EU, FE|
|deleteSmallAndLightEnrollmentBySellerSKU|DELETE|/fba/smallAndLight/v1/enrollments/{sellerSKU}|NA, EU, FE|
|estimateTransport|POST|/fba/inbound/v0/shipments/{shipmentId}/transport/estimate|NA, EU, FE|
|generateInvoice|POST|/externalFulfillment/shipments/2021-01-06/shipments/{shipmentId}/packages/{packageId}/invoice|NA, EU, FE|
|generateShipLabel|POST|/externalFulfillment/shipments/2021-01-06/shipments/{shipmentId}/packages/{packageId}/shipLabel|NA, EU, FE|
|getBillOfLading|GET|/fba/inbound/v0/shipments/{shipmentId}/billOfLading|NA, EU, FE|
|getDestination|GET|/notifications/v1/destinations/{destinationId}|NA, EU, FE|
|getDestinations|GET|/notifications/v1/destinations|NA, EU, FE|
|getFeatureInventory|GET|/fba/outbound/2020-07-01/features/inventory/{featureName}|NA, EU, FE|
|getFeatures|GET|/fba/outbound/2020-07-01/features|NA, EU, FE|
|getFeatureSKU|GET|/fba/outbound/2020-07-01/features/inventory/{featureName}/{sellerSku}|NA, EU, FE|
|getFeedDocument|GET|/feeds/2020-09-04/documents/{feedDocumentId}|NA, EU, FE|
|getFeedDocument|GET|/feeds/2021-06-30/documents/{feedDocumentId}|NA, EU, FE|
|getFeed|GET|/feeds/2020-09-04/feeds/{feedId}|NA, EU, FE|
|getFeed|GET|/feeds/2021-06-30/feeds/{feedId}|NA, EU, FE|
|getFeeds|GET|/feeds/2020-09-04/feeds|NA, EU, FE|
|getFeeds|GET|/feeds/2021-06-30/feeds|NA, EU, FE|
|getFulfillmentOrder|GET|/fba/outbound/2020-07-01/fulfillmentOrders/{sellerFulfillmentOrderId}|NA, EU, FE|
|getFulfillmentOrder|GET|/fba/outbound/v0/fulfillmentOrders/{sellerFulfillmentOrderId}|NA, EU, FE|
|getFulfillmentPreview|POST|/fba/outbound/2020-07-01/fulfillmentOrders/preview|NA, EU, FE|
|getFulfillmentPreview|POST|/fba/outbound/v0/fulfillmentOrders/preview|NA, EU, FE|
|getInboundGuidance|GET|/fba/inbound/v0/itemsGuidance|NA, EU, FE|
|getInventorySummaries|GET|/fba/inventory/v1/summaries|NA|
|getItemEligibilityPreview|GET|/fba/inbound/v1/eligibility/itemPreview|NA, EU, FE|
|getLabels|GET|/fba/inbound/v0/shipments/{shipmentId}/labels|NA, EU, FE|
|getMarketplaceParticipations|GET|/sellers/v1/marketplaceParticipations|FE|
|getMyFeesEstimateForASIN|POST|/products/fees/v0/items/{Asin}/feesEstimate|NA, EU, FE|
|getMyFeesEstimateForSKU|POST|/products/fees/v0/listings/{SellerSKU}/feesEstimate|NA, EU, FE|
|getOrderAddress|GET|/orders/v0/orders/{orderId}/address|NA, EU, FE|
|getOrderBuyerInfo|GET|/orders/v0/orders/{orderId}/buyerInfo|NA, EU, FE|
|getOrder|GET|/orders/v0/orders/{orderId}|NA, EU, FE|
|getOrderItemsBuyerInfo|GET|/orders/v0/orders/{orderId}/orderItems/buyerInfo|NA, EU, FE|
|getOrderItems|GET|/orders/v0/orders/{orderId}/orderItems|NA, EU, FE|
|getOrderMetrics|GET|/sales/v1/orderMetrics|FE|
|getOrders|GET|/orders/v0/orders|NA, EU, FE|
|getPackageTrackingDetails|GET|/fba/outbound/2020-07-01/tracking|NA, EU, FE|
|getPackageTrackingDetails|GET|/fba/outbound/v0/tracking|NA, EU, FE|
|getPackingSlip|GET|/vendor/directFulfillment/shipping/v1/packingSlips/{purchaseOrderNumber}|NA, EU, FE|
|getPackingSlips|GET|/vendor/directFulfillment/shipping/v1/packingSlips|NA, EU, FE|
|getPreorderInfo|GET|/fba/inbound/v0/shipments/{shipmentId}/preorder|NA, EU, FE|
|getPrepInstructions|GET|/fba/inbound/v0/prepInstructions|NA, EU, FE|
|getPurchaseOrder|GET|/vendor/orders/v1/purchaseOrders/{purchaseOrderNumber}|NA, EU, FE|
|getPurchaseOrders|GET|/vendor/orders/v1/purchaseOrders|NA, EU, FE|
|getPurchaseOrdersStatus|GET|/vendor/orders/v1/purchaseOrdersStatus|NA, EU, FE|
|getReportDocument|GET|/reports/2020-09-04/documents/{reportDocumentId}|NA, EU, FE|
|getReportDocument|GET|/reports/2021-06-30/documents/{reportDocumentId}|NA, EU, FE|
|getReport|GET|/reports/2020-09-04/reports/{reportId}|NA, EU, FE|
|getReport|GET|/reports/2021-06-30/reports/{reportId}|NA, EU, FE|
|getReportSchedule|GET|/reports/2020-09-04/schedules/{reportScheduleId}|NA, EU, FE|
|getReportSchedule|GET|/reports/2021-06-30/schedules/{reportScheduleId}|NA, EU, FE|
|getReportSchedules|GET|/reports/2020-09-04/schedules|NA, EU, FE|
|getReportSchedules|GET|/reports/2021-06-30/schedules|NA, EU, FE|
|getReports|GET|/reports/2020-09-04/reports|NA, EU, FE|
|getReports|GET|/reports/2021-06-30/reports|NA, EU, FE|
|getShipment|GET|/externalFulfillment/shipments/2021-01-06/shipments/{shipmentId}|NA, EU, FE|
|getShipmentItemsByShipmentId|GET|/fba/inbound/v0/shipments/{shipmentId}/items|NA, EU, FE|
|getShipmentItems|GET|/fba/inbound/v0/shipmentItems|NA, EU, FE|
|getShipments|GET|/externalFulfillment/shipments/2021-01-06/shipments|NA, EU, FE|
|getShipments|GET|/fba/inbound/v0/shipments|NA, EU, FE|
|getSmallAndLightEligibilityBySellerSKU|GET|/fba/smallAndLight/v1/eligibilities/{sellerSKU}|NA, EU, FE|
|getSmallAndLightEnrollmentBySellerSKU|GET|/fba/smallAndLight/v1/enrollments/{sellerSKU}|NA, EU, FE|
|getSmallAndLightFeePreview|POST|/fba/smallAndLight/v1/feePreviews|NA, EU, FE|
|getTransaction|GET|/vendor/transactions/v1/transactions/{transactionId}|NA, EU, FE|
|getTransportDetails|GET|/fba/inbound/v0/shipments/{shipmentId}/transport|NA, EU, FE|
|listAllFulfillmentOrders|GET|/fba/outbound/2020-07-01/fulfillmentOrders|NA, EU, FE|
|listAllFulfillmentOrders|GET|/fba/outbound/v0/fulfillmentOrders|NA, EU, FE|
|listFinancialEvents|GET|/finances/v0/financialEvents|NA, FE|
|listReturnReasonCodes|GET|/fba/outbound/2020-07-01/returnReasonCodes|NA, EU, FE|
|listReturnReasonCodes|GET|/fba/outbound/v0/returnReasonCodes|NA, EU, FE|
|processShipment|POST|/externalFulfillment/shipments/2021-01-06/shipments/{shipmentId}|NA, EU, FE|
|putSmallAndLightEnrollmentBySellerSKU|PUT|/fba/smallAndLight/v1/enrollments/{sellerSKU}|NA, EU, FE|
|putTransportDetails|PUT|/fba/inbound/v0/shipments/{shipmentId}/transport|NA, EU, FE|
|retrieveInvoice|GET|/externalFulfillment/shipments/2021-01-06/shipments/{shipmentId}/packages/{packageId}/invoice|NA, EU, FE|
|retrieveShipLabel|GET|/externalFulfillment/shipments/2021-01-06/shipments/{shipmentId}/packages/{packageId}/shipLabel|NA, EU, FE|
|retrieveShippingOptions|GET|/externalFulfillment/shipments/2021-01-06/shippingOptions|NA, EU, FE|
|submitAcknowledgement|POST|/vendor/orders/v1/acknowledgements|NA, FE, EU|
|submitInvoices|POST|/vendor/payments/v1/invoices|NA, EU, FE|
|SubmitShipmentConfirmations|POST|/vendor/shipping/v1/shipmentConfirmations|NA, EU, FE|
|updateFulfillmentOrder|PUT|/fba/outbound/2020-07-01/fulfillmentOrders/{sellerFulfillmentOrderId}|NA, EU, FE|
|updateFulfillmentOrder|PUT|/fba/outbound/v0/fulfillmentOrders/{sellerFulfillmentOrderId}|NA, FE, EU|
|updateInboundShipment|PUT|/fba/inbound/v0/shipments/{shipmentId}|NA, EU, FE|
|updatePackage|PUT|/externalFulfillment/shipments/2021-01-06/shipments/{shipmentId}/packages/{packageId}|NA, EU, FE|
|updatePackageStatus|PATCH|/externalFulfillment/shipments/2021-01-06/shipments/{shipmentId}/packages/{packageId}|NA, EU, FE|
|voidTransport|POST|/fba/inbound/v0/shipments/{shipmentId}/transport/void|NA, EU, FE|
## Feeds, Reports and Notifications
|API Section|Type|Region|
|-|-|-|
|Feeds|POST\_FBA\_INBOUND\_CARTON\_CONTENTS|NA, EU, FE|
|Feeds|POST\_FLAT\_FILE\_FBA\_CREATE\_INBOUND\_PLAN|NA, EU, FE|
|Feeds|POST\_FLAT\_FILE\_FBA\_CREATE\_REMOVAL|NA, EU, FE|
|Feeds|POST\_FLAT\_FILE\_FBA\_UPDATE\_INBOUND\_PLAN|NA, EU, FE|
|Feeds|POST\_FLAT\_FILE\_FROM\_EXCEL\_FBA\_CREATE\_CARTON\_INFO|NA, EU, FE|
|Feeds|POST\_FLAT\_FILE\_FULFILLMENT\_ORDER\_CANCELLATION\_REQUEST\_DATA|NA, EU, FE|
|Feeds|POST\_FLAT\_FILE\_FULFILLMENT\_ORDER\_REQUEST\_DATA|NA, EU, FE|
|Feeds|POST\_FULFILLMENT\_ORDER\_CANCELLATION\_REQUEST\_DATA|NA, EU, FE|
|Notifications|FBA_OUTBOUND_SHIPMENT_STATUS|NA, EU*, FE|
|Notifications|FEED_PROCESSING_FINISHED|NA, EU*, FE|
|Notifications|FULFILLMENT_ORDER_STATUS|NA, EU*, FE|
|Notifications|MFN_ORDER_STATUS_CHANGE|NA|
|Notifications|ORDER_STATUS_CHANGE|NA, EU, FE|
|Notifications|REPORT_PROCESSING_FINISHED|NA, EU*, FE|
|Reports|GET\_AFN\_INVENTORY\_DATA\_BY\_COUNTRY|NA, EU, FE|
|Reports|GET\_AFN\_INVENTORY\_DATA|NA, EU, FE|
|Reports|GET\_AMAZON\_FULFILLED\_SHIPMENTS\_DATA\_GENERAL|NA, EU, FE|
|Reports|GET\_EXCESS\_INVENTORY\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_ESTIMATED\_FBA\_FEES\_TXT\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_CURRENT\_INVENTORY\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_CUSTOMER\_RETURNS\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_CUSTOMER\_SHIPMENT\_PROMOTION\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_CUSTOMER\_SHIPMENT\_REPLACEMENT\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_CUSTOMER\_SHIPMENT\_SALES\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_CUSTOMER\_TAXES\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_INBOUND\_NONCOMPLIANCE\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_INVENTORY\_ADJUSTMENTS\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_INVENTORY\_EXPIRATION\_DATE\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_INVENTORY\_HEALTH\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_INVENTORY\_RECEIPTS\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_INVENTORY\_SUMMARY\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_LONGTERM\_STORAGE\_FEE\_CHARGES\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_MONTHLY\_INVENTORY\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_REMOVAL\_ORDER\_DETAIL\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_FULFILLMENT\_REMOVAL\_SHIPMENT\_DETAIL\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_INVENTORY\_AGED\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_MYI\_ALL\_INVENTORY\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_MYI\_UNSUPPRESSED\_INVENTORY\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_OVERAGE\_FEE\_CHARGES\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_RECOMMENDED\_REMOVAL\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_RECONCILIATION\_REPORT\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_REIMBURSEMENTS\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_SNS\_FORECAST\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_SNS\_PERFORMANCE\_DATA|NA, EU|
|Reports|GET\_FBA\_STORAGE\_FEE\_CHARGES\_DATA|NA, EU, FE|
|Reports|GET\_FBA\_UNO\_INVENTORY\_DATA|NA, EU, FE|
|Reports|GET\_FLAT\_FILE\_ALL\_ORDERS\_DATA\_BY\_LAST\_UPDATE\_GENERAL|NA, EU, FE|
|Reports|GET\_FLAT\_FILE\_ALL\_ORDERS\_DATA\_BY\_ORDER\_DATE\_GENERAL|NA, EU, FE|
|Reports|GET\_FLAT\_FILE\_ARCHIVED\_ORDERS\_DATA\_BY\_ORDER\_DATE|NA, EU, FE|
|Reports|GET\_LEDGER\_DETAIL\_VIEW\_DATA|NA, EU, FE|
|Reports|GET\_LEDGER\_SUMMARY\_VIEW\_DATA|NA, EU, FE|
|Reports|GET\_PAN\_EU\_OFFER\_STATUS|NA, EU, FE|
|Reports|GET\_PRODUCT\_EXCHANGE\_DATA|NA, EU, FE|
|Reports|GET\_RESERVED\_INVENTORY\_DATA|NA, EU, FE|
|Reports|GET\_RESTOCK\_INVENTORY\_RECOMMENDATIONS\_REPORT|NA, EU, FE|
|Reports|GET\_SELLER\_FEEDBACK\_DATA|NA, EU, FE|
|Reports|GET\_STRANDED\_INVENTORY\_LOADER\_DATA|NA, EU, FE|
|Reports|GET\_STRANDED\_INVENTORY\_UI\_DATA|NA, EU, FE|
|Reports|GET\_V2\_SETTLEMENT\_REPORT\_DATA\_FLAT\_FILE|NA, EU, FE|
|Reports|GET\_XML\_ALL\_ORDERS\_DATA\_BY\_LAST\_UPDATE\_GENERAL|NA, EU, FE|
|Reports|GET\_XML\_ALL\_ORDERS\_DATA\_BY\_ORDER\_DATE\_GENERAL|NA, EU, FE|
|Reports|SUPPLY\_CHAIN\_HUB\_INSIGHTS\_DATA|NA, EU, FE|
|Reports|SUPPLY\_CHAIN\_HUB\_INSIGHTS|NA, EU, FE|
|Reports|SUPPLY\_CHAIN\_HUB\_RAW\_DATA|NA, EU, FE|
<br/>
* Functionality may not be entirely available in this region.
