# Data Dictionary for Collection: PreParsedTreatmentPlans
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| TreatmentPlan | dict | |
| ParsedDate | DatetimeWithNanoseconds | |
| PatientId | str | |
| OfficeId | str | |
| document_id | str | |

## Example Document
```json
{'TreatmentPlan': {'TreatmentPlans': None, 'DefaultConsentInfo': None, 'Created': '05/02/2023', 'PracticeId': 1, 'DefaultVisitPhase': 1, 'PatientGuid': '7zfyQvTYzhU76A1v4ZbW', 'EnableInsurance': True, 'ShowVisitPhase': True, 'OfficeId': '17003175', 'ShowInsurancePay': True, 'PatientId': '3903', 'ProviderId': 'VAVH', 'Adjustments': []}, 'ParsedDate': DatetimeWithNanoseconds(2023, 5, 2, 17, 33, 32, 751000, tzinfo=datetime.timezone.utc), 'PatientId': '3903', 'OfficeId': '17003175', 'document_id': '01T2bQXIFeswYKq9Mig2'}
```
