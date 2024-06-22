# Data Dictionary for Collection: Unsubscribes
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| OfficeId | str | |
| Sms | dict | |
| PatientId | str | |
| Email | dict | |
| document_id | str | |

## Example Document
```json
{'OfficeId': '17003005', 'Sms': {'AutoOptOutDate': DatetimeWithNanoseconds(2021, 8, 11, 3, 28, 0, 685000, tzinfo=datetime.timezone.utc), 'Auto': True, 'AutoOptInDate': None, 'StandardOptInDate': None, 'Standard': False, 'StandardOptOutDate': None}, 'PatientId': '70', 'Email': {'AutoOptOutDate': None, 'Auto': False, 'AutoOptInDate': None, 'StandardOptInDate': None, 'Standard': False, 'StandardOptOutDate': None}, 'document_id': '0mJx1L26eZ0eaHhZqcGr'}
```
