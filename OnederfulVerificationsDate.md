# Data Dictionary for Collection: OnederfulVerificationsDate
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| Success | bool | |
| PayerId | str | |
| PatientDocRef | DocumentReference | |
| VerifiedOnDate | DatetimeWithNanoseconds | |
| OfficeId | str | |
| document_id | str | |
| Provider | str | |

## Example Document
```json
{'Success': True, 'PayerId': 'DD_GEORGIA', 'PatientDocRef': <google.cloud.firestore_v1.document.DocumentReference object at 0x00000252B5F99550>, 'VerifiedOnDate': DatetimeWithNanoseconds(2021, 5, 7, 3, 57, 0, 483000, tzinfo=datetime.timezone.utc), 'OfficeId': '17003005', 'document_id': '00IwNwiwSfIisryRa5sP'}
```
