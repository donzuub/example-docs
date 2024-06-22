# Data Dictionary for Collection: AppointmentRequests
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| Notes | str | |
| TreatmentPlanId | int | |
| Status | str | |
| Created | DatetimeWithNanoseconds | |
| ApptRequestedDate | str | |
| OfficeId | str | |
| TxValue | int | |
| PatientName | str | |
| ApptRequestedTime | str | |
| PatientId | str | |
| document_id | str | |
| StatusUpdated | str | |
| CallbackDate | str | |

## Example Document
```json
{'Notes': 'Thanks.', 'TreatmentPlanId': 2, 'Status': '', 'Created': DatetimeWithNanoseconds(2021, 10, 20, 20, 22, 30, 683000, tzinfo=datetime.timezone.utc), 'ApptRequestedDate': '10-22-2021', 'OfficeId': '17003005', 'TxValue': 4408, 'PatientName': 'Adam Jones', 'ApptRequestedTime': '8:00 AM', 'PatientId': '25', 'document_id': '0XTXNr1oWSPyppVDMkfP'}
```
