# Data Dictionary for Collection: PaymentAgreementDocuments
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| officeId | str | |
| content | str | |
| type | str | |
| updateTime | DatetimeWithNanoseconds | |
| contentType | str | |
| createTime | DatetimeWithNanoseconds | |
| name | str | |
| document_id | str | |

## Example Document
```json
{'officeId': '17005176', 'content': '<p>By enrolling in this payment arrangement, I authorize Advanced DDS to charge the debit/credit card for the amount and terms as indicated above. I agree to promptly update Advanced DDS before my next payment is due if there are any changes to the card on file, including but not limited to: card decline, insufficient funds, card expiration, account closure, card replacement, etc. I authorize Advanced DDS to contact me regarding any failed payment, and understand that failure to make a monthly payment as scheduled may result in my account being turned over to an attorney or agency for collection and additional legal fees may apply.</p>', 'type': 'default', 'updateTime': DatetimeWithNanoseconds(2023, 5, 4, 23, 30, 10, 356000, tzinfo=datetime.timezone.utc), 'contentType': 'text/html', 'createTime': DatetimeWithNanoseconds(2023, 5, 4, 23, 30, 10, 356000, tzinfo=datetime.timezone.utc), 'name': 'default', 'document_id': 'QpBLf1K7vmBtikuG2uvj'}
```
