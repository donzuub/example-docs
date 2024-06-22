# Data Dictionary for Collection: Configurations
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| retryLimit | int | |
| batchSize | int | |
| targetTopic | str | |
| document_id | str | |
| delta-dental-pdf-bot | dict | |
| dentalXChange | dict | |
| dentalXChangeEligibility | dict | |
| updatedTreatmentPlan | dict | |
| enhancedAdmin | dict | |
| accountLogin | dict | |
| minutesBeforeRetry | dict | |
| chargeRate | float | |
| transactionFee | int | |
| text | str | |
| botIds | list | |

## Example Document
```json
{'retryLimit': 1, 'batchSize': 100, 'targetTopic': 'projects/dev-zuub/topics/insurance-bot-runner-0001', 'document_id': 'bot-request-publish'}
```
