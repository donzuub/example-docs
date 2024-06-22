# Data Dictionary for Collection: AccountInboundSms
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| to | str | |
| description | str | |
| type | str | |
| createTime | DatetimeWithNanoseconds | |
| time | DatetimeWithNanoseconds | |
| message | dict | |
| document_id | str | |
| updateTime | DatetimeWithNanoseconds | |

## Example Document
```json
{'to': '+14242710652', 'description': 'Incoming message received', 'type': 'message-received', 'createTime': DatetimeWithNanoseconds(2024, 1, 5, 17, 21, 25, 906000, tzinfo=datetime.timezone.utc), 'time': DatetimeWithNanoseconds(2024, 1, 5, 17, 21, 25, 799000, tzinfo=datetime.timezone.utc), 'message': {'text': 'Guardian Life: Your one-time passcode is 853796. Msg&data rates may apply.', 'id': 'c977d82e-9084-409e-8c6e-546769e9ed5b', 'time': DatetimeWithNanoseconds(2024, 1, 5, 17, 21, 25, 623000, tzinfo=datetime.timezone.utc), 'applicationId': '2e702737-7a28-4264-98d3-53818841c31f', 'owner': '+14242710652', 'from': '32858', 'to': ['+14242710652'], 'direction': 'in', 'segmentCount': 1}, 'document_id': '016CCU9BD8LbNGUG4cEK'}
```
