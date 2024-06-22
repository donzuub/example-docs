# Data Dictionary for Collection: DelayLoginStatusUpdates
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| target | str | |
| duration | int | |
| threshold | int | |
| createTime | DatetimeWithNanoseconds | |
| botId | str | |
| document_id | str | |

## Example Document
```json
{'target': 'DelayLogin', 'duration': 1000, 'threshold': 100, 'createTime': DatetimeWithNanoseconds(2024, 4, 10, 22, 51, 55, 52000, tzinfo=datetime.timezone.utc), 'botId': 'cigna-data', 'document_id': '0PXtBplTwIDw6o3MgkLF'}
```
