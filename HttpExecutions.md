# Data Dictionary for Collection: HttpExecutions
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| messageId | str | |
| responses | list | |
| method | str | |
| url | str | |
| messageTimestamp | str | |
| limit | int | |
| correlationId | str | |
| attempt | int | |
| status | str | |
| current | int | |
| createTime | DatetimeWithNanoseconds | |
| document_id | str | |
| updateTime | DatetimeWithNanoseconds | |
| retryCount | int | |

## Example Document
```json
{'messageId': '11459636501067252', 'responses': [{'body': '"Success"', 'headers': {'x-amzn-requestid': '7b7cedb1-e013-4064-aa0d-bec35646e818', 'date': 'Mon, 10 Jun 2024 22:13:22 GMT', 'x-amz-apigw-id': 'ZLAUEGcYvHcFtnA=', 'x-amzn-trace-id': 'Root=1-66677a80-6866484a5e29b7eb567968bd;Parent=5a5b18ecd66c4c50;Sampled=0;lineage=9cfc0bd6:0|e086bac0:0', 'content-type': 'application/json', 'server': 'Server', 'content-length': '9', 'connection': 'close'}, 'statusCode': 200}], 'method': 'POST', 'url': 'https://eligibility-verification.tst.pdsconnect.com/TST/eligibility-verification', 'messageTimestamp': '2024-06-10T22:13:14.514Z', 'limit': 3, 'correlationId': 'd48430b2-9bc1-411c-ae95-dceeefaddb5b', 'attempt': 1, 'status': 'Succeeded', 'current': 1, 'createTime': DatetimeWithNanoseconds(2024, 6, 10, 22, 13, 22, 538000, tzinfo=datetime.timezone.utc), 'document_id': '00WI3rSxShSavFNv5d01'}
```
