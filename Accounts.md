# Data Dictionary for Collection: Accounts
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| PrimaryEmail | str | |
| Products | list | |
| LatLng | dict | |
| Discount | dict | |
| StatusId | DocumentReference | |
| Name | str | |
| AutoNotify | bool | |
| DataInitialized | bool | |
| PmsConnectorId | str | |
| FinanceOptions | list | |
| Business | dict | |
| AccountNumber | int | |
| PMS | str | |
| Primary | DocumentReference | |
| Users | list | |
| AutoNotifySettings | dict | |
| TreatmentPlanStatus | dict | |
| InsurancePays | bool | |
| SmsEnabled | bool | |
| PmsVersion | str | |
| document_id | str | |
| EncryptKey | str | |
| DefaultVisitPhase | int | |
| ShowVisitPhase | bool | |
| InsuranceVerifySettings | dict | |
| ConsentEmail | str | |
| ShowFeesAndInsurance | bool | |
| ApptScheduleSettings | dict | |
| TxSettingsUpdateDate | DatetimeWithNanoseconds | |
| UpdaterServiceVersion | str | |
| BandwidthNumber | str | |
| ShowConsent | bool | |
| Timezone | str | |
| NotificationsEmailAddress | str | |
| ServiceVersion | str | |
| LatestTpRunning | bool | |
| ApptTpSendInterval | int | |
| Country | str | |
| ApptStatus | dict | |
| Email | str | |
| UseOfficeNameForTx | bool | |
| reminders | dict | |
| TreatmentPlanVisible | list | |
| SaveVerificationHistory | bool | |
| OfficeLogo | str | |

## Example Document
```json
{'PrimaryEmail': 'zuubtester+dx1@gmail.com', 'Products': [<google.cloud.firestore_v1.document.DocumentReference object at 0x00000252B6ACD160>, <google.cloud.firestore_v1.document.DocumentReference object at 0x00000252B6ACD3A0>], 'LatLng': {'Lng': '-73.42391429999999', 'Lat': '41.0924881'}, 'Discount': {'CustomDiscount': 0, 'Enabled': False, 'Value': 0}, 'StatusId': <google.cloud.firestore_v1.document.DocumentReference object at 0x00000252B6ACD2B0>, 'Name': '***TEST DATABASE***  Dr. Dental of Norwalk, PC', 'AutoNotify': False, 'DataInitialized': False, 'PmsConnectorId': '17003064', 'FinanceOptions': [], 'Business': {'Address2': '', 'Zipcode': '06854', 'Phone': '8188500452', 'State': 'CT', 'City': 'Norwalk', 'Address1': '360 Connecticut Ave.', 'Name': '***TEST DATABASE***  Dr. Dental of Norwalk, PC'}, 'AccountNumber': 17003064, 'PMS': 'DentrixEnterprise', 'Primary': <google.cloud.firestore_v1.document.DocumentReference object at 0x00000252B6ACC1A0>, 'Users': [<google.cloud.firestore_v1.document.DocumentReference object at 0x00000252B6ACC140>, <google.cloud.firestore_v1.document.DocumentReference object at 0x00000252B6ACD310>], 'AutoNotifySettings': {'SendLatestTp': True, 'NonInsuredOnly': False}, 'TreatmentPlanStatus': {'Incomplete': ['Treatment Planned'], 'Completed': ['Completed']}, 'InsurancePays': True, 'SmsEnabled': True, 'PmsVersion': '11.0.20.921', 'document_id': '098LeUpMEUSzK5r6L7UF'}
```
