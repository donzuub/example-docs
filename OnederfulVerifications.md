# Data Dictionary for Collection: OnederfulVerifications
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| PatientDocRef | DocumentReference | |
| Month | int | |
| OfficeId | str | |
| Count | int | |
| document_id | str | |
| Success | bool | |
| Provider | str | |
| PayerId | str | |
| VerifiedOnDate | DatetimeWithNanoseconds | |

## Example Document
```json
{'PatientDocRef': <google.cloud.firestore_v1.document.DocumentReference object at 0x00000252B5F74920>, 'Month': 10, 'OfficeId': '17003433', 'Count': 1, 'document_id': '002k5j6wOUhuSAakCQiw'}
```
