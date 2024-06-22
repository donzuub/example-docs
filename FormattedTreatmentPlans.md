# Data Dictionary for Collection: FormattedTreatmentPlans
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| PatientId | str | |
| Created | DatetimeWithNanoseconds | |
| OfficeId | str | |
| FutureAppointment | NoneType | |
| Procedures | list | |
| document_id | str | |
| TreatmentPlanId | int | |
| LastSentDateTime | NoneType | |
| MiddleName | str | |

## Example Document
```json
{'PatientId': '248', 'Created': DatetimeWithNanoseconds(2022, 6, 14, 0, 0, tzinfo=datetime.timezone.utc), 'OfficeId': '17003172', 'FutureAppointment': '', 'Procedures': ['T3541'], 'document_id': '00IM6IzRFFMeDgyn5gza'}
```
