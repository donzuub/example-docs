# Data Dictionary for Collection: PatientTransactions
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| officeId | str | |
| events | list | |
| createTimestamp | DatetimeWithNanoseconds | |
| id | str | |
| patientId | str | |
| treatmentPlanId | str | |
| status | str | |
| refunds | list | |
| amount | int | |
| patientFullName | str | |
| document_id | str | |
| lastPlaceInFlow | str | |
| completeTimestamp | DatetimeWithNanoseconds | |
| purchaseId | int | |
| postTimestamp | DatetimeWithNanoseconds | |
| currentAmount | int | |

## Example Document
```json
{'officeId': '17003158', 'events': [{'type': 'Initialized', 'timestamp': DatetimeWithNanoseconds(2022, 4, 29, 18, 20, 54, 100000, tzinfo=datetime.timezone.utc), 'data': {'request': {'customerDetails': {'lastName': 'Toledano', 'firstName': 'Keren', 'dateOfBirth': '1987-01-28'}, 'location': '17003158', 'amount': 197, 'transactionId': '00f5f430-d72f-40d1-b654-b537a1b7695f'}, 'response': {'token': 'eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6IjMxNGY0MWQxMzY2ODJhNmUxOTg2ZDkxMjA1Y2IwM2E4In0.eyJhdXRob3JpdGllcyI6WyJST0xFX09OTElORV9DVVNUT01FUiJdLCJqdGkiOiI3MDkwMDg5OS01MGM3LTRjYjAtOTQzNy1kYWE0YTYyZTU1YjEiLCJzY29wZSI6WyJlcGF5Il0sImFkZGl0aW9uYWxQcm9wZXJ0aWVzIjp7ImNvbnRleHRJZCI6IjYzNjJhOWJhLTU0MDYtNGNmNC1iYjA1LWEzNmNhZmMxZGJiZiJ9LCJleHAiOjE2NTEyNTgyNTQsImlhdCI6MCwiY2xpZW50X2lkIjoiZXBheS1zZXJ2aWNlIn0.v6Zf_Gi6NCJvu1PBZf9J-76AlE6MP0inQV2l3SGmaoKVJgEm7-FMW4-LiNuf7M_6uDlD2sAQoq3SWVhevboQwx8fFlMmKINzYt8aNzyVckm2JpBfzYEh-TP10tMPNW72SVH7Fq668dP3Ttsfu-rU0TZAs2ptEnFAXhavHXlma1cu3Lt50fTadQkBXRSBZZXXF3uqFSZSCL9iU51xYoa36LE-1WveLD-qCxmLmRCMQO0fbbJ5r6juusUWBgaRGqcJhfcmMjAyuW5eXYQwYILGCPAkyxXQSM0ez0rJjKEKNsBxNbMAEzmyr5SehQ_qu8P5luv1t01_eyFs1oh-SzNOFQ'}}}, {'type': 'UserCancelled', 'timestamp': DatetimeWithNanoseconds(2022, 4, 29, 18, 30, 56, 658000, tzinfo=datetime.timezone.utc), 'data': {'purchaseId': None, 'type': 'USER_CANCEL'}}], 'createTimestamp': DatetimeWithNanoseconds(2022, 4, 29, 18, 20, 54, 100000, tzinfo=datetime.timezone.utc), 'id': '00f5f430-d72f-40d1-b654-b537a1b7695f', 'patientId': '120', 'treatmentPlanId': '168', 'status': 'UserCancelled', 'refunds': [], 'amount': 197, 'patientFullName': 'Keren Toledano', 'document_id': '00f5f430-d72f-40d1-b654-b537a1b7695f'}
```
