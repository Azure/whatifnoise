# Microsoft.Logic

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## integrationAccounts/agreements

![cleanliness](https://img.shields.io/badge/cleanliness-99.85%25%20(651%20/%20652)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.content.aS2.sendAgreement.protocolSettings.mdnSettings.receiptDeliveryUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

## integrationAccounts/maps

![cleanliness](https://img.shields.io/badge/cleanliness-61.11%25%20(11%20/%2018)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.content

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.contentType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

## integrationAccounts/partners

![cleanliness](https://img.shields.io/badge/cleanliness-90.91%25%20(10%20/%2011)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.content.b2b.partnerClassification

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

## integrationAccounts/schemas

![cleanliness](https://img.shields.io/badge/cleanliness-78.95%25%20(15%20/%2019)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties.content

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.contentType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.documentName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.targetNamespace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

## integrationAccounts

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.integrationServiceEnvironment.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.integrationServiceEnvironment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

## integrationserviceenvironments

![cleanliness](https://img.shields.io/badge/cleanliness-92.86%25%20(39%20/%2042)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.properties.endpointsConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Unknown               |

### \$.properties.integrationServiceEnvironmentId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

## workflows

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-75.59%25%20(1211%20/%201602)-yellowgreen)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.accessControl.actions.allowedCallerIpAddresses[*].addressRange

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.accessControl.contents.allowedCallerIpAddresses[*].addressRange

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.accessControl.triggers.allowedCallerIpAddresses[*].addressRange

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-06-01  | Unknown             | Put-as-patch                                          |
| 2017-07-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.definition.actions.400_-_Failed_XSLT_due_to_invalid_input.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.500_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Accepted.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.AddRightsResult.actions.Success_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.AddRightsResult.else.actions.AddRightsFailureResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Any_records_to_process.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Any_records_to_process.else.actions.Success_response_if_no_data.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Application_Scope.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Application_Scope.actions.Response_schema_validation_error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Authorization_Failed_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.BasicData_Request.actions.Condition.actions.Compose_Not_Found_Response.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.BasicData_Request.actions.Condition.actions.Response_NotFound_BasicData.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.BasicData_Request.actions.Condition.else.actions.Compose_Error_Response.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.BasicData_Request.actions.Condition.else.actions.Response_ERROR_BasicData.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Business_Scope.actions.PositiveResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Call_CIS.actions.Authorised_for_NVR.else.actions.Organization_not_authorized_for_NVR.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Call_CIS.actions.CIS_Response.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Call_CIS.actions.Response_CIS_ERROR.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Call_Document_Manager_to_check_if_File_Exists.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Call_Update_Flight_Metadata.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Call_to_FLS.actions.Send_response_from_fls_back.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check if valid json received with statusCode 200.actions.Check_If_BillingAddress_is_null.actions.For_each_BillingAddress.actions.Compose_BillingAddresses.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check if valid json received with statusCode 200.actions.Check_If_ShippingAddress_is_null.actions.For_each_ShippingAddress.actions.Compose_ShippingAddresses.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check if valid json received with statusCode 200.actions.Compose_TrackedProperties_Get_BasicProfileInformation_Error.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check if valid json received with statusCode 200.actions.Compose_TrackedProperties_Get_Billing_address_Error.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check if valid json received with statusCode 200.actions.Compose_TrackedProperties_Get_OAuth2_token_from_ESP3_Error.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check if valid json received with statusCode 200.actions.Compose_TrackedProperties_Get_PhoneNumber_Error.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check if valid json received with statusCode 200.actions.Compose_TrackedProperties_Get_Shipping_address_Error.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check if valid json received with statusCode 200.actions.Compose_TrackedProperties_Get_UserName_Error.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check if valid json received with statusCode 200.else.actions.Compose_TrackedProperties_Invalid_Json.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.CheckIfAccountFound.actions.CreateAccountUpdateMessage.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.CheckIfNeedToCreateIncident.actions.CreateIncident.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_If_Data_Factory_Processing_Was_Successful.actions.Check_If_ML_Engine_Processing_Was_Complete.actions.Wait_For_Promotion_Callback_From_Client.actions.Check_Promotion_Callback_Status.else.actions.Delay_2.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_If_Data_Factory_Processing_Was_Successful.actions.Check_If_ML_Engine_Processing_Was_Complete.actions.Wait_For_Recommendations_To_Be_Verified.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_If_Data_Factory_Processing_Was_Successful.actions.Wait_1_Minute_For_ML_Engine_To_Start_Processing.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_If_Data_Factory_Processing_Was_Successful.actions.Wait_Until_ML_Engine_Processing_Completes.actions.Check_If_ML_Engine_Processing_Was_Successful.else.actions.Wait_5_Minutes.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_IsSuccessAPICall_Condition_On_MapAndCall_Failed.else.actions.Return_Failed_Response_For_IsSuccessAPICall_On_MapAndCall_Fail.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_IsSuccessAPICall_Condition_On_MapAndCall_Success.actions.Return_Success_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_IsSuccessAPICall_Condition_On_MapAndCall_Success.else.actions.Return_Failed_Response_For_IsSuccessAPICall_On_MapAndCall_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_Scope_Status.actions.Response_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_Scope_Status.else.actions.Response_ErrorOccurred.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_Status.actions.Check_current_contractor.actions.compose_map_input.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_Templates.actions.Send_message_to_Sender-Boards_for_wiki.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_ESRP_Scan_Passed.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_if_ESRP_Scan_Passed.else.actions.Call_Esrp_Wrapper_to_Check_Current_Esrp_Status.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_if_ESRP_Scan_Passed.else.actions.Check_if_ESRP_Release_Passed_or_InProgress.actions.Send_Success_Response_back.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_if_ESRP_Scan_Passed.else.actions.Persist_Scan_Status_in_the_database_through_Document_Manager.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_if_Esrp_Submission_Passed.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_if_Esrp_Submission_Passed.else.actions.CreateIncident.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_if_IFS_returned_an_empty_body.actions.Response_-_IFS_returned_an_empty_body.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_if_Submission_is_Needed.else.actions.Check_if_Esrp_Document_was_already_created_in_the_Database.actions.Create_Esrp_Document_in_Cosmos_DB.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_if_file_was_downloaded.actions.Response_Ok.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_if_file_was_downloaded.else.actions.Response_KO.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_if_list_contains_files.actions.For_each_file_in_list.actions.Lookup_And_Replace_Values_(Async).inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_there's_a_LpeCorrelationId.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_topic_is_PipelinesManagement.actions.Send_request_to_Sender.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_if_we_need_to_create_a_new_CRM_Account.else.actions.Check_if_we_need_to_read_Owner_from_Account.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_isCreate.actions.Check_for_errors.actions.Send_to_SignalR_failed.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_isCreate.actions.Check_for_errors.else.actions.Send_to_SignalR_successful.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_isCreate.else.actions.Check_for_errors_2.actions.Send_to_SignalR_failed_2.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_isCreate.else.actions.Check_for_errors_2.else.actions.Send_to_SignalR_failed_3.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Check_logWorkflow_value.actions.Compose_log_data.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_the_Status_of_Payment_Envelope_Record.cases.If_Status_of_Payment_Envelope_is_Open.actions.Scope_for_creating_and_sending_Payment_Message.actions.Compose_Body_for_Supplier_Bank_Address.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_the_Status_of_Payment_Envelope_Record.cases.If_Status_of_Payment_Envelope_is_Open.actions.Scope_for_creating_and_sending_Payment_Message.actions.Compose_Body_for_Supplier_Counterparty_Address.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_the_Status_of_Payment_Envelope_Record.cases.If_Status_of_Payment_Envelope_is_Open.actions.Scope_for_creating_and_sending_Payment_Message.actions.Compose_Payment_Message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_whether_we_need_to_submit_this_File_to_Esrp.actions.Add_LogicApp_RunDetail_to_EsrpDocument_in_the_Cosmos_DB.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_whether_we_need_to_submit_this_File_to_Esrp.actions.Call_Esrp_Submission_Service.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Check_whether_we_need_to_submit_this_File_to_Esrp.actions.Update_the_latest_Esrp_Submission_Information_in_the_database.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose_-_Response_Blob_Reference.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose_-_TrackedProperties_-_Send_quoteCreate_to_magento_-_Error.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose_AccountToWebsiteMap.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose_Blob_Name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose_Email_Notification_Message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose_ErklaerungFernsteuerbarkeitBlob.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose_Log_Message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose_PrintJob.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose_Remove_Namespace.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Compose_loadErrors.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Compose_productinfoCollection_To_post.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Compose_utc_dates.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Compose-ClientAuthenticationRequest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Compose-SendAccessKeyRequest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Condition-PostClientAuthentication.actions.Compose-GetClientDataEntityRequest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Condition-PostClientAuthentication.actions.Condition-GetClientDataEntity.actions.Compose-ClientDataEntityToUser.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Condition-PostClientAuthentication.actions.Condition-GetClientDataEntity.actions.Compose-GetClientTokenRequest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Condition-PostClientAuthentication.actions.Condition-GetClientDataEntity.else.actions.Response-GetClientDataEntityFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.actions.Condition-PostClientAuthentication.else.actions.Response-PostClientAuthentication.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.else.actions.Response-GetAuthenticationToken.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetAuthenticationToken.else.actions.Response-GetAuthenticationTokenFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetClientDataEntity.actions.Condition-GetAuthenticationToken.actions.Compose-SendAccessKeyRequest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetClientDataEntity.actions.Condition-GetAuthenticationToken.else.actions.Response-GetAuthenticationTokenFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-GetClientDataEntity.else.actions.Response-GetClientDataEntity-Failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-PostMarketListInsertIdItsNotNull.actions.Condition-SetMarketListProductsItsNotNull.actions.Response-PostMarketListProducts.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-PostMarketListInsertIdItsNotNull.actions.Condition-SetMarketListProductsItsNotNull.else.actions.Response-SetMarketListProductsRequestFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition-PostMarketListInsertIdItsNotNull.else.actions.Response-PostMarketListFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.actions.ActivateTokenSuccessResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.actions.ESRP_Scan_Completed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.actions.No_data_found_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.actions.Ok.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.actions.Response_2.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.actions.Response_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.actions.TokenActivated.actions.TokenActivatedResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.actions.TokenActivated.else.actions.ActivationSuccessCheck.actions.ActivateTokenSuccessResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.actions.TokenActivated.else.actions.ActivationSuccessCheck.else.actions.ActivationFailResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.ActivateTokenFailResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.ESRP_Scan_Failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.Error_Reponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.Response_2.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.Response_500.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.Response_Failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.Response_When_Processing_Successful.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.Response_When_Storing_Of_Impex_File_Into_Blob_Storage_Failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.Response_if_Generate_Dynamic_Header_failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.Scope_-Check_if_Retry_Status_Code.actions.Switch.cases.Case_-_Retry.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.Success_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition.else.actions.TokenActivationFailResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ConditionOcvTypeAllowed.actions.DelayInitial.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_-_check_ErrorString.actions.No_gaps_found_for_any_TripStatus_(0_,1,_2).type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_-_check_if_b2b_workflow_returned_error.else.actions.Response_-_return_b2b_workflow_error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_-_check_if_headers_contain_valid_values.else.actions.Response_-_return_error_invalid_header.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_-_check_request_parameters.actions.Response_-_NotFound_(File_does_not_exists).kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_-_check_request_parameters.actions.Response_-_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_-_check_request_parameters.else.actions.Response_-_NotFound_(Request_is_invalid).kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_-_if_service_item.actions.Response_2.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_2.actions.Loop_Update_Data.actions.Compose_Updates.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_File_vaildation.actions.Compose.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_File_vaildation.actions.Telemetry_End_Success.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_File_vaildation.else.actions.Telemetry_End_Error.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_Funding_Response_is_Accepted.actions.For_each.actions.Update_Funding_Invoice_Scope.actions.Add_BulkPaymentID.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_Funding_Response_is_Accepted.actions.For_each.actions.Update_Funding_Invoice_Scope.actions.Add_PaymentEnvelopeID.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_Funding_Response_is_Accepted.actions.Payment_Envelope_Scope.actions.Compose_Payment_Envelope.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_Get_Realtime_Params.actions.Compose_From_FormatEASParams.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_Get_Realtime_Params.else.actions.Compose_Raw_Values_And_Formatted_Params.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_To_Check_GridSchedule_Status.actions.Until_GridQueue_Is_Flushed.actions.Standard_Loop_Delay_Flush_GridQueue.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_if_Get_Order_succeeds.actions.Response_OK.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_if_Get_Order_succeeds.else.actions.Response_Error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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

### \$.properties.definition.actions.Condition_to_check_If_Index_Updation_was_successful.actions.Check_if_Submission_Notify.actions.Check_if_SubmissionNumber_is_correct.actions.Send_Submission_Msg_to_Notify_Event_Grid.inputs.headers.aeg-sas-key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_If_Index_Updation_was_successful.actions.Check_if_Submission_Notify.actions.Check_if_SubmissionNumber_is_correct.actions.Send_Submission_Msg_to_Notify_Event_Grid.inputs.uri

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

### \$.properties.definition.actions.Condition_to_check_If_Index_Updation_was_successful.actions.Send_Error_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Condition_to_check_event_type.actions.Response_ICC_will_process_the_request_further.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_to_check_event_type.else.actions.Response_ICC_will_not_process_the_request_further.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Condition_wait_for_other_jobs_to_finish.actions.Until_no_other_jobs_running.actions.Delay_-_checking_no_other_jobs_running.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Core_Scope.actions.Delete_processing_folder.runAfter.Transfer_file[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Core_Scope.actions.Transfer_file.actions.Change_filename.runAfter.If_delete_original_file[*]

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

### \$.properties.definition.actions.Core_Upload_Document_Process.actions.Send_Message_to_event_grid.inputs.headers.aeg-sas-key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Core_Upload_Document_Process.actions.Send_Message_to_event_grid.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Core_Upload_Document_Process.actions.Until.actions.Condition_to_check_the_Status_of_Upload_Document.actions.HTTP_Failure_Call_to_Event_Grid.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Core_Upload_Document_Process.actions.Until.actions.Condition_to_check_the_Status_of_Upload_Document.else.actions.HTTP_success_Call_to_Event_Grid.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Core_Upload_Document_Process.actions.check_value_of_document_upload_flag.else.actions.Check_if_Submission_Notify.actions.Check_if_SubmissionNumber_is_correct.actions.Send_Submission_Msg_to_Notify_Event_Grid.inputs.headers.aeg-sas-key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Core_Upload_Document_Process.actions.check_value_of_document_upload_flag.else.actions.Check_if_Submission_Notify.actions.Check_if_SubmissionNumber_is_correct.actions.Send_Submission_Msg_to_Notify_Event_Grid.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Core_Upload_Document_Process.actions.check_value_of_document_upload_flag.else.actions.Check_if_Submission_Notify.else.actions.Check_if_Claim_Notify.actions.Send_Claim_Msg_to_Notify_Event_Grid.inputs.headers.aeg-sas-key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Core_Upload_Document_Process.actions.check_value_of_document_upload_flag.else.actions.Check_if_Submission_Notify.else.actions.Check_if_Claim_Notify.actions.Send_Claim_Msg_to_Notify_Event_Grid.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Create_Tracing_Message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Decode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Delay_in_sequential_debatching.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Delay_removeAccess.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Delete_file_share_of_SFTP_server.inputs.body.StorageAccountKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Different_paths_based_upon_status_code_of_call_to_Gov.UK_Pay.cases.201_-_Success.actions.Response_with_success_information.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Different_paths_based_upon_status_code_of_call_to_Gov.UK_Pay.cases.422_-_content_has_problems.actions.Response_with_error_information.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Error_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Error_action.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Error_actions.actions.Error_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Error_response_on_export_to_package_failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Error_response_on_query_execute_status_failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Error_response_on_query_execution_status_failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Error_response_on_run_export_failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Exception.actions.Condition.actions.Compose.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Exception.actions.Condition.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Exception.actions.Condition.else.actions.Response_2.kind

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.FailedResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Failed_to_insert.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Failure_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Failure_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.File_failure_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Finally.actions.Has_Application_Run_Succeeded.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Finally.actions.Has_Application_Run_Succeeded.else.actions.Error_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ForEachWorkerFile.actions.IfWorkerFileHasContent.actions.EachWorkerFileLine.actions.ComposeWorker.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ForEachWorkerFile.actions.IfWorkerFileHasContent.actions.SplitWorkerFileContent.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ForEach_Error.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ForEach_File.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.ForEach_Message.actions.If_ActionIsDeleted.else.actions.Transform.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ForEach_Message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.Check_If_Certification.actions.Check_If_Token_is_received.else.actions.Compose_-_Magento-CertAdmin_mapping.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.Compose_SalesOrderDetailsCount_.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.Condition.actions.Compose.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.Condition.actions.Compose_Additions.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.Condition.actions.Error_Desc.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.Condition.actions.rowKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.ErrorLogging_2.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.ErrorLogging_2.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.ErrorLogging_2.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.ErrorLogging_2.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.ErrorLogging_2.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.Remove_special_characters.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.Run_Mapping_Job.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each.actions.Send_AudiencePublishingFailed.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_-_invoice_found.actions.Condition_-_Check_the_invoice_has_a_valid_supplier.actions.Condition_-_check_if_business_object_created_.actions.Condition_-_check_on_return_status_-_200_-_exists.actions.put-core-businessobject_-_Update_existing_Invoice_Business_Object.inputs.subscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_-_invoice_found.actions.Condition_-_Check_the_invoice_has_a_valid_supplier.actions.Condition_-_check_if_business_object_created_.actions.Condition_-_check_on_return_status_-_200_-_exists.else.actions.post-core-businessobject_-_Create_new_Invoice_Business_Object.inputs.subscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_-_invoice_found.actions.Condition_-_Check_the_invoice_has_a_valid_supplier.actions.Condition_-_check_if_business_object_created_.actions.get-core-businessobject_-_Check_if_Business_Object_already_exists.inputs.subscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_-_invoice_found.actions.Condition_-_Check_the_invoice_has_a_valid_supplier.actions.get-core-businessobjects_-_Get_PSF_-_Coupa_code_mapping.inputs.subscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_2.actions.Compose_2.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_of_received_orders.actions.Map_HOT_integration_order_to_Jeans_order.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_of_received_orders.actions.Map_Jeans_response_to_HOT_order_status_update_model.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Check_language.actions.Fr_Body_Bottom.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Check_language.actions.Fr_Body_Top.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Check_language.actions.Fr_Footer.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Check_language.actions.Fr_Subject.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Check_language.else.actions.De_Body_Bottom.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Check_language.else.actions.De_Body_Top.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Check_language.else.actions.De_Footer.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Check_language.else.actions.De_Subject.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Contact_information.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Get_Logo_Url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.HTML_style.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Mail_cc.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Mail_from.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Mail_to.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.MeteringPointFirstRowTable.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Switch.cases.French.actions.Fr_Body_Bottom.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Switch.cases.French.actions.Fr_Body_Top.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Switch.cases.French.actions.Fr_Footer.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Switch.cases.French.actions.Fr_Subject.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Switch.default.actions.De_Body_Bottom.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Switch.default.actions.De_Body_Top.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Switch.default.actions.De_Footer.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_there_were_no_errors.actions.Check_if_we_want_to_send_e-mails.actions.Switch.default.actions.De_Subject.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Check_if_this_is_the_first_quote_version.actions.Quote_has_one_Historisches_Profil.actions.Wait_until_rollout_is_finished.actions.Delay_and_wait_for_the_rollout_finished.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_quote.actions.Check_if_the_VC_is_released.actions.Wait_2_minutes_(Calculation_may_take_so_long).type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.For_each_run_parameter.actions.Acknowledge_Forbund_ManuelBehandling.runAfter.Start_Dispatcher_AR_005[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Foreach_Product.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Global_Exception_Scope.actions.NegativeResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.HTTP.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.HTTPResponseToTrigger.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.HTTP_Perform_Contact_Check.inputs.headers.Ocp-Apim-Subscription-Key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.HTTP_Request_to_Error_Logging_for_Unhandled_Exception.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.HTTP_Request_to_Error_Logging_for_Unhandled_Exception.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.HTTP_Request_to_Error_Logging_for_Unhandled_Exception.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.HTTP_Request_to_Error_Logging_for_Unhandled_Exception.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.HTTP_Request_to_Error_Logging_for_Unhandled_Exception.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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

### \$.properties.definition.actions.Handle_execution_status.actions.Error_response_on_download_exported_file_failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Handle_execution_status.actions.Error_response_on_get_execution_history_record_failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Handle_execution_status.actions.Error_response_on_get_exported_file_url_failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Handle_execution_status.actions.Success_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Handle_execution_status.else.actions.Error_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Handle_execution_status.else.actions.Error_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Has_source_system_returned_successful_response.else.actions.Failure_cases_switch.cases.401_case.actions.401_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Has_source_system_returned_successful_response.else.actions.Failure_cases_switch.default.actions.502_or_404_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.IfApplicationRowsToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.IfIdsToDelete.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.IfJobApprovalDataRowsToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.IfNeedToCreatIncident.actions.CreateIncident.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.IfNeedToCreatIncident.actions.Response_500.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.IfNeedToCreatIncident.else.actions.Response_200.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.IfNeedToCreateIncident.actions.CreateIncident.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.IfNeedToCreeateIncident.actions.CreateIncident.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.IfPersonRowsToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.IfRowsToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_Applier_URI.actions.204_-_Applied.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_Applier_URI.actions.400_-_Applier_Failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_Applier_URI.else.actions.204_-_No_Action_Needed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_Errors.actions.Response_Failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.If_Errors.else.actions.Response_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.If_Request_Contains_Result.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_Request_Contains_Result.else.actions.Response_2.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_SubscriptionPublishSend.actions.Create_SubscriptionPublish_Message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_multiple_'EndOfLoad'_messages_per_batch.actions.POST_error_because_too_many_ENDOFLOAD_messages.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_multiple_'EndOfLoad'_messages_per_batch.actions.POST_error_because_too_many_ENDOFLOAD_messages.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_multiple_'EndOfLoad'_messages_per_batch.actions.POST_error_because_too_many_ENDOFLOAD_messages.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_multiple_'EndOfLoad'_messages_per_batch.actions.POST_error_because_too_many_ENDOFLOAD_messages.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_multiple_'EndOfLoad'_messages_per_batch.actions.POST_error_because_too_many_ENDOFLOAD_messages.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.If_needs_to_terminate_workflow.actions.CreateIncident.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Initialize_variable.inputs.variables[*].value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Inserted_Successfully.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_Clear_Bank_response_HTTP_400.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_Clear_Bank_response_HTTP_400.else.actions.Response_2.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_WorkOrder_in_Sync_Status.actions.204_-_Done.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_WorkOrder_in_Sync_Status.actions.400_-_Failure_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_WorkOrder_in_Sync_Status.else.actions.204_-_No_Action_Needed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_capitaContactArray_not_null.actions.Failed_to_create_file.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_capitaContactArray_not_null.actions.File_created.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_capitaContactArray_not_null.else.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_eventType_eq_create_and_Is_documentType_eq_Testprotokoll.else.actions.NoHandlingNeeded.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_username_in_use_in_database.actions.Username_is_in_use_in_database.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_username_in_use_in_temporary_storage.actions.Username_is_in_use_in_temporary_storage.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Is_username_in_use_in_temporary_storage.else.actions.Username_is_not_in_use.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.LogWorkflowEnd_Failed.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.LogWorkflowEnd_Succeeded.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.LogWorkflowStart.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Log_Error_for_Exception.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Log_Error_for_Exception.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Log_Error_for_Exception.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Log_Error_for_Exception.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Log_Error_for_Exception.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Login_Request.actions.Compose_Not_Authorised_response.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.MainScope.actions.CallMediatorServiceToNotify.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.MainScope.actions.CallMediatorServiceToPublish.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.MainScope.actions.For_each.actions.Send_AudiencePublishingFailed.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Main_scope.actions.Check_DefaultSender.else.actions.Extract_sender_GLN_webhook.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Main_scope.actions.Extract_GTIN_webhook.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Main_scope.actions.Extract_sender_GLN_webhook.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Main_scope.actions.Production_transformation_webhook.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Meta_Data_Processing.actions.FirstIndex.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Meta_Data_Processing.actions.LastIndex.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.NotificationTemplateExists.actions.IfRowsToSync.actions.EachRowsToSync.actions.IfHasEmail.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.NotificationTemplateExists.actions.IfRowsToSync.actions.EachRowsToSync.actions.IfRowToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.NotificationTemplateExists.actions.IfRowsToSync.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.On_Failure.actions.Internal_Server_Error_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_Counter_exist.else.actions.UpdateCounter.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_Event_exist.else.actions.UpdateEvent.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_Experience_exist.else.actions.UpdateExperience.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_LinkItem_exist.else.actions.UpdateLinkItem.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_NavigatorServiceInfo_exist.else.actions.UpdateNavigatorServiceInfo.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_Product_exist.else.actions.UpdateProduct.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_SubCategory_exist.else.actions.UpdateSubCategory.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Publish_to_Graph.actions.IsDeletedRequest.else.actions.Does_TrainingType_exist.else.actions.UpdateTrainingType.runAfter.Set_variable_operation_update[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.RESP.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.RESP_200.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Reply_OK_unless_from_file_caching.default.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Request_contains_API_User.actions.Respond_to_caller_with_HTTP_code_from_authorise_request.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.RespondToEventHandlerMain.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.RespondToEventhandlerMainWhenSuccessfull.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response-Failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response-LogicAppSucceeded-Compose.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response-LogicAppSucceeded-SendAccessKey.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response-LogicAppSucceeded-SendOrderFormToCheckout.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response-LogicAppSucceeded.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response-Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response.kind

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-06-01  | Unknown             | Put-as-patch                                          |
| 2017-07-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.definition.actions.ResponseNotOkSendToBus.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ResponseOnAddRightsFailure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ResponseOnCreateUserFailure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ResponseRequestReceived.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_-_Error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_-_Error_Accessing_File.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_-_Failed_and_Skipped.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_-_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_-_Timed_Out.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_-_error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_2.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_3.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_4.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_Cannot_Create_File.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_Error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_Fail.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_Failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_Failed_on_Deliver.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_Failure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_If_Impex_File_Is_Transformed_Successfully.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_If_Impex_File_Transformation_has_failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_If_Session_Is_Not_Valid.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_If_Transformation_or_Schema_Validation_Failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_KO.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_OK.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Response_failed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_if_Session_Is_Not_Valid.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_not_found.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_to_show_creditinvoice_in_browser.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_with_Error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Response_with_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Retrive_IDOC_xml_from_Blob_after_decryption.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Retry_copy_scope.actions.Until.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Return_HTTP_500.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.SWIT.cases.Called_from_LoadProcess.actions.RESP.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Save_Idocxml_to_Blob_With_Encryption.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope-Catch.actions.Response-CatchError.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope-OrderForm-Client.actions.Condition-VTEXOrderFormClient.else.actions.Response-VTEXOrderFormClient.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope-OrderForm-Coupon.actions.Condition-GetOrderForm.actions.Condition-GetOrderForm-CouponCode.actions.Condition-VTEXOrderFormCoupon.actions.Response-VTEXOrderFormCoupon.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope-OrderForm-Coupon.actions.Condition-GetOrderForm.else.actions.Response-GetOrderForm.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope-Try.actions.DoesRequestIncludeSalesforceAccountID.actions.Switch-UpdateAccountResult.default.actions.Response-UpdateAccountFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope-Try.actions.DoesRequestIncludeSalesforceAccountID.else.actions.Switch-CreateAccountResult.default.actions.Response-CreateAccountFailed.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope-Try.actions.DoesRequestIncludeSalesforceShippingAddressID.actions.Switch-UpdateShipToRecordResult.default.actions.Response-UpdateShipToRecordFailure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope-Try.actions.DoesRequestIncludeSalesforceShippingAddressID.else.actions.Switch-CreateShipToRecordResult.default.actions.Response-CreateShipToRecordFailure.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope-Try.actions.Does_ShippingAddress_Exist.actions.Did_Shipping_Address_Upsert_Fail.actions.Failed_Response-Shipping_Address_Upsert.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope-Try.actions.Response-Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Call_DCAT_Add_Audience.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Check_ESRP_Certification_Status.actions.Response_Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Condition.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Condition.else.actions.Bad_Request_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Condition_-_Check_Input_App_Name.else.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Condition_-_Check_Token_API_Call_Return_Code.else.actions.Response_-_Failed_API_Token_Call.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Condition_for_checking_status_code.actions.Send_Notification_EventGrid.inputs.headers.aeg-sas-key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_for_checking_status_code.actions.Send_Notification_EventGrid.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_Check_if_detain_is_record_present_or_not.else.actions.Check_if_AIM_returned_Success_or_not.else.actions.HTTP_Request_to_Error_Logging_Service.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Condition_to_Check_if_detain_is_record_present_or_not.else.actions.Check_if_AIM_returned_Success_or_not.else.actions.HTTP_Request_to_Error_Logging_Service.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Condition_to_Check_if_detain_is_record_present_or_not.else.actions.Check_if_AIM_returned_Success_or_not.else.actions.HTTP_Request_to_Error_Logging_Service.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Condition_to_Check_if_detain_is_record_present_or_not.else.actions.Check_if_AIM_returned_Success_or_not.else.actions.HTTP_Request_to_Error_Logging_Service.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Condition_to_Check_if_detain_is_record_present_or_not.else.actions.Check_if_AIM_returned_Success_or_not.else.actions.HTTP_Request_to_Error_Logging_Service.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.actions.Condition_to_check_Crud_service__response.actions.Check_if_AIM_return_success_or_not.else.actions.Log_Error_for_AIM_failure.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.actions.Condition_to_check_Crud_service__response.actions.Check_if_AIM_return_success_or_not.else.actions.Log_Error_for_AIM_failure.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.actions.Condition_to_check_Crud_service__response.actions.Check_if_AIM_return_success_or_not.else.actions.Log_Error_for_AIM_failure.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.actions.Condition_to_check_Crud_service__response.actions.Check_if_AIM_return_success_or_not.else.actions.Log_Error_for_AIM_failure.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.actions.Condition_to_check_Crud_service__response.actions.Check_if_AIM_return_success_or_not.else.actions.Log_Error_for_AIM_failure.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.actions.Condition_to_check_Crud_service__response.else.actions.Log_Error_for_CRUD_service_failure.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.actions.Condition_to_check_Crud_service__response.else.actions.Log_Error_for_CRUD_service_failure.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.actions.Condition_to_check_Crud_service__response.else.actions.Log_Error_for_CRUD_service_failure.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.actions.Condition_to_check_Crud_service__response.else.actions.Log_Error_for_CRUD_service_failure.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.actions.Condition_to_check_Crud_service__response.else.actions.Log_Error_for_CRUD_service_failure.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.else.actions.Log_Error_for_invalid_entity.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.else.actions.Log_Error_for_invalid_entity.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.else.actions.Log_Error_for_invalid_entity.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.else.actions.Log_Error_for_invalid_entity.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope.actions.Condition_to_check_if_Entity_is_Valid.else.actions.Log_Error_for_invalid_entity.inputs.uri

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Determine_Success_from_CallResult.else.actions.400_Bad_Request_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Failed_Validation_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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

### \$.properties.definition.actions.Scope.actions.Generate_MSDN_Spreadsheet_with_TTGL,_Number_of_Files,ESRP_IDs_and_SHA256_Hash.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Get_ReleaseProposalMetadataDocuments_using_ReleaseDocument.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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

### \$.properties.definition.actions.Scope.actions.Login_Status_Code.cases.Case_200_-_Success.actions.Switch.cases.Case_200_-_Success.actions.Compose_Success_Response.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Login_Status_Code.cases.Case_200_-_Success.actions.Switch.default.actions.Compose_CreatePlan_Failure.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Login_Status_Code.default.actions.Compose_Login_failed.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.MUPublishingService_Submit.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Process_Payload.actions.Condition.else.actions.ErrorLogging.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Process_Payload.actions.Condition.else.actions.ErrorLogging.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Process_Payload.actions.Condition.else.actions.ErrorLogging.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Process_Payload.actions.Condition.else.actions.ErrorLogging.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Process_Payload.actions.Condition.else.actions.ErrorLogging.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.ResponseNotOkSendToBusSkipped.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Send_AudienceCompleted_Notification_to_AWE.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Set_the_Document_to_approved_in_Release_Document.inputs.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.ShouldSendFormSalesForce.actions.ResponseNotOkSendToBus.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.ShouldSendFormSalesForce.actions.ScopeSendToBus.actions.ResponseOkAcceptContent.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.ShouldSendFormSalesForce.else.actions.ResponseOkEmptyContent.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.ShouldSendFromE1.actions.ResponseNotOkSendToBus.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.ShouldSendFromE1.actions.ScopeSendToBus.actions.ResponseOkAcceptContent.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.ShouldSendFromE1.else.actions.ResponseOkEmptyContent.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Until_2.actions.Delay_2.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Until_Audience_Submission_Status_:_Completed.actions.Get_Audience_Submission_Status.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope.actions.Verify_Targeting.inputs.subscribe.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ScopeSalesForceGet.actions.Condition.else.actions.DelayBeforeRunning.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.ScopeSendToBus.actions.ResponseOkSendToBus.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope_-_Try.actions.For_Each_-_Message.actions.get-core-businessguid.inputs.subscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope_-_Try.actions.For_Each_-_Message.actions.put-core-systemobject.inputs.subscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope_All.actions.Condition_No_Result.actions.Response_No_Result.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope_All.actions.Response_Succeeded.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope_All.actions.Response_succeeded.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope_Bloomberg_Process.actions.Decide_Success.actions.Until_Success_or_Max_Retry.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Scope_to_Send_Message_to_DCT.actions.Condition_to_Check_Response_from_DCT.else.actions.Send_Submission_Msg_to_Notify_Event_Grid.inputs.headers.aeg-sas-key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Scope_to_Send_Message_to_DCT.actions.Condition_to_Check_Response_from_DCT.else.actions.Send_Submission_Msg_to_Notify_Event_Grid.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.SendToQueue.actions.CheckSendMessageVariable.actions.TryToSendMessageToQueue.actions.RetryIfNotSuccessful.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Send_Request_to_Sender-Repo.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Send_request_to_Sender.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Send_to_Sender-Boards.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Send_to_Sender_topic:_pipelines.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Sjekk_om_det_er_noen_betalingspåminnelser_som_oppfyller_kravene.actions.Looper_betalingspåminnelsene.actions.Invoice_State_Is_Issued,_not_EHF,_invoice_not_paid_and_enterpriseplan.actions.Sjekker_om_det_er_betalingspåminnelser_som_skal_sendes.else.actions.Compose_Supplements_table.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Sjekk_om_det_er_noen_betalingspåminnelser_som_oppfyller_kravene.actions.Looper_betalingspåminnelsene.actions.Invoice_State_Is_Issued,_not_EHF,_invoice_not_paid_and_enterpriseplan.actions.Sjekker_om_det_er_betalingspåminnelser_som_skal_sendes.else.actions.Compose_utc_dates.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Source_system_scope.actions.400_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Source_system_scope.actions.400_response_at_validate_request.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Source_system_scope.actions.Failure_cases_switch.cases.400_case.actions.400_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Source_system_scope.actions.Failure_cases_switch.cases.401_case.actions.401_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Source_system_scope.actions.Failure_cases_switch.default.actions.502_or_404_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Source_system_scope.actions.Has_source_system_returned_successful_response.actions.Success_cases_switch.cases.200_case.actions.Final_response_transformation_scope.actions.200_response_at_modality.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Source_system_scope.actions.Has_source_system_returned_successful_response.actions.Success_cases_switch.default.actions.204_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Success.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Success_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Success_Scope.actions.Check_error_length.actions.Success_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Success_Scope.actions.Check_error_length.else.actions.Response_DB_Error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Success_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch.cases.Acos.actions.AcosResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch.cases.Case.actions.Slate_Updated_Scope.actions.Delay_Clearing_Cache.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch.cases.Case_ADT_A08.actions.Catch_ADT_A08.actions.Response_Error_AD_A08.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch.cases.Case_ADT_A08.actions.Try_ADT_A08.actions.Response_Success_ADT_A08.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch.cases.Case_Create.actions.Response_POST.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch.cases.Case_Dispatcher_2018.actions.Response_2018.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Switch.cases.Case_ORG_O20.actions.Try_ORG_O20.actions.Response_ORG_O20.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch.cases.Case_Update.actions.Response_PATCH.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch.cases.Gerica.actions.GericaResponse.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch.default.actions.Response_Error.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch_'Doelapplicatie'.cases.Case:_Navision.actions.Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch_Deliver_Via.cases.Case_AS2.actions.Response_AS2.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch_Deliver_Via.cases.Case_FTP.actions.Response_AllscriptsFTP.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch_Deliver_Via.cases.Case_HTTPs.actions.Condition.actions.Response_No_Auth.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch_Deliver_Via.cases.Case_HTTPs.actions.Condition.else.actions.Response_with_Auth.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch_Deliver_Via.default.actions.Response_no_Deliver_Via.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Switch_Entity.cases.Case_Project.actions.Response:_Failed_exactonlineproject-cla.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Telemetry_Start.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Terminate_if_ID_or_name_is_empty.actions.Return_400.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Track_Sku_Number.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Trigger_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Trigger_response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Try.actions.If_payment_is_paymentCanonical_2.actions.Routing_to_GL.actions.File_name_Outbound_GL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Try.actions.Set_Outbound_GL_Filename.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Try.actions.Until_a_message_is_received_from_response_queue.actions.Delay_retry.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Try_Scope.actions.HTTP_Retrieve_BLOB.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Try_Scope.actions.Loop_until_Status_Order_is_returned_with_1_or_2.actions.Delay_Get_Status_Information.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.TurnToAppliucationxml.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.TurnToJSON.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until.actions.Condition.else.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until.actions.For_each.actions.Condition.actions.postMessage.inputs.subscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.UntilSuccess.actions.ConditionSuccess.else.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.UntilSuccess.actions.DelayBuffer.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Until_-_Loop_Tripstatus_0_to_2.actions.Condition_check_if_there_is_any_records_to_check.actions.Check_for_gaps.actions.No_gaps_found_for_current_status.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_-_Loop_Tripstatus_0_to_2.actions.Condition_check_if_there_is_any_records_to_check.actions.Show_parameters.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_GridSchedule_Has_Data.actions.Standard_Loop_Delay_GridSchedule.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_Oracle_job_is_ended.actions.Compose_Entity_update.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Until_Oracle_job_is_ended.actions.If_jobStatus_is_"Running".actions.Wait_before_retry.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Until_paging_is_complete.actions.Check_we_have_results.actions.For_each.actions.Condition.actions.Check_we_need_to_update.actions.Patch_Scope.actions.Compose_Updates.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_paging_is_complete.actions.Check_we_have_results.actions.For_each.actions.Condition.actions.Post_scope.actions.Compose_Additions.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_paging_is_complete.actions.Check_we_have_results.actions.For_each.actions.Does_Project_Exist.else.actions.Condition.actions.Post_to_SO_Scope.actions.Compose_Additions.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_scopeDF_deployment.actions.Delay_scopeDF_deployment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.Until_sqs_messages_available.actions.Error_handling_scope.actions.If_sqs_message_exists.actions.Finish_batch_processing_if_EndOfLoad.actions.Is_number_of_EndOfLoad_GW_DataFeed_rows_valid.actions.Start_Batch_Publish_Logic_App.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_sqs_messages_available.actions.Error_handling_scope.actions.If_sqs_message_exists.actions.Finish_batch_processing_if_EndOfLoad.actions.Is_number_of_EndOfLoad_GW_DataFeed_rows_valid.actions.Start_Batch_Publish_Logic_App.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_sqs_messages_available.actions.Error_handling_scope.actions.If_sqs_message_exists.actions.Finish_batch_processing_if_EndOfLoad.actions.Is_number_of_EndOfLoad_GW_DataFeed_rows_valid.actions.Start_Batch_Publish_Logic_App.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_sqs_messages_available.actions.Error_handling_scope.actions.If_sqs_message_exists.actions.Finish_batch_processing_if_EndOfLoad.actions.Is_number_of_EndOfLoad_GW_DataFeed_rows_valid.actions.Start_Batch_Publish_Logic_App.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_sqs_messages_available.actions.Error_handling_scope.actions.If_sqs_message_exists.actions.Finish_batch_processing_if_EndOfLoad.actions.Is_number_of_EndOfLoad_GW_DataFeed_rows_valid.actions.Start_Batch_Publish_Logic_App.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_sqs_messages_available.actions.For_each.actions.POST_unknown_logic_app_error.inputs.queries.api-version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_sqs_messages_available.actions.For_each.actions.POST_unknown_logic_app_error.inputs.queries.sig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_sqs_messages_available.actions.For_each.actions.POST_unknown_logic_app_error.inputs.queries.sp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_sqs_messages_available.actions.For_each.actions.POST_unknown_logic_app_error.inputs.queries.sv

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Until_sqs_messages_available.actions.For_each.actions.POST_unknown_logic_app_error.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Update_employee_entity.actions.If_employee_is_already_disabled.actions.Response_employee_already_disabled.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.User_Not_Found.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Validation_Failed_Response.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Wait_For_Execution.inputs.subscribe.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.Wait_Until_Data_Factory_Processing_Completes.actions.Condition.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.catch.runAfter.try[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.checkIfRemotecontrollabilityExists.cases.Case.actions.Remotecontrollability_already_exists.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.decode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.finally.runAfter.catch[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.if_mandate_exists.actions.Check_reg_status_and_bank_account_in_both_CE_and_FO.actions.Check_for_CE_bank_account.actions.Execute_delay_if_bank_account_not_found_in_FO.actions.Delay.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.pingSite.inputs.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.actions.qaHTTPAction.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.response_202.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.actions.workflows-get-all-elo-files.inputs.body.RecursionUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.outputs.dataAreaId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.outputs.eInvoiceAddress.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.outputs.eInvoiceId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.outputs.env.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.outputs.fileName.type

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$AGTBOpsSupportEmailAddress.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$BulkPaymentPollerQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$BulkPaymentQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$CashWithdrawalQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$CommonApiManagementBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$DataAccessApiCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$DbtrAdrLine.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$DbtrBIC.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$DbtrCtry.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$DbtrIBAN.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$DbtrNm.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$Environment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$KeyVaultName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$LGA26_Time_Frequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$LGA26_Time_Interval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$LGA26_Time_Zone.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$LoanCRUDQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$MambuBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$MambuGroupUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$MambuUserName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$MambuUserPwd.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$NotificationApiCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$NotificationProcessingUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$OutstandingLoansNotificationQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$PainBuilderFunctionApp.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$PaymentReferenceUtilityApiCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$SvtFenergoCotsApplicationName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$SvtLegalEntityAdvanceQueryUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$SvtMambuCotsApplicationName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$SvtServiceManagementBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$SvtServiceManagementGetCotsIdUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TFSNonFundedBuyerInvoicesPollerQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TIXClientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TIXFundingResponseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TIXGetCompanyUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TIXGetInvoiceUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TIXInvoiceStatusQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TIXLedgerInvoiceUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TIXScope.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TIXSupplierUName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TIXTokenUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TixClientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TixUsrPwd.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$TokenGrantType.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$Ustr.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$abbyyLocation.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$accessTokenRequest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$apimOGPBaseUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$appErrorCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$appErrorMessage.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$bcCompanies.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$bcCountry.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$bcUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$blobFolderPathTestStorage.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$blobFolderPathToStoreMQMessagesTest.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$commonApiManagementBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$connections.type

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-06-01  | Unknown             | Put-as-patch                                          |
| 2017-07-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.definition.parameters.$creditCheckQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$currency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$d365_ClientID.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$d365_OrgRegion.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$d365_URL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$dataAccessApiCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$dataBaseCollectionOutBox.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$dataBaseID.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$documentuploadqueue.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$errorLogUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$errorMessage.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$eventType.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$exceptionHandlerUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$fundingResponseAcceptedStatus.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$galaxy_passupdatedtrigger_blob_filepath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$hcmLoginUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$keyVaultUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$logicAppName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$mambuApiUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$mambuLoanFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$mambuUserName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$mambuUserPwd.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$maxItemToProcess.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$nextInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$nextTimeUnit.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$notificationApiCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$notificationProcessingUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$onedrive_srcFolderId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$paramEmailTo.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$paramTopicInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$partitionkey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$paymentEnvelopeFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$paymentEnvelopeStatusForBulkPayment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$paymentIDGeneratorUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$pollFrequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$pollInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$programUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$queueTriggerFrequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$queueTriggerInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$recurrence.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$recurrenceFrequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$recurrenceFrequencyOfLogicApp.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$recurrenceInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$recurrenceIntervalOfLogicAppInSeconds.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$sharepointurl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.$storageServiceBusBlobFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$storageServiceBusMessagesUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$subscriptionName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$svtCountryCodeQueryUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$svtDataApiBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$svtLegalEntityAdvanceQueryUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$svtLegalEntityDetailUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$svtPaymentEnvelopeAdvanceQueryUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$svtPaymentItemAdvanceQueryUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$tixFundingRequestFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$tixFundingRequestQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$tixFundingResponseApiQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$tixFundingResponseFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$tixFundingResponseQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$tixFundingResponseTriggerQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$topicName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$uri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$webhook.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$workflowsqldwusername.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$zslDbName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$zslFTZUser.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$zslIssueApiUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$zslMsgApiUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$zslShipmentApiUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$zslShipmentTrackingApiUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.$zslSqlServer.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.AKFunctionName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.APIM.Audience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.APIM.ClientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.APIM.ClientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.APIM.Instance.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.APIM.Tenant.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Aad_audience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Aad_authority.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Aad_clientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Aad_secret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Aad_tenant.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.AfPrISSFTP_app_service_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ApiKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ApproverGroup.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.AssociatedFunctionApp.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Audience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.AuditDescription.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.AzureFileStoragePath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.BaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.BisNodeLoginPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.BisNodeLoginUserName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.BusinessFragmentName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.CRMEnvironment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.CRMOrganization.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.CRM_org_id.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.CSVToJSONFunctionCode.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.CSVToJSONFunctionUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ClientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.CommonResourceGroupName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.CoreDbConnection.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Create_Ticket_La_Url_LA.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.CreatedByIntegrationUser.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.CustomeridMailTesting.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.D365FoUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.D365Secret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.D3FOClientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.DmfFunctionName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.Dynamics365_ClientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Dynamics365_Secret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.DynamicsCE-la.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.DynamicsOps-la.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.EMDToAllegroFutureForwardPriceProcessCustomLogType.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.EMDToAllegroOptionsPriceProcessCustomLogType.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.EOM.Audience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.EOM.ClientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.EOM.ClientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.EmailTo.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.EnableApprissQueue.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.EnablePIIQueue.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.EnableTloQueue.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.EnableTransunionQueue.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ErrorMailRecipients.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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

### \$.properties.definition.parameters.FTPFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Flow_SubscribeURI_SendingEmailToApprovers.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Function Audience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.Function.Audience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Function.ClientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Function.ClientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.FunctionThrowFailedUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.FunctionalModuleName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.GetBlobPathURL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.GetCosmos_authorization_code.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.GtResource.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.HTTP-Authorization.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.HTTP-Password.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.HTTP-Username.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ICMStaticValues.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.IFSUsernameAndPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ImportDbConnection.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.InitializeLogicAppName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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

### \$.properties.definition.parameters.ListaMappeEdEntita.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.LogicAppCreateTargetFileUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.LogicAppInitializeUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.LogicAppMoveFilesUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.LogicAppName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.LogicAppTransformUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.MailSender.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.MailTo.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.MapName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ModifiedByIntegrationUser.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.NfsaApiKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.OMSWorkspaceName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.OMSWorkspaceResourceGroup.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.OrganizationId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.OutputFileName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.Receiver.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.RecurrenceFrequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.RecurrenceInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ResourceGroupName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.RestServiceBklBaseUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.RestServiceBklBearerToken.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ReviewerGroup.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.RootFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SPORootSite.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.SPOSitePlant.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.SchemaNameIn.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.SchemaNameOut.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.Secret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.SecureInput.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.SecureInputOutput.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.SecureOutput.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.SendMail.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ServiceBusSubscription.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.SqlServer.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.StorageAccountName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.StormLaundryUserRole.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.StormQueryApiApplicationId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.StormQueryApiApplicationKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.StormQueryApiBaseUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.StormQueryApiFilterCustomerInfoTypes.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.StormQueryApiSelectCustomer.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.StormQueryTopFilterKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.StormQueryTopFilterValue.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.SubscriptionId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.SystemDescription.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.TargetFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Tenant.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.TikosBaseUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.TikosPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.TikosUsername.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.TimeZone.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.TransformMapping1.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.TransformMapping2.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.TransformSourceSchema.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.TransformTargetSchema.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.TransformationTempFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.Username.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters._environmentName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters._objectSuffix.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.action.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.addressTypes.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.apiConn.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apiConnections.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.apiVersion.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.apiappsecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.apiapptenant.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.apigee_metadados_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.apigee_token_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.apigee_token_user.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.apimSubscriptionKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.app_service_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.applicationCompletedEventType.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.archivePath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.armTemplate.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.audience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.authHeader.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.automationAccount.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ax_api_base.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ax_api_key.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.azureDevops_Project_Name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.azureStorageConnectionKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.azureblob_Connection_DisplayName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.azureblob_accountName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.azurefunctionappname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.azurefunctionname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.baseApiUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.baseProxyUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.basicDataUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.basic_auth.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.blob.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.blobContainerName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.bomJournalNameId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.bookingsappaction.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.businessprocessname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.cdlaudience.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.cdlclientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.cdlsecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.cdluri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.cdsEnvironment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.clientId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.clientSecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.clientTenant.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.client_id.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.client_secret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.cmAppURL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.commondataservice_OrganizationUniqueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.composeCartLinesUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.consumerGroupName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.container_Name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.conversationstage.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.coreAPIURL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.createBomJournalUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.createBomServiceUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.crmBaseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.crmEndpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.crmdataset.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.crmurl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ctp_ErrorLocation.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ctp_FileLocation.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ctp_ProcessedLocation.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.customerMultiplier.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.customerName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.customerNumSeqServiceUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.d365Secret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.d365ServicesHost.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.d365Url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.dataFactoryMainFeedName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.dataFactoryName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.dateType.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.defaultSender.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.deleteJournalUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.deleteTopicName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.deleteTransferJournalUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.deleteTransferOrderUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.denaliApiBase.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.destinataire.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.destinationDirectory.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.documentdbDatabaseIdLA.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.dynamics365Instance.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.dynamicsBaseEndpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.dynamicsOAuthBody.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.dynamicscrmCaamOrg.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.dynamicscrmOrg.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.dynamicscrmUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.dynamicscrmonline_path.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.emailAdressForIntegrationAlert.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.emailFromQueue.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.emos_web_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.employeeDetailUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.endpointPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.endpointUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.endpointUsername.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.entityAction.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.entityActionWebhook.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.entityIdProperty.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.entityName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.env.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.environmentname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.environnement.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.errorTopic.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.error_email_from.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.error_email_to.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.error_retry_count.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.error_retry_interval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.etape.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.eventHubsInstanceName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.eventName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.eventSubscription.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.eventTopic.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.eventhubFunctionAppName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.eventhubFunctionName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.excelConnectionDisplayName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.excelConnectionName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.excelKeyColumn.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.excelPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.excelTableId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.fileExtension.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.fileIngestionDataTableName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.fileName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.fileUploadQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.filesystem_1_password.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.filesystem_1_rootfolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.filesystem_1_username.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.fixedLocationsUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.flsPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.flsUsername.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ftpErrorFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ftpPickupFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.functionAppNameInternal.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.function_code.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.function_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.functionalArea.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.fyi_api_access_key.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.gateAPIURL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.gateway_URI.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.genderCodes.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.getLocationUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.hoursToGoBack.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.httpDataSourceApiBase.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.httpDataSourceUser.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.httpendpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.hub_azure_tenant_id.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.hub_client_id.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.hub_client_secret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.hub_la_set_execution_state_queue_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.hub_solution_id.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.hub_tenant_id.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.hub_tenant_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.idsrv4_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ignoreErrorOnActions.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.infravisionSftpPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.inputFileNamePattern.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.integrationAccountMapName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.interval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.invictusAuthenticationObject.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.invictusPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.iserver365_client_id.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.itemWeightServiceUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.job_name_full_sync_job.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.job_name_sync_job.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.journalName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.keyVault_Url_LA.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.l_CRMOrganization.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.l_EnvironmentPrefix.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.l_ResourceGroupName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.l_ServicebusQueueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.l_SubscriptionId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.liquidTransformName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.localgeneration.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.logWorkflow.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.logicApp.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.logicAppAuthentication.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.logicAppGeneralAccessKeySecret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.logicAppLocationIdInternal.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.logicAppName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.loginUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.magentoQuoteCreateApi.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.mail_recipients.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.mail_subject_full_webjob.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.mapName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.masterCompany.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.mdm_password_key_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.mdm_root_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.mdm_username.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.message.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.messageSerialisationService.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.mlEngineEndpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.mlEngineProgressEndpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.mlEngineProgressEndpointKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ndssFaGeneralAccessAppId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ndssLaGeneralAccessAppId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ndssResourceGroup.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ndssTenantId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.nestedExportCustomerXlsxLogicAppName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.nestedExportCustomersXlsxLogicAppName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.notificationEmail.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.numSeqServiceUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.oAuth.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.oAuthPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.oAuthUsername.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ocpApimSubscriptionKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.ohi_path_policy.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ohi_path_procedure_groups.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ohi_path_product_details.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ohi_path_product_types.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.ohi_path_service_definitions.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.orbusbi_url.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.order_api_base.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.order_api_key.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.originsystemname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.packageAPIWhereFileNameEquals.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.partitionKeyParameter.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.policies_accept.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.postJournalUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.postTransferJournalUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.prefixes.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.prepareemailQueueStorageName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.processmaxcount.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.prodigiCredentials.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.prodigiInstance.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.profileAddressURL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.profileBasicInfoURL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.profilePhoneNumberURL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.profileUserNameURL.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.promotionsCallbackEndpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.promotionsCallbackEndpointKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.promotionsEndpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.promotionsEndpointKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.promotionsGetClientResponseFileKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.promotionsGetClientResponseFileUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.promotionsUpdateEventStatusFromClientResponseKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.promotionsUpdateEventStatusFromClientResponseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.providernumber_querystring.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.proxyToken.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.publishTransferOrderUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.pwd_ohi.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.queue-name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.queueLockDuration.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.queueName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.queue_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.queuename.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.receiverid.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.recurrencyFrequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.recurrencyInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.releasedProdDefUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.remedy_apibaseUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.remedy_workOrderUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.report_file.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.resourceGroupName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.resourcegroup.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.rootSftpFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.salesforceSoapApiLoginEndpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.salesforceUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sbSubscriptionName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sb_subscr_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sb_topic_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.secret.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sendOmToSapLogicAppUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.senderid.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.serviceBus.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.serviceBusConnectionString.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sftpFolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sftpServerId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sftp_1_hostName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sftp_1_password.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sftp_1_portNumber.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sftp_1_userName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sharePointFailedFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sharePointSiteAddress.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sharePointSuccessfulFolderPath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.sharepointUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sharepointonline_1_Connection_DisplayName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.shipLocation.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.shipTransferOrderUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.slackChannel.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sourceDirectoryAndFile.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sourceSystem.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sourcesystem.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sourcesystemname.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sp-apim-subscription-keys.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sp-azure-resources-urls.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sp-external-urls.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sp-la-access-token-request.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sp-la-gaia-api-credentials.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.sp-tenant-id.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.splitXpathExpression.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.staffingCustomerId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.state_querystring.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.stripeTestKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.subfolder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.subscriptionDisplayName-laparam.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.suburb_querystring.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.surname_querystring.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.targetFileName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.targetFilePath.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.targetMetaDataId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.taskName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.taskTopic.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.teamsWebHook.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.templateParameters.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.tenant.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.tenantId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.tenantid.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.testURI.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.testUri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.timeZone.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.timeZoneName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.toEmail-laparam.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.tokenResource.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.tokenazurefunction_logManagement.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.tokenazurefunction_reportgeneration.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.topicName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.topic_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.topic_subscription_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.tracking.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.transaction_function_authorization_code.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.transaction_function_base_uri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.transaction_function_uri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.transaction_pipeline_eod_authorization_code.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.transaction_pipeline_sale_authorization_code.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.transferJournalNameId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.transformName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.transformResponseName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.triggerFrequency.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.triggerHours.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.triggerInterval.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.triggerMinutes.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.triggerStartTime.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.uniqueCollectionString.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.uri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.url_policies.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.url_proddef.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.user_ohi.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.vwacApiKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.webhookUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.winteamApiUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.workspace_folder.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.parameters.xpTemplatesEndpoint.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.xpTemplatesEndpointKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.xylem_azureblob_accountName_receive.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.parameters.xylem_azureblob_accountName_send.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.DQ_Reports_Scheduler.recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.DQ_Reports_Scheduler.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* (1)        | Put-as-patch          |

### \$.properties.definition.triggers.DQ_Reports_Scheduler.recurrence.startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.DQ_Reports_Scheduler.recurrence.timeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.EveryDay.recurrence.startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.EveryNight.recurrence.startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.Recurrence.recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.Recurrence.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.Recurrence.recurrence.schedule.hours[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.Recurrence.recurrence.startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.Recurrence.recurrence.timeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.Recurrence.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.Recurrence_Trigger.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.Reef_generated_a_document_for_Saddle_Creek.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* (1)        | Put-as-patch          |

### \$.properties.definition.triggers.Trigger for Scheduler App.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.WhenAMessageIsReceivedInTheBannerChangesTopic.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Default* (3)        | No Swagger            |

### \$.properties.definition.triggers.When_a_Message_Is_Received_in_the_Entity_Topic_Subscription_(Peek-Lock).recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.When_a_Message_Is_Received_in_the_Entity_Topic_Subscription_(Peek-Lock).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Default* (3)        | No Swagger            |

### \$.properties.definition.triggers.When_a_Recently_Created_or_Updated_File_Is_In_Folder.recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.When_a_Recently_Created_or_Updated_File_Is_In_Folder.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Default* (3)        | No Swagger            |

### \$.properties.definition.triggers.When_a_file_is_added_or_modified_(properties_only).recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.When_a_file_is_added_or_modified_(properties_only).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.When_a_file_is_added_or_modified_(properties_only).recurrence.startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.When_a_message_is_received_in_a_queue_(peek-lock).recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.When_a_message_is_received_in_a_queue_(peek-lock).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.When_a_message_is_received_in_a_topic_subscription_(auto-complete).recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.When_a_message_is_received_in_a_topic_subscription_(auto-complete).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.definition.triggers.When_a_message_is_received_in_a_topic_subscription_(peek-lock).recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.When_a_message_is_received_in_a_topic_subscription_(peek-lock).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.When_a_message_is_received_in_invoice_poll_starter_queue_(peek-lock).recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.When_a_message_is_received_in_invoice_poll_starter_queue_(peek-lock).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* (3)        | Put-as-patch          |

### \$.properties.definition.triggers.When_a_message_is_received_in_non_funded_invoice_poll_starter_queue_(peek-lock).recurrence.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.When_a_message_is_received_in_non_funded_invoice_poll_starter_queue_(peek-lock).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* (3)        | Put-as-patch          |

### \$.properties.definition.triggers.When_a_message_is_received_in_topic_subscription.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.When_one_or_more_messages_arrive_in_a_topic_(auto-complete).recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* (3)        | Put-as-patch          |

### \$.properties.definition.triggers.addBlob.recurrence.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.definition.triggers.manual.kind

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-06-01  | Unknown             | Put-as-patch                                          |
| 2017-07-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.definition.triggers.manual.type

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-02-01-preview | Unknown             | Put-as-patch                                          |
| 2016-06-01         | Unknown             | Put-as-patch                                          |
| 2017-07-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01         | Unknown             | Put-as-patch                                          |

### \$.properties.definition.triggers.recurrence.type

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-06-01  | Unknown             | Put-as-patch                                          |
| 2017-07-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.endpointsConfiguration

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2015-02-01-preview | Unknown             | Put-as-patch                                                  |
| 2015-08-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-06-01)         |
| 2016-06-01         | Unknown             | Put-as-patch                                                  |
| 2016-10-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-07-01-preview) |
| 2017-07-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-07-01-preview) |
| 2018-07-01-preview | Unknown             | Put-as-patch                                                  |
| 2019-05-01         | Unknown             | Put-as-patch                                                  |

### \$.properties.endpointsConfiguration.connector.outgoingIpAddresses[*].address

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.endpointsConfiguration.workflow.accessEndpointIpAddresses[*].address

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.endpointsConfiguration.workflow.outgoingIpAddresses[*].address

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.integrationServiceEnvironment.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2016-10-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.integrationServiceEnvironment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2016-10-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$TixClientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$TixUsrPwd

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$appConnections

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.FaciliaConnector.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.GandalfApiConnector.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.apolloerrorsb.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.apollosb.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.azureblob.id

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-06-01  | Unknown             | Put-as-patch                                          |
| 2017-07-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.parameters.$connections.value.azuredatafactory.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.azureeventgridpublisher.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.azureeventgridsubscriber.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.azurefile.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.azurequeues.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.azuretable.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.azuretables.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.commonDataservice.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.commondataservice.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.documentdb.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.dynamicsAx.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.dynamicsax.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.dynamicscrmonline.connectionId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.excelonlinebusiness.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.filesystem.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.office365.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.servicebus.connectionId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.servicebus.connectionName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.servicebus.id

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2017-07-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.parameters.$connections.value.sftp.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.sftpwithssh.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$connections.value.sharepointonline.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.smtp.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.sql.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.$connections.value.x12.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$logicAppSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$passwords

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$portalAppHost.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$syncAdvertisements.value.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$uri.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.$webAppHost.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.1isTelemetrySourceV4Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.1isTelemetrySourceV4Url.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ANTAI_certificate_password

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ANTAI_key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.APExchangeProtocolAS2V4Url.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.APIM.ClientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.APIMSubscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.AS2EncodeAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.AppClientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.AzureSqlServer

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.BTSAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.BisNodeLoginPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.BisNodeLoginUserName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ClientAuthPFXPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ClientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ClientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ClientSecretParam

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.CoinsEnvironment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.CoinsHostName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.CoinsUserId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.CoinsUserPassword.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.CoinsUserPassword.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.CopPriceDiscExecData_StorageAccountKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.CoreDbConnection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.CreateEmailBodyFunctionUri.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.CreateReportFunctionUri.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.Dynamics365_ClientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.Dynamics365_Secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.EisMessagePublisherV3Url.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ErrorNotificationEmail.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.FileShareAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.Function.ClientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

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
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.HttpWithAadAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ImportDbConnection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.KeyVaultName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.LappAPIPwd

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.LappAPIUsr

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.NewAPPRecordWebHookURL.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

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

### \$.properties.parameters.PADebatchBadMessagesV4Url.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.PADebatchGeneratedAcksV4Url.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.PADebatchGoodMessagesV4Url.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.PADebatchReceivedAcksV4Url.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.Password

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

### \$.properties.parameters.SALESFORCE_QUERY_FUNCTION_API_KEY

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.SALESFORCE_UPDATE_FUNCTION_API_KEY

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ServiceHealthRouterV2Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ServiceHealthRouterV4Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.SftpFileAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.SoapSyncHttpAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.SqlServerPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.SqlServerUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.SubscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.SystemFileReadAdapterProcessorV4Name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.TixApiClientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.TixApiUsrPwd

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.WashingtonCustomAdapterV3Url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.X-Plex-Connect-Api-Key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.api-wattsight-clientid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.api-wattsight-clientsecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.apiKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.api_key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.apiappclientid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.apiappsecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.apimSubscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.apimSubscriptionKeyValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.apisubscriptionkey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.appSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.armTemplate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.azureAdGraphApiClientSecret.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.azureStorageConnectionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.azure_search_api_key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.azureiPaaSAPIGwyAPIKey.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.blobDeleteUrlKeyVaultReference

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.bradyPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.cdn_log_credential

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.clientId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-06-01  | Unknown             | Put-as-patch                                          |
| 2017-07-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.parameters.clientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.clientTenant

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.client_secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.clientid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.clientsecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.composeCartLinesUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.composeCartLinesUrl.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.createBomJournalUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.custom_auth_key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.d365Secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.d365secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.dhlFusion_workingDirectory.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.dynamicsOAuthBody

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.enable_encryption.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.endpointPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.endpointUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.filesystem_1_password.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.filesystem_1_username.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.graphql_client_secret.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.httpDataSourcePass

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.hub_client_id.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.hub_client_secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.initializerUrlKeyVaultReference

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.invictusPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.iserver365_client_id.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.logicAppGeneralAccessKeySecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.netivePassword.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.netiveUsername.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.oAuthPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.oAuthUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ocpApimSubscriptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.ocpapimsubscriptionkey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.orbusbi_url.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.providernumber_querystring.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.pwd_ohi.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.pwd_ohi.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.queue_name.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.resource

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.salesforcePassword.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.salesforceSecurityToken.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.salesforceUsername.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.secret

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2017-07-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.parameters.sendOmToSapLogicAppUrl.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.serviceBusConnectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.severaClientId.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.state_querystring.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.subfolder.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.suburb_querystring.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.surname_querystring.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.templateParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.transaction_function_authorization_code.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.transaction_function_uri.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.transaction_pipeline_eod_authorization_code.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.transaction_pipeline_sale_authorization_code.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.user_ohi.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.user_ohi.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.webhookUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.worktribeAlertEmailSubject.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.worktribeAlertEmailTo.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.youforceApiClientId.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.parameters.youforceApiClientSecret.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Put-as-patch          |

### \$.properties.runtimeConfiguration.lifetime.unit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.state

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-02-01-preview | Unknown             | Put-as-patch                                          |
| 2016-06-01         | Unknown             | Put-as-patch                                          |
| 2017-07-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01         | Unknown             | Put-as-patch                                          |

### \$.tags

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-06-01  | Unknown             | Put-as-patch                                          |
| 2016-10-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2017-07-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01  | Unknown             | Put-as-patch                                          |

### \$.tags.*

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-08-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-06-01) |
| 2016-06-01         | Unknown             | Put-as-patch                                          |
| 2016-10-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2017-07-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-05-01) |
| 2019-05-01         | Unknown             | Put-as-patch                                          |
