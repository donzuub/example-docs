# Data Dictionary for Collection: PatientPreQualifications
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| validUntilTimestamp | DatetimeWithNanoseconds | |
| events | list | |
| createTimestamp | DatetimeWithNanoseconds | |
| id | str | |
| url | str | |
| patientId | str | |
| status | str | |
| completeTimestamp | DatetimeWithNanoseconds | |
| officeId | str | |
| document_id | str | |
| approveTimestamp | DatetimeWithNanoseconds | |

## Example Document
```json
{'validUntilTimestamp': DatetimeWithNanoseconds(2022, 6, 3, 0, 0, tzinfo=datetime.timezone.utc), 'events': [{'type': 'Initialized', 'timestamp': DatetimeWithNanoseconds(2022, 5, 6, 22, 37, 58, 315000, tzinfo=datetime.timezone.utc), 'data': {'referral': '03321e16-3feb-4587-a90b-fc86797c0a29', 'sendSMS': False, 'customerDetails': {'lastName': 'Jones', 'firstName': 'Adam', 'dateOfBirth': '1980-06-01', 'phone': '3109104989', 'email': 'sales@zuub.com'}, 'location': '17003161', 'customerPhoneNumber': '3109104989'}}, {'type': 'Completed', 'timestamp': DatetimeWithNanoseconds(2022, 5, 6, 22, 40, 39, 327000, tzinfo=datetime.timezone.utc), 'data': {'payload': {'validUntil': DatetimeWithNanoseconds(2022, 6, 3, 0, 0, tzinfo=datetime.timezone.utc), 'referral': '03321e16-3feb-4587-a90b-fc86797c0a29', 'purchaseId': '99-775-187', 'approvalAmount': '2290.0', 'location': '17003161', 'purchaseAmountEntered': '1553.0'}, 'eventType': 'PREQUAL_COMPLETED'}}], 'createTimestamp': DatetimeWithNanoseconds(2022, 5, 6, 22, 37, 58, 315000, tzinfo=datetime.timezone.utc), 'id': '03321e16-3feb-4587-a90b-fc86797c0a29', 'url': 'https://demo-apply.sunbit.com/SunbitTest-00q6', 'patientId': '25', 'status': 'Completed', 'completeTimestamp': DatetimeWithNanoseconds(2022, 5, 6, 22, 40, 39, 327000, tzinfo=datetime.timezone.utc), 'officeId': '17003161', 'document_id': '03321e16-3feb-4587-a90b-fc86797c0a29'}
```
