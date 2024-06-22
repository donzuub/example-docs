# Data Dictionary for Collection: InsuranceWritebacks
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| appointmentId | str | |
| isRetry | bool | |
| attempts | list | |
| eligibleAfter | DatetimeWithNanoseconds | |
| updateTime | str | |
| policy | dict | |
| createTime | str | |
| payerId | str | |
| status | str | |
| messages | list | |
| officeId | str | |
| document_id | str | |
| creationOfficeId | str | |
| patientId | str | |
| trigger | dict | |
| note | str | |
| appointmentOfficeId | str | |
| noteDate | str | |

## Example Document
```json
{'appointmentId': '4579', 'isRetry': False, 'attempts': [{'fields': {'PatientNote': {'primaryKey': 'AptNum=4579', 'message': None, 'fieldName': 'PatientNote', 'previous': None, 'status': 'Success', 'current': '11/21/2023 3:00 PM - Zuub verified Primary insurance: Status: Active, Maximum: $1,000.00, Remaining Maximum: $530.05, Deductible: Not Available, Remaining Deductible: Not Available', 'canRetry': False}, 'InsuranceUsed': {'primaryKey': None, 'message': None, 'fieldName': 'InsuranceUsed', 'previous': None, 'status': 'NoChange', 'current': None, 'canRetry': False}, 'LastEligibilityCheckDate': {'primaryKey': None, 'message': None, 'fieldName': 'LastEligibilityCheckDate', 'previous': '2023-11-21', 'status': 'NoChange', 'current': '2023-11-21', 'canRetry': False}, 'EligibilityEndDate': {'primaryKey': None, 'message': 'Missing value', 'fieldName': 'EligibilityEndDate', 'previous': None, 'status': 'NoChange', 'current': None, 'canRetry': False}, 'IsEligible': {'primaryKey': None, 'message': 'Missing value', 'fieldName': 'IsEligible', 'previous': None, 'status': 'NoChange', 'current': None, 'canRetry': False}, 'AnnualIndividualDeductibleStandard': {'primaryKey': None, 'message': 'No value(s) found', 'fieldName': 'AnnualIndividualDeductibleStandard', 'previous': None, 'status': 'NoChange', 'current': None, 'canRetry': False}, 'EligibilityStartDate': {'primaryKey': None, 'message': 'Missing value', 'fieldName': 'EligibilityStartDate', 'previous': None, 'status': 'NoChange', 'current': None, 'canRetry': False}, 'DeductibleUsed': {'primaryKey': None, 'message': None, 'fieldName': 'DeductibleUsed', 'previous': None, 'status': 'NoChange', 'current': None, 'canRetry': False}, 'AnnualFamilyDeductibleStandard': {'primaryKey': None, 'message': 'No value(s) found', 'fieldName': 'AnnualFamilyDeductibleStandard', 'previous': None, 'status': 'NoChange', 'current': None, 'canRetry': False}, 'IndividualMaximum': {'primaryKey': 'BenefitNum=5727', 'message': None, 'fieldName': 'IndividualMaximum', 'previous': '1000', 'status': 'NoChange', 'current': '1000', 'canRetry': False}}, 'attemptedAt': '2023-11-21T15:00:51.2923672-08:00', 'id': '000lYamtpMIlh9LSEnyo', 'pmsType': 'OpenDental', 'pmsVersion': '19.4.30.0'}], 'eligibleAfter': DatetimeWithNanoseconds(2023, 11, 21, 22, 58, 25, 898000, tzinfo=datetime.timezone.utc), 'updateTime': '2023-11-21T23:00:51.634Z', 'policy': {'benefitsUsage': {'insuranceUsed': 469.95, 'individualBenefitsApplied': 469.95}, 'patientId': '508', 'dateOfBirth': '12/17/1982', 'eligibility': {'isEligible': True, 'lastEligibilityCheckDate': '2023-11-21T22:58:25.274Z', 'planStartDate': '01/01/2021'}, 'isSecondaryInsurance': False, 'maximums': {'individual': 1000}, 'verificationId': 'tvoJY9SPUoBv4wRu6OSv'}, 'createTime': '2023-11-21T22:58:25.898Z', 'payerId': 'AETNA_DENTAL_PLANS', 'status': 'Success', 'messages': [], 'officeId': '17003005', 'document_id': '000lYamtpMIlh9LSEnyo'}
```
