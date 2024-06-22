# Data Dictionary for Collection: SmsHistory
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| OfficeId | str | |
| UnreadCount | int | |
| Active | bool | |
| Birthdate | str | |
| PatientPhone | str | |
| LastModifiedDate | DatetimeWithNanoseconds | |
| LastMessage | str | |
| LastName | str | |
| FirstName | str | |
| PatientId | str | |
| Favorite | bool | |
| Email | str | |
| document_id | str | |
| Consented | bool | |
| Unread | bool | |
| SmsConsentInfo | dict | |

## Example Document
```json
{'OfficeId': '17003174', 'UnreadCount': 0, 'Active': False, 'Birthdate': '10/10/1980', 'PatientPhone': '6262009760', 'LastModifiedDate': DatetimeWithNanoseconds(2023, 1, 31, 1, 11, 32, 436000, tzinfo=datetime.timezone.utc), 'LastMessage': None, 'LastName': 'Johnson', 'FirstName': 'Don', 'PatientId': '376', 'Favorite': False, 'Email': 'donj@zuub.com', 'document_id': '06kSiK1kY0PsemyvWL5F'}
```
