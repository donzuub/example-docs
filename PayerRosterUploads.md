# Data Dictionary for Collection: PayerRosterUploads
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| fileName | str | |
| id | str | |
| updateTime | DatetimeWithNanoseconds | |
| createTime | DatetimeWithNanoseconds | |
| payerId | str | |
| location | str | |
| status | str | |
| officeId | str | |
| document_id | str | |

## Example Document
```json
{'fileName': 'BRICK-TERM0123-1679908174.xls', 'id': '0DtYhl0SqHOu3ZuVZ2OU', 'updateTime': DatetimeWithNanoseconds(2023, 3, 27, 9, 9, 36, 576000, tzinfo=datetime.timezone.utc), 'createTime': DatetimeWithNanoseconds(2023, 3, 27, 9, 9, 34, 968000, tzinfo=datetime.timezone.utc), 'payerId': 'AETNA_DENTAL_PLANS', 'location': 'uploads/BRICK-TERM0123-1679908174.xls', 'status': 'Failed', 'officeId': '17003005', 'document_id': '0DtYhl0SqHOu3ZuVZ2OU'}
```
