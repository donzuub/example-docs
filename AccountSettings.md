# Data Dictionary for Collection: AccountSettings
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| Sunbit | dict | |
| OfficeId | str | |
| document_id | str | |
| searchPatientsInAllOffices | bool | |
| SharedDataOfficeId | str | |
| InsuranceVerifySettings | dict | |
| inactiveInsuranceVerificationOverrides | dict | |
| SaveVerificationHistory | bool | |
| PayerVerificationSettings | dict | |
| treatmentPlanPriorities | dict | |
| ApptReminderSettings | dict | |
| GlobalPaymentsSettings | dict | |
| authenticationPhoneNumber | str | |
| showAllProvidersInAllOffices | bool | |

## Example Document
```json
{'Sunbit': {'minimumPatientBalance': 0, 'responses': {'webhook': [{'payload': {'statusReason': 'NONE', 'location': '17003161', 'url': 'https://merchant-onboarding-demo.sunbit.com/GDwsLqnz'}, 'eventType': 'MERCHANT_CREATED'}, {'payload': {'statusReason': 'NONE', 'location': '17003161', 'url': 'https://merchant-onboarding-demo.sunbit.com/GDwsLqnz'}, 'eventType': 'MERCHANT_LOCATION_DETAILS_ADDED'}, {'payload': {'statusReason': 'NONE', 'location': '17003161', 'url': 'https://merchant-onboarding-demo.sunbit.com/GDwsLqnz'}, 'eventType': 'MERCHANT_CONTACT_DETAILS_ADDED'}, {'payload': {'statusReason': 'NONE', 'location': '17003161', 'url': 'https://merchant-onboarding-demo.sunbit.com/GDwsLqnz'}, 'eventType': 'MERCHANT_LEGAL_INFORMATION_ADDED'}, {'payload': {'statusReason': 'NONE', 'location': '17003161', 'url': 'https://merchant-onboarding-demo.sunbit.com/GDwsLqnz'}, 'eventType': 'MERCHANT_CONTACT_DETAILS_ADDED'}, {'payload': {'statusReason': 'NONE', 'location': '17003161', 'url': 'https://merchant-onboarding-demo.sunbit.com/GDwsLqnz'}, 'eventType': 'MERCHANT_LEGAL_INFORMATION_ADDED'}, {'payload': {'statusReason': 'NONE', 'location': '17003161', 'url': 'https://merchant-onboarding-demo.sunbit.com/GDwsLqnz'}, 'eventType': 'MERCHANT_BANK_INFORMATION_ADDED'}, {'payload': {'statusReason': 'NONE', 'location': '17003161', 'url': 'https://merchant-onboarding-demo.sunbit.com/GDwsLqnz'}, 'eventType': 'MERCHANT_ACTIVATED'}], 'onboarding': [{'status': 'CREATED', 'location': '17003161', 'url': 'https://merchant-onboarding-demo.sunbit.com/GDwsLqnz', 'creationDate': DatetimeWithNanoseconds(2022, 5, 6, 0, 0, tzinfo=datetime.timezone.utc)}]}, 'showFinancingOnTreatmentPlans': True, 'notificationEmail': [], 'showForAllProcedures': True, 'patientTypes': ['insured', 'discountplan', 'cash'], 'applyToAllInvoices': True, 'procedureCodes': [], 'applyToAllTreatmentPlans': True, 'showFinancingOnInvoices': True, 'status': 'Linked'}, 'OfficeId': '17003161', 'document_id': '0BV62tCKDvcdyuoFdAJm'}
```
