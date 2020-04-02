# Microsoft.Logic

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## integrationAccounts/agreements

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.content.aS2.sendAgreement.protocolSettings.mdnSettings.receiptDeliveryUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

## integrationAccounts/maps

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.content

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.contentType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

## integrationAccounts/partners

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.content.b2b.partnerClassification

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

## integrationAccounts/schemas

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.content

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.contentType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.documentName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.targetNamespace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

## integrationAccounts

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

## workflows

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.accessControl.actions.allowedCallerIpAddresses[*].addressRange

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.accessControl.triggers.allowedCallerIpAddresses[*].addressRange

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.AddRightsResult.actions.Success_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.AddRightsResult.else.actions.AddRightsFailureResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Any_records_to_process.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Any_records_to_process.else.actions.Success_response_if_no_data.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.BasicData_Request.actions.Condition.actions.Compose_Not_Found_Response.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.BasicData_Request.actions.Condition.actions.Response_NotFound_BasicData.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.BasicData_Request.actions.Condition.else.actions.Compose_Error_Response.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.BasicData_Request.actions.Condition.else.actions.Response_ERROR_BasicData.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Business_Logic.actions.Compose_Kusto_Query_Parameters.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Business_Logic.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Business_Scope.actions.Condition.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Business_Scope.actions.PositiveResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Business_logic.actions.Transform_message_to_external_format.inputs.headers.StorageConnectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Business_logic.actions.Transform_to_intermediate_xml_format.inputs.headers.StorageConnectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Call_CIS.actions.Authorised_for_NVR.else.actions.Compose_not_authorised.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Call_CIS.actions.Authorised_for_NVR.else.actions.Organization_not_authorized_for_NVR.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Call_CIS.actions.CIS_Response.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Call_CIS.actions.Response_CIS_ERROR.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_IsSuccessAPICall_Condition_On_MapAndCall_Failed.else.actions.Return_Failed_Response_For_IsSuccessAPICall_On_MapAndCall_Fail.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_IsSuccessAPICall_Condition_On_MapAndCall_Success.actions.Return_Success_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_IsSuccessAPICall_Condition_On_MapAndCall_Success.else.actions.Return_Failed_Response_For_IsSuccessAPICall_On_MapAndCall_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_Scope_Status.actions.Response_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_Scope_Status.else.actions.Response_ErrorOccurred.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_ESRP_Scan_Passed.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_ESRP_Scan_Passed.else.actions.Call_Esrp_Wrapper_to_Check_Current_Esrp_Status.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_ESRP_Scan_Passed.else.actions.Check_if_ESRP_Release_Passed_or_InProgress.actions.Send_Success_Response_back.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_ESRP_Scan_Passed.else.actions.Persist_Scan_Status_in_the_database_through_Document_Manager.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_list_contains_files.actions.For_each_file_in_list.actions.Lookup_And_Replace_Values_(Async).inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_there's_a_LpeCorrelationId.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_we_need_to_create_a_new_CRM_Account.else.actions.Check_if_we_need_to_read_Owner_from_Account.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_logWorkflow_value.actions.Compose_log_data.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_the_Status_of_Payment_Envelope_Record.cases.If_Status_of_Payment_Envelope_is_Open.actions.Scope_for_creating_and_sending_Payment_Message.actions.Compose_Body_for_Supplier_Bank_Address.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_the_Status_of_Payment_Envelope_Record.cases.If_Status_of_Payment_Envelope_is_Open.actions.Scope_for_creating_and_sending_Payment_Message.actions.Compose_Body_for_Supplier_Counterparty_Address.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_the_Status_of_Payment_Envelope_Record.cases.If_Status_of_Payment_Envelope_is_Open.actions.Scope_for_creating_and_sending_Payment_Message.actions.Compose_Payment_Message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Compose.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Compose_-_Response_Blob_Reference.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Compose_Email_Notification_Message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Compose_ErklaerungFernsteuerbarkeitBlob.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Compose_PrintJob.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Compose_utc_dates.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Compose-ClientAuthenticationRequest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Compose-SendAccessKeyRequest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Condition-PostClientAuthentication.actions.Compose-GetClientDataEntityRequest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Condition-PostClientAuthentication.actions.Condition-GetClientDataEntity.actions.Compose-ClientDataEntityToUser.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Condition-PostClientAuthentication.actions.Condition-GetClientDataEntity.actions.Compose-GetClientTokenRequest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Condition-PostClientAuthentication.actions.Condition-GetClientDataEntity.else.actions.Response-GetClientDataEntityFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Condition-PostClientAuthentication.else.actions.Response-PostClientAuthentication.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.else.actions.Response-GetAuthenticationToken.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.else.actions.Response-GetAuthenticationTokenFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-PostMarketListInsertIdItsNotNull.actions.Condition-SetMarketListProductsItsNotNull.actions.Response-PostMarketListProducts.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-PostMarketListInsertIdItsNotNull.actions.Condition-SetMarketListProductsItsNotNull.else.actions.Response-SetMarketListProductsRequestFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition-PostMarketListInsertIdItsNotNull.else.actions.Response-PostMarketListFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.actions.ActivateTokenSuccessResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.actions.No_data_found_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.actions.TokenActivated.actions.TokenActivatedResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.actions.TokenActivated.else.actions.ActivationSuccessCheck.actions.ActivateTokenSuccessResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.actions.TokenActivated.else.actions.ActivationSuccessCheck.else.actions.ActivationFailResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.else.actions.ActivateTokenFailResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.else.actions.Response_2.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.else.actions.Response_500.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.else.actions.Response_When_Processing_Successful.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.else.actions.Response_When_Storing_Of_Impex_File_Into_Blob_Storage_Failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.else.actions.Response_if_Generate_Dynamic_Header_failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.else.actions.Scope_-Check_if_Retry_Status_Code.actions.Switch.cases.Case_-_Retry.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.else.actions.Success_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition.else.actions.TokenActivationFailResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_-_check_if_b2b_workflow_returned_error.else.actions.Response_-_return_b2b_workflow_error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_-_check_if_headers_contain_valid_values.else.actions.Response_-_return_error_invalid_header.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_2.actions.Loop_Update_Data.actions.Compose_Updates.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_Funding_Response_is_Accepted.actions.For_each.actions.Update_Funding_Invoice_Scope.actions.Add_BulkPaymentID.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_Funding_Response_is_Accepted.actions.For_each.actions.Update_Funding_Invoice_Scope.actions.Add_PaymentEnvelopeID.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_Funding_Response_is_Accepted.actions.Payment_Envelope_Scope.actions.Compose_Payment_Envelope.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_Get_Realtime_Params.actions.Compose_From_FormatEASParams.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_Get_Realtime_Params.else.actions.Compose_Raw_Values_And_Formatted_Params.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.cases.Case_for_RecordDocument.actions.HTTP_to_upload_documents.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.cases.Case_for_RecordDocument.actions.HTTP_to_upload_documents.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.cases.Case_for_RecordDocument.actions.HTTP_to_upload_documents.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.cases.Case_for_RecordDocument.actions.HTTP_to_upload_documents.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.cases.Case_for_RecordDocument.actions.HTTP_to_upload_documents.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.cases.Case_for_RecordDocumentVersion.actions.HTTP_for_Record_Document_Version_Async.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.cases.Case_for_RecordDocumentVersion.actions.HTTP_for_Record_Document_Version_Async.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.cases.Case_for_RecordDocumentVersion.actions.HTTP_for_Record_Document_Version_Async.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.cases.Case_for_RecordDocumentVersion.actions.HTTP_for_Record_Document_Version_Async.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.cases.Case_for_RecordDocumentVersion.actions.HTTP_for_Record_Document_Version_Async.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.default.actions.HTTP_for_update_file_index.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.default.actions.HTTP_for_update_file_index.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.default.actions.HTTP_for_update_file_index.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.default.actions.HTTP_for_update_file_index.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_Application_Details.actions.Switch_for_record_document_type.default.actions.HTTP_for_update_file_index.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_If_Index_Updation_was_successful.actions.HTTP_Request_to_Notify_Task_Retry_Limit.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_If_Index_Updation_was_successful.actions.HTTP_Request_to_Notify_Task_Retry_Limit.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_If_Index_Updation_was_successful.actions.HTTP_Request_to_Notify_Task_Retry_Limit.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_If_Index_Updation_was_successful.actions.HTTP_Request_to_Notify_Task_Retry_Limit.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_If_Index_Updation_was_successful.actions.HTTP_Request_to_Notify_Task_Retry_Limit.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Core_Scope.actions.Delete_processing_folder.runAfter.Transfer_file[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Core_Scope.actions.Transfer_file.actions.Change_filename.runAfter.Set_Extension

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Core_Scope.actions.Transfer_file.actions.Change_filename.runAfter.Set_Extension[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Create_Tracing_Message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Delay_removeAccess.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Delete_file_share_of_SFTP_server.inputs.body.StorageAccountKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Error_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Error_action.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Error_actions.actions.Error_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Exception.actions.Response_Fail.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Exception.actions.Select_first.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Execution.actions.HTTP_Webhook.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Failed_to_insert.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Failure_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Failure_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.File_failure_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.ForEachWorkerFile.actions.IfWorkerFileHasContent.actions.EachWorkerFileLine.actions.ComposeWorker.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.ForEachWorkerFile.actions.IfWorkerFileHasContent.actions.SplitWorkerFileContent.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.ForEach_File.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each.actions.Check_If_Certification.actions.Check_If_Token_is_received.else.actions.Compose_-_Magento-CertAdmin_mapping.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each.actions.Condition.actions.Compose_Additions.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each.actions.Remove_special_characters.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each.actions.Send_AudiencePublishingFailed.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each_BU_ID.actions.HTTP_to_upload_document.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each_BU_ID.actions.HTTP_to_upload_document.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each_BU_ID.actions.HTTP_to_upload_document.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each_BU_ID.actions.HTTP_to_upload_document.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each_BU_ID.actions.HTTP_to_upload_document.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each_curve.actions.Until_-_Curve_response_has_content.actions.Condition_-_If_QueryResult_is_empty_array_("[]")_we_delay_the_loop.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each_of_received_orders.actions.Map_HOT_integration_order_to_Jeans_order.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.For_each_of_received_orders.actions.Map_Jeans_response_to_HOT_order_status_update_model.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Get_BU_details_and_injection_module_index_mappings.actions.Condition_to_validate_injection_module_id.actions.Condition_to_check_customer_id_is_available.actions.HTTP_to_call_retrieveinjectionmodule_function_and_get_index_mappings.inputs.queries.code

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Get_BU_details_and_injection_module_index_mappings.actions.HTTP_To_GetBUDetails.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Get_BU_details_and_injection_module_index_mappings.actions.HTTP_To_GetBUDetails.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Get_BU_details_and_injection_module_index_mappings.actions.HTTP_To_GetBUDetails.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Get_BU_details_and_injection_module_index_mappings.actions.HTTP_To_GetBUDetails.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Get_BU_details_and_injection_module_index_mappings.actions.HTTP_To_GetBUDetails.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Get_ESRP_Document_By_EsrpSubmissionId.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Global_Exception_Scope.actions.NegativeResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_Perform_Contact_Check.inputs.headers.Ocp-Apim-Subscription-Key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_for_record_document_async.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_for_record_document_async.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_for_record_document_async.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_for_record_document_async.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_for_record_document_async.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_call_record_document_async.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_call_record_document_async.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_call_record_document_async.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_call_record_document_async.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_call_record_document_async.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_get_BU_Details.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_get_BU_Details.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_get_BU_Details.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_get_BU_Details.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_get_BU_Details.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_upload_document.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_upload_document.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_upload_document.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_upload_document.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTP_to_upload_document.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Has_source_system_returned_successful_response.else.actions.Failure_cases_switch.cases.401_case.actions.401_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Has_source_system_returned_successful_response.else.actions.Failure_cases_switch.default.actions.502_or_404_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.IfApplicationRowsToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.IfIdsToDelete.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.IfJobApprovalDataRowsToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.IfNeedToCreatIncident.actions.CreateIncident.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.IfNeedToCreatIncident.actions.Response_500.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.IfNeedToCreatIncident.else.actions.Response_200.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.IfNeedToCreateIncident.actions.CreateIncident.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.IfPersonRowsToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.IfRowsToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.If_needs_to_terminate_workflow.actions.CreateIncident.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Inserted_Successfully.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Is_capitaContactArray_not_null.actions.Failed_to_create_file.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Is_capitaContactArray_not_null.actions.File_created.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Is_capitaContactArray_not_null.else.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Is_eventType_eq_create_and_Is_documentType_eq_Testprotokoll.else.actions.NoHandlingNeeded.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Is_username_in_use_in_database.actions.Username_is_in_use_in_database.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Is_username_in_use_in_temporary_storage.actions.Username_is_in_use_in_temporary_storage.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Is_username_in_use_in_temporary_storage.else.actions.Username_is_not_in_use.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.LogWorkflowEnd_Failed.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.LogWorkflowEnd_Succeeded.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.LogWorkflowStart.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Login_Request.actions.Compose_Not_Authorised_response.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.MainScope.actions.CallMediatorServiceToNotify.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.MainScope.actions.CallMediatorServiceToPublish.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Main_scope.actions.Extract_GTIN_webhook.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Main_scope.actions.Extract_sender_GLN_webhook.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Main_scope.actions.Production_transformation_webhook.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Meta_Data_Processing.actions.FirstIndex.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Meta_Data_Processing.actions.LastIndex.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.NotificationTemplateExists.actions.IfRowsToSync.actions.EachRowsToSync.actions.IfHasEmail.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.NotificationTemplateExists.actions.IfRowsToSync.actions.EachRowsToSync.actions.IfRowToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.NotificationTemplateExists.actions.IfRowsToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.On_Failure.actions.Internal_Server_Error_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Primary_actions.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Principal_actions.actions.Condition_-_If_InsertedValue_is_not_null_or_empty.actions.Response_Ok.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Principal_actions.actions.Condition_-_If_InsertedValue_is_not_null_or_empty.else.actions.Response_-_not_inserted_records.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_Article_exist.else.actions.UpdateArticle.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_Counter_exist.else.actions.UpdateCounter.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_Event_exist.else.actions.UpdateEvent.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_Experience_exist.else.actions.UpdateExperience.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_LinkItem_exist.else.actions.UpdateLinkItem.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_NavigatorServiceInfo_exist.else.actions.UpdateNavigatorServiceInfo.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Request_contains_API_User.actions.Respond_to_caller_with_HTTP_code_from_authorise_request.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.RespondToEventHandlerMain.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.RespondToEventhandlerMainWhenSuccessfull.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response-LogicAppSucceeded-Compose.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response-LogicAppSucceeded-SendOrderFormToCheckout.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response-LogicAppSucceeded.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.ResponseNotOkSendToBus.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.ResponseOnAddRightsFailure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.ResponseOnCreateUserFailure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.ResponseRequestReceived.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_-_Error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_-_Error_Accessing_File.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_-_Failed_and_Skipped.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_-_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_-_Timed_Out.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_2.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_Error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_Fail.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_If_Impex_File_Is_Transformed_Successfully.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_If_Impex_File_Transformation_has_failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_If_Transformation_or_Schema_Validation_Failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_KO.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_OK.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_not_found.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_to_show_creditinvoice_in_browser.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Return_HTTP_500.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope-OrderForm-Client.actions.Condition-VTEXOrderFormClient.else.actions.Response-VTEXOrderFormClient.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope-OrderForm-Coupon.actions.Condition-GetOrderForm.actions.Condition-GetOrderForm-CouponCode.actions.Condition-VTEXOrderFormCoupon.actions.Response-VTEXOrderFormCoupon.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope-OrderForm-Coupon.actions.Condition-GetOrderForm.else.actions.Response-GetOrderForm.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition.else.actions.Bad_Request_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_-_Check_Input_App_Name.else.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_-_Check_Token_API_Call_Return_Code.else.actions.Response_-_Failed_API_Token_Call.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_for_checking_status_code.actions.Send_Notification_EventGrid.inputs.headers.aeg-sas-key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_for_checking_status_code.actions.Send_Notification_EventGrid.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_extract_geolab.else.actions.HTTP_to_ExtractGeoLOB.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_extract_geolab.else.actions.HTTP_to_ExtractGeoLOB.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_extract_geolab.else.actions.HTTP_to_ExtractGeoLOB.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_extract_geolab.else.actions.HTTP_to_ExtractGeoLOB.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_extract_geolab.else.actions.HTTP_to_ExtractGeoLOB.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Determine_Success_from_CallResult.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Determine_Success_from_CallResult.else.actions.400_Bad_Request_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Failed_Validation_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.For_each_BU_Detail.actions.HTTP_to_get_Document_Details.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.For_each_BU_Detail.actions.HTTP_to_get_Document_Details.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.For_each_BU_Detail.actions.HTTP_to_get_Document_Details.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.For_each_BU_Detail.actions.HTTP_to_get_Document_Details.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.For_each_BU_Detail.actions.HTTP_to_get_Document_Details.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Get_ReleaseProposalMetadataDocuments_using_ReleaseDocument.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_Request_to_get_BU_Details.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_Request_to_get_BU_Details.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_Request_to_get_BU_Details.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_Request_to_get_BU_Details.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_Request_to_get_BU_Details.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_to_RetrieveInjectionModule.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_to_RetrieveInjectionModule.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_to_RetrieveInjectionModule.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_to_RetrieveInjectionModule.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_to_RetrieveInjectionModule.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_to_get_Application_details.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_to_get_Application_details.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_to_get_Application_details.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_to_get_Application_details.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.HTTP_to_get_Application_details.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.MUPublishingService_Submit.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Send_AudienceCompleted_Notification_to_AWE.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Set_the_Document_to_approved_in_Release_Document.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Until_2.actions.Delay_2.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.ScopeSendToBus.actions.ResponseOkSendToBus.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.Condition_to_extract_geolab_for_MS_Dynamics_and_submission_number_is_null.actions.HTTP_to_ExtractGeoLOB.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.Condition_to_extract_geolab_for_MS_Dynamics_and_submission_number_is_null.actions.HTTP_to_ExtractGeoLOB.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.Condition_to_extract_geolab_for_MS_Dynamics_and_submission_number_is_null.actions.HTTP_to_ExtractGeoLOB.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.Condition_to_extract_geolab_for_MS_Dynamics_and_submission_number_is_null.actions.HTTP_to_ExtractGeoLOB.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.Condition_to_extract_geolab_for_MS_Dynamics_and_submission_number_is_null.actions.HTTP_to_ExtractGeoLOB.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.HTTP_to_RetrieveInjectionModule.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.HTTP_to_RetrieveInjectionModule.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.HTTP_to_RetrieveInjectionModule.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.HTTP_to_RetrieveInjectionModule.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.HTTP_to_RetrieveInjectionModule.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.HTTP_to_get_Application_details.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.HTTP_to_get_Application_details.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.HTTP_to_get_Application_details.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.HTTP_to_get_Application_details.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_.actions.HTTP_to_get_Application_details.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_2.actions.500_Internal_Server_Error_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_Contact.actions.#_Contacts.cases.Case_No_Contact.actions.Response:_Failed_to_create_new_Contact.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_Contact.actions.#_Contacts.cases.Case_One_Contact.actions.Response:_Failed_to_update_Contact.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_Contact.actions.#_Contacts.default.actions.Response:_Multiple_Contacts_found_with_same_HID.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_Contact.actions.Scope_Lookup_Account.actions.If_one_Account_is_found.else.actions.Response:_No_Account_found.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_for_sending_Payment_Envelope_on_Queue_for_Bulk_Payment.actions.For_each_loop_to_send_a_Payment_Envelope_for_Bulk_Payment.actions.Condition_to_check_count_of_Payment_Items_in_Payment_Envelope.actions.Condition_to_check_total_amount_of_Payment_Items_in_Payment_Envelope.actions.Compose_Payment_Envelope_message_with_CorrelationId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Send_request_to_Sender.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Source_system_scope.actions.400_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Success_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Switch.cases.Case_ADT_A08.actions.Catch_ADT_A08.actions.Response_Error_AD_A08.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Switch.cases.Case_ADT_A08.actions.Try_ADT_A08.actions.Response_Success_ADT_A08.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Switch.cases.Case_Create.actions.Response_POST.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Switch.cases.Case_ORG_O20.actions.Try_ORG_O20.actions.Response_ORG_O20.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Switch.cases.Case_Update.actions.Response_PATCH.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Switch.default.actions.Response_Error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Switch_'Doelapplicatie'.cases.Case:_Navision.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Switch_Entity.cases.Case_Project.actions.Response:_Failed_exactonlineproject-cla.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Trigger_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Try.actions.If_payment_is_paymentCanonical_2.actions.Routing_to_GL.actions.File_name_Outbound_GL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Try.actions.Set_Outbound_GL_Filename.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Try_Scope.actions.HTTP_Retrieve_BLOB.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.TurnToAppliucationxml.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.TurnToJSON.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Until_Oracle_job_is_ended.actions.Compose_Entity_update.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Until_Oracle_job_is_ended.actions.If_jobStatus_is_"Running".actions.Wait_before_retry.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.User_Not_Found.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Wait_For_Execution.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.checkIfRemotecontrollabilityExists.cases.Case.actions.Remotecontrollability_already_exists.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.if_mandate_exists.actions.Check_reg_status_and_bank_account_in_both_CE_and_FO.actions.Check_for_CE_bank_account.actions.Execute_delay_if_bank_account_not_found_in_FO.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.pingSite.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.workflows-get-all-elo-files.inputs.body.RecursionUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.outputs.result.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$AGTBOpsEmail.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$AGTBOpsSupportEmailAddress.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$BulkPaymentPollerQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$BulkPaymentQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$CashWithdrawalQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$CommonApiManagementBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$DataAccessApiCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$DbtrAdrLine.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$DbtrBIC.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$DbtrCtry.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$DbtrIBAN.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$DbtrNm.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$Environment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$LGA26_Time_Frequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$LGA26_Time_Interval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$LGA26_Time_Zone.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$LoanCRUDQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$MambuBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$MambuGroupUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$MambuUserName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$MambuUserPwd.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$NotificationApiCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$NotificationProcessingUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$OutstandingLoansNotificationQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$PainBuilderFunctionApp.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$PaymentReferenceUtilityApiCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$SvtFenergoCotsApplicationName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$SvtLegalEntityAdvanceQueryUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$SvtMambuCotsApplicationName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$SvtServiceManagementBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$SvtServiceManagementGetCotsIdUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TFSNonFundedBuyerInvoicesPollerQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TIXClientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TIXFundingResponseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TIXGetCompanyUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TIXGetInvoiceUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TIXInvoiceStatusQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TIXLedgerInvoiceUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TIXScope.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TIXSupplierUName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TIXTokenUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TixClientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TixUsrPwd.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$TokenGrantType.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$Ustr.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$appErrorCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$appErrorMessage.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$bcCompanies.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$bcCountry.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$bcUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$blobFolderPathTestStorage.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$blobFolderPathToStoreMQMessagesTest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$commonApiManagementBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$connections.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$creditCheckQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$currency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$dataAccessApiCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$errorLogUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$errorMessage.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$eventType.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$exceptionHandlerUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$fundingResponseAcceptedStatus.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$keyVaultUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$logicAppName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$mambuApiUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$mambuLoanFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$mambuUserName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$mambuUserPwd.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$nextInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$nextTimeUnit.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$notificationApiCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$notificationProcessingUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$onedrive_srcFolderId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$paramEmailTo.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$paramTopicInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$paymentEnvelopeFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$paymentEnvelopeStatusForBulkPayment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$paymentIDGeneratorUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$pollFrequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$pollInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$programUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$queueTriggerFrequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$queueTriggerInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$recurrenceFrequencyOfLogicApp.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$recurrenceIntervalOfLogicAppInSeconds.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$svtCountryCodeQueryUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$svtDataApiBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$svtLegalEntityAdvanceQueryUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$svtLegalEntityDetailUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$svtPaymentEnvelopeAdvanceQueryUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$svtPaymentItemAdvanceQueryUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$tixFundingRequestFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$tixFundingRequestQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$tixFundingResponseApiQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$tixFundingResponseFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$tixFundingResponseQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$tixFundingResponseTriggerQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$uri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.APIM.Audience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.APIM.ClientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.APIM.ClientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.APIM.Instance.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.APIM.Tenant.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.AfPrISSFTP_app_service_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ApproverGroup.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.AssociatedFunctionApp.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.AuditDescription.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.AzureFileStoragePath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.BaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.BisNodeLoginPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.BisNodeLoginUserName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.BlobContainerNameInput.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.BlobContainerNameOutput.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.BulkUploadInstance.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.BusinessFragmentName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.CRMOrganization.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.CRM_org_id.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.CSVToJSONFunctionCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.CSVToJSONFunctionUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.CommonResourceGroupName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.CreatedByIntegrationUser.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.D365FoUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.D3FOClientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.DmfFunctionName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.DynamicsCE-la.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.DynamicsOps-la.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.EmailTo.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ErrorMailRecipients.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ErrorNotificationEmail.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ExportDefinitionId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.FTPFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.Flow_SubscribeURI_SendingEmailToApprovers.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.Function.Audience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.Function.ClientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.Function.ClientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.FunctionalModuleName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ICMStaticValues.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.InputFileName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.IntegrationAccountName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.InvictusAPIKey1.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.LegalEntityId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.LogicAppName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.MailTo.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.MapName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ModifiedByIntegrationUser.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.NfsaApiKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.OutputFileName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.Receiver.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ReviewerGroup.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.RootFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SPORootSite.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SPOSitePlant.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SchemaNameIn.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SchemaNameOut.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SecureInput.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SecureInputOutput.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SecureOutput.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SqlServer.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.StorageAccountName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.StormQueryApiApplicationId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.StormQueryApiApplicationKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.StormQueryApiBaseUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SystemDescription.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.TimeZone.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.TransformationTempFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.action.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apiConnections.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.api_KustoQuery_baselinesTable.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.api_KustoQuery_cluster.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.api_KustoQuery_database.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.api_KustoQuery_host.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.api_KustoQuery_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.api_KustoQuery_trace.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.api_KustoQuery_version.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apiappclientid.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apiappsecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apiapptenant.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apimSubscriptionKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apim_IntuneSecOps_LibraryFunctions_AppId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apim_IntuneSecOps_LibraryFunctions_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apim_IntuneSecOps_LibraryFunctions_trace.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apisubscriptionkey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.app_service_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.archivePath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.armTemplate.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.automationAccount.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.azureDevops_Project_Name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.azurefunctionappname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.azurefunctionname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.basicDataUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.basic_auth.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.blobContainerName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.bookingsappaction.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.businessprocessname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.cdlaudience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.cdlclientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.cdlsecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.cdluri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.cdsEnvironment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.clientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.clientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.commondataservice_OrganizationUniqueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.composeCartLinesUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.container_Name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.conversationstage.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.crmEndpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.crmdataset.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.customerName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.d365ServicesHost.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.deleteTransferJournalUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.deleteTransferOrderUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.destinationDirectory.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.dynamicsBaseEndpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.dynamicsOAuthBody.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.dynamicscrmCaamOrg.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.dynamicscrmOrg.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.dynamicscrmUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.dynamicscrmonline_path.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.emailAdressForIntegrationAlert.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.employeeDetailUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.entityAction.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.entityActionWebhook.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.entityIdProperty.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.entityName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.environmentname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.eventName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.fileExtension.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.filesystem_1_password.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.filesystem_1_username.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ftpErrorFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ftpPickupFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.function_code.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.function_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.hoursToGoBack.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.idsrv4_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ignoreErrorOnActions.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.inputFileNamePattern.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.integrationAccountMapName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.invictusAuthenticationObject.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.invictusPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.job_name_full_sync_job.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.job_name_sync_job.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.localgeneration.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.logWorkflow.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.logicAppAuthentication.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.logicAppName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.loginUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.mail_recipients.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.mail_subject_full_webjob.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.mapName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.mdm_password_key_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.mdm_root_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.mdm_username.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.messageSerialisationService.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.notificationEmail.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.oAuth.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.oAuthPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.oAuthUsername.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ocpApimSubscriptionKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.originsystemname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.postTransferJournalUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.processmaxcount.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.prodigiCredentials.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.prodigiInstance.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.publishTransferOrderUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.pwd_ohi.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.queue-name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.queueLockDuration.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.queuename.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.receiverid.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.recurrencyFrequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.recurrencyInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.remedy_apibaseUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.salesforceUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sbSubscriptionName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sb_subscr_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sb_topic_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sendOmToSapLogicAppUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.senderid.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sftp_1_hostName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sftp_1_password.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sftp_1_portNumber.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sftp_1_userName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sharepointonline_1_Connection_DisplayName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.shipTransferOrderUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sourcesystem.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sourcesystemname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.staffingCustomerId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.status_change_topic_listener_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.status_change_topic_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.stripeProdKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.stripeTestKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.subfolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.taskName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.teamsWebHook.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.templateParameters.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.tenantId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.tenantid.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.testURI.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.testUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.timeZoneName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.tokenResource.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.topicName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.transferJournalNameId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.transformName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.transformResponseName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.user_ohi.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.webhookUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.DQ_Reports_Scheduler.recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.DQ_Reports_Scheduler.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* (1)        | No Swagger            |

### \$.properties.definition.triggers.DQ_Reports_Scheduler.recurrence.startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.DQ_Reports_Scheduler.recurrence.timeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.EveryDay.recurrence.startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.EveryNight.recurrence.startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.Recurrence.recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.Recurrence.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.Recurrence.recurrence.startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.Recurrence.recurrence.timeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.Recurrence.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.Trigger for Scheduler App.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.WhenAMessageIsReceivedInTheBannerChangesTopic.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Default* (3)        | No Swagger            |

### \$.properties.definition.triggers.When_a_Message_Is_Received_in_the_Entity_Topic_Subscription_(Peek-Lock).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Default* (3)        | No Swagger            |

### \$.properties.definition.triggers.When_a_file_is_added_or_modified_(properties_only).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* (1)        | No Swagger            |

### \$.properties.definition.triggers.When_a_message_is_received_in_a_queue_(peek-lock).recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.When_a_message_is_received_in_a_queue_(peek-lock).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.When_a_message_is_received_in_a_topic_subscription_(auto-complete).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Default* (3)        | No Swagger            |

### \$.properties.definition.triggers.When_a_message_is_received_in_invoice_poll_starter_queue_(peek-lock).recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.When_a_message_is_received_in_invoice_poll_starter_queue_(peek-lock).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* (3)        | No Swagger            |

### \$.properties.definition.triggers.When_a_message_is_received_in_non_funded_invoice_poll_starter_queue_(peek-lock).recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.When_a_message_is_received_in_non_funded_invoice_poll_starter_queue_(peek-lock).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* (3)        | No Swagger            |

### \$.properties.definition.triggers.When_a_message_is_received_in_topic_subscription.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.When_one_or_more_messages_arrive_in_a_topic_(auto-complete).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* (3)        | No Swagger            |

### \$.properties.definition.triggers.addBlob.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.manual.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.manual.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-02-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2019-05-01         | Unknown             | No Swagger            |

### \$.properties.definition.triggers.recurrence.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.endpointsConfiguration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-02-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2019-05-01         | Unknown             | Unknown               |

### \$.properties.integrationServiceEnvironment.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.integrationServiceEnvironment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$TixClientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$TixUsrPwd

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.FaciliaConnector.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.GandalfApiConnector.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.azureblob.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.azureeventgridpublisher.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.azurequeues.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.commonDataservice.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.documentdb.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.dynamicsAx.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.dynamicscrmonline.connectionId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.excelonlinebusiness.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.filesystem.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.servicebus.connectionId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.servicebus.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.sharepointonline.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.sql.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$passwords

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$portalAppHost.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$syncAdvertisements.value.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$uri.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$webAppHost.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.APIM.ClientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.AS2EncodeAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.AppClientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.BTSAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.BisNodeLoginPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.BisNodeLoginUserName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.BuckeyeAuthAPI Password.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.BuckeyeAuthAPI Password.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.BuckeyeAuthAPI Username.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.BuckeyeAuthAPI Username.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.CRMOrganisationName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.CSVToJSONFunctionCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.CSVToJSONFunctionUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ClientAuthPFX

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ClientAuthPFXPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ClientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ClientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.CreateEmailBodyFunctionUri.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.CreateReportFunctionUri.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ErrorNotificationEmail.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.FileShareAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.Function.ClientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.GWR Operations Load API Key.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.GWR Operations Load API Key.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.GetLogsFunctionToken.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.Honeywell API Authentication id.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.Honeywell API Authentication id.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.Honeywell API Password.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.Honeywell API Password.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.HttpAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.HttpWithAadAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.LappAPIPwd

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.LappAPIUsr

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.NewConfirmEnquiryWebHookURL.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.Nexiot API Key.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.Nexiot API Key.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.Nexiot API UserName.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.Nexiot API UserName.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.OpenAccessPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.OpenAccessUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ProcessConfigAPI Key.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ProcessConfigAPI Key.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ProcessConfigAPI URL.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ProcessConfigAPI URL.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.RootFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ServiceHealthRouterV2Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.SftpFileAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.SoapSyncHttpAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.SubscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.TixApiClientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.TixApiUsrPwd

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.WashingtonCustomAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.api-wattsight-clientid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.api-wattsight-clientsecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.apiKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.api_key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.apiappclientid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.apiappsecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.apimSubscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.apisubscriptionkey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.appSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.armTemplate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.azure_search_api_key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.client_secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.composeCartLinesUrl.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.custom_auth_key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.d365secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.dhlFusion_workingDirectory.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.dynamicsOAuthBody

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.filesystem_1_password.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.filesystem_1_username.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.invictusPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.netivePassword.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.netiveUsername.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.oAuthPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.oAuthUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.pwd_ohi.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.pwd_ohi.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.sendOmToSapLogicAppUrl.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.subfolder.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.templateParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.user_ohi.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.user_ohi.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.webhookUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.youforceApiClientId.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.youforceApiClientSecret.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.runtimeConfiguration.lifetime.unit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.state

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-02-01-preview | Unknown             | Unknown               |
| 2016-06-01         | Unknown             | Unknown               |
| 2017-07-01         | Unknown             | No Swagger            |
| 2019-05-01         | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |
| 2016-10-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |
| 2017-07-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | Unknown               |
