# Data Dictionary for Collection: PayerRosterPatients
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| memberId | str | |
| lastName | str | |
| firstName | str | |
| id | str | |
| updateTime | DatetimeWithNanoseconds | |
| officeCopay | int | |
| status | str | |
| rowNumber | int | |
| effectiveDate | DatetimeWithNanoseconds | |
| birthDate | DatetimeWithNanoseconds | |
| standards | str | |
| originalJson | dict | |
| createTime | DatetimeWithNanoseconds | |
| uploadId | str | |
| document_id | str | |
| groupRenewalDate | DatetimeWithNanoseconds | |
| patientChargeSchedule | str | |
| groupName | str | |
| childAge | str | |
| planNumber | str | |
| orthodonticsCoverage | str | |
| coInsurance | str | |
| terminationDate | DatetimeWithNanoseconds | |

## Example Document
```json
{'memberId': '204148189', 'lastName': 'SOOY', 'firstName': 'DONNA J', 'id': '', 'updateTime': DatetimeWithNanoseconds(2023, 3, 31, 19, 56, 9, 598000, tzinfo=datetime.timezone.utc), 'officeCopay': 0, 'status': 'Active', 'rowNumber': 996, 'effectiveDate': DatetimeWithNanoseconds(2015, 1, 1, 0, 0, tzinfo=datetime.timezone.utc), 'birthDate': DatetimeWithNanoseconds(1950, 10, 21, 0, 0, tzinfo=datetime.timezone.utc), 'standards': '*', 'originalJson': {'G': 'E', 'M': '*', 'P': '$7.00 ', 'H': 'F', 'O': '0', 'I': '1/1/2015', 'F': 'N', 'J': '812311', 'A': 'S', 'D': 'DONNA J', 'C': 'SOOY', 'B': '204148189', 'N': '34C', 'K': 'N', 'S': '$8.26 ', 'R': '$1.26 ', 'Q': '$0.00 ', 'E': '10/21/1950'}, 'createTime': DatetimeWithNanoseconds(2023, 3, 31, 19, 56, 9, 598000, tzinfo=datetime.timezone.utc), 'uploadId': 'fhqzOJiXYYkk9xKFYqhU', 'document_id': '0016mZgBzth2NhCA8aaW'}
```
