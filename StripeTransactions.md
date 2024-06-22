# Data Dictionary for Collection: StripeTransactions
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| patientFullName | str | |
| events | list | |
| createTimestamp | DatetimeWithNanoseconds | |
| status | str | |
| id | str | |
| source | str | |
| patientId | str | |
| invoicesId | list | |
| completeTimestamp | DatetimeWithNanoseconds | |
| refunds | list | |
| amount | int | |
| officeId | str | |
| document_id | str | |
| treatmentPlanId | int | |

## Example Document
```json
{'patientFullName': 'Jose Towers', 'events': [{'type': 'Initialized', 'timestamp': DatetimeWithNanoseconds(2022, 8, 16, 20, 52, 15, 75000, tzinfo=datetime.timezone.utc), 'data': {'response': {'clientSecret': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT_secret_urQGrcgA8hwQnc8XiEq87Mqkg', 'id': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT'}, 'payload': {'PartialPayment': False, 'InvoicesId': [1300237], 'Amount': 3514, 'PayAsCustomer': True, 'RememberPaymentInfo': False}}}, {'type': 'Completed', 'timestamp': DatetimeWithNanoseconds(2022, 8, 16, 20, 52, 20, 595000, tzinfo=datetime.timezone.utc), 'data': {'review': None, 'shipping': None, 'metadata': {'InvoicesId': '1300237', 'PatientId': '142', 'OfficeId': '17003005', 'Amount': '3514'}, 'payment_method_options': {'card': {'installments': None, 'mandate_options': None, 'network': None, 'request_three_d_secure': 'automatic'}}, 'object': 'payment_intent', 'setup_future_usage': None, 'amount_details': {'tip': {}}, 'status': 'succeeded', 'capture_method': 'automatic', 'next_action': None, 'cancellation_reason': None, 'customer': 'cus_KwisQ9ltJnW6bT', 'currency': 'usd', 'invoice': None, 'amount_capturable': 0, 'on_behalf_of': 'acct_1Jd4d8PZXvb9SveU', 'created': 1660683136, 'amount_received': 351400, 'charges': {'object': 'list', 'total_count': 1, 'has_more': False, 'url': '/v1/charges?payment_intent=pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'data': [{'review': None, 'shipping': None, 'receipt_number': None, 'metadata': {'InvoicesId': '1300237', 'PatientId': '142', 'OfficeId': '17003005', 'Amount': '3514'}, 'failure_message': None, 'object': 'charge', 'outcome': {'risk_score': 58, 'network_status': 'approved_by_network', 'type': 'authorized', 'risk_level': 'normal', 'seller_message': 'Payment complete.', 'reason': None}, 'status': 'succeeded', 'application_fee': 'fee_1LXWkHPZXvb9SveUrigr5QIK', 'dispute': None, 'currency': 'usd', 'customer': 'cus_KwisQ9ltJnW6bT', 'destination': 'acct_1Jd4d8PZXvb9SveU', 'refunded': False, 'invoice': None, 'created': 1660683136, 'on_behalf_of': 'acct_1Jd4d8PZXvb9SveU', 'amount_refunded': 0, 'disputed': False, 'fraud_details': {}, 'paid': True, 'description': None, 'source_transfer': None, 'application_fee_amount': 10221, 'id': 'ch_3LXWkGBMDq1CfeLP1msFzCzf', 'failure_code': None, 'receipt_email': 'jose@zuub.com', 'captured': True, 'payment_intent': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'order': None, 'billing_details': {'address': {'line2': None, 'line1': None, 'state': None, 'city': None, 'postal_code': None, 'country': None}, 'email': None, 'phone': None, 'name': 'Jose Towers'}, 'receipt_url': 'https://pay.stripe.com/receipts/payment/CAcaFwoVYWNjdF8xRWlTbndCTURxMUNmZUxQKIOH8JcGMgbyxW8d74s6LBZDRkL7FdYpOriFgQQ53Trs_A2tWBT11omVoUor9wEzm_7UFbwSQ5WfKatn', 'balance_transaction': 'txn_3LXWkGBMDq1CfeLP1aeGb6yT', 'refunds': {'object': 'list', 'total_count': 0, 'has_more': False, 'url': '/v1/charges/ch_3LXWkGBMDq1CfeLP1msFzCzf/refunds', 'data': []}, 'amount': 351400, 'transfer_group': 'group_pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'livemode': False, 'statement_descriptor_suffix': None, 'transfer': 'tr_3LXWkGBMDq1CfeLP1z2vD84D', 'amount_captured': 351400, 'calculated_statement_descriptor': 'WWW.ZUUB.COM', 'source': None, 'transfer_data': {'destination': 'acct_1Jd4d8PZXvb9SveU', 'amount': None}, 'payment_method': 'pm_1KK9nvBMDq1CfeLPRyAluTXg', 'failure_balance_transaction': None, 'payment_method_details': {'type': 'card', 'card': {'last4': '4242', 'three_d_secure': None, 'mandate': None, 'exp_month': 1, 'funding': 'credit', 'wallet': None, 'network': 'visa', 'country': 'US', 'exp_year': 2023, 'installments': None, 'brand': 'visa', 'fingerprint': 'J0tUZqRxPXcgl545', 'checks': {'address_line1_check': None, 'address_postal_code_check': None, 'cvc_check': None}}}, 'statement_descriptor': None, 'application': None}]}, 'description': None, 'application_fee_amount': 10221, 'id': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'automatic_payment_methods': None, 'last_payment_error': None, 'receipt_email': 'jose@zuub.com', 'transfer_group': 'group_pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'amount': 351400, 'payment_method_types': ['card'], 'livemode': False, 'statement_descriptor_suffix': None, 'client_secret': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT_secret_urQGrcgA8hwQnc8XiEq87Mqkg', 'transfer_data': {'destination': 'acct_1Jd4d8PZXvb9SveU'}, 'statement_descriptor': None, 'source': None, 'processing': None, 'payment_method': 'pm_1KK9nvBMDq1CfeLPRyAluTXg', 'canceled_at': None, 'confirmation_method': 'automatic', 'application': None}}, {'type': 'Completed', 'timestamp': DatetimeWithNanoseconds(2022, 8, 16, 20, 52, 35, 379000, tzinfo=datetime.timezone.utc), 'data': {'review': None, 'application': None, 'metadata': {'InvoicesId': '1300237', 'Amount': '3514', 'OfficeId': '17003005', 'PatientId': '142'}, 'payment_method_options': {'card': {'installments': None, 'mandate_options': None, 'request_three_d_secure': 'automatic', 'network': None}}, 'object': 'payment_intent', 'setup_future_usage': None, 'amount_details': {'tip': {}}, 'status': 'succeeded', 'capture_method': 'automatic', 'next_action': None, 'cancellation_reason': None, 'customer': 'cus_KwisQ9ltJnW6bT', 'currency': 'usd', 'invoice': None, 'created': 1660683136, 'charges': {'object': 'list', 'total_count': 1, 'has_more': False, 'url': '/v1/charges?payment_intent=pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'data': [{'review': None, 'receipt_number': None, 'shipping': None, 'metadata': {'InvoicesId': '1300237', 'OfficeId': '17003005', 'PatientId': '142', 'Amount': '3514'}, 'failure_message': None, 'object': 'charge', 'outcome': {'risk_score': 58, 'network_status': 'approved_by_network', 'type': 'authorized', 'risk_level': 'normal', 'seller_message': 'Payment complete.', 'reason': None}, 'status': 'succeeded', 'application_fee': 'fee_1LXWkHPZXvb9SveUrigr5QIK', 'dispute': None, 'refunded': False, 'customer': 'cus_KwisQ9ltJnW6bT', 'destination': 'acct_1Jd4d8PZXvb9SveU', 'currency': 'usd', 'invoice': None, 'created': 1660683136, 'order': None, 'on_behalf_of': 'acct_1Jd4d8PZXvb9SveU', 'disputed': False, 'fraud_details': {}, 'paid': True, 'billing_details': {'address': {'line2': None, 'line1': None, 'state': None, 'city': None, 'postal_code': None, 'country': None}, 'email': None, 'phone': None, 'name': 'Jose Towers'}, 'source_transfer': None, 'receipt_email': 'jose@zuub.com', 'id': 'ch_3LXWkGBMDq1CfeLP1msFzCzf', 'failure_code': None, 'amount_refunded': 0, 'captured': True, 'payment_intent': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'description': None, 'application_fee_amount': 10221, 'receipt_url': 'https://pay.stripe.com/receipts/payment/CAcaFwoVYWNjdF8xRWlTbndCTURxMUNmZUxQKIOH8JcGMgbyxW8d74s6LBZDRkL7FdYpOriFgQQ53Trs_A2tWBT11omVoUor9wEzm_7UFbwSQ5WfKatn', 'balance_transaction': 'txn_3LXWkGBMDq1CfeLP1aeGb6yT', 'transfer_group': 'group_pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'amount': 351400, 'refunds': {'object': 'list', 'total_count': 0, 'has_more': False, 'url': '/v1/charges/ch_3LXWkGBMDq1CfeLP1msFzCzf/refunds', 'data': []}, 'livemode': False, 'statement_descriptor_suffix': None, 'transfer': 'tr_3LXWkGBMDq1CfeLP1z2vD84D', 'transfer_data': {'destination': 'acct_1Jd4d8PZXvb9SveU', 'amount': None}, 'calculated_statement_descriptor': 'WWW.ZUUB.COM', 'source': None, 'statement_descriptor': None, 'payment_method_details': {'type': 'card', 'card': {'last4': '4242', 'three_d_secure': None, 'mandate': None, 'exp_month': 1, 'funding': 'credit', 'wallet': None, 'network': 'visa', 'country': 'US', 'exp_year': 2023, 'installments': None, 'brand': 'visa', 'fingerprint': 'J0tUZqRxPXcgl545', 'checks': {'address_line1_check': None, 'address_postal_code_check': None, 'cvc_check': None}}}, 'failure_balance_transaction': None, 'payment_method': 'pm_1KK9nvBMDq1CfeLPRyAluTXg', 'amount_captured': 351400, 'application': None}]}, 'on_behalf_of': 'acct_1Jd4d8PZXvb9SveU', 'amount_received': 351400, 'amount_capturable': 0, 'description': None, 'receipt_email': 'jose@zuub.com', 'id': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'last_payment_error': None, 'automatic_payment_methods': None, 'application_fee_amount': 10221, 'transfer_group': 'group_pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'amount': 351400, 'payment_method_types': ['card'], 'livemode': False, 'statement_descriptor_suffix': None, 'client_secret': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT_secret_urQGrcgA8hwQnc8XiEq87Mqkg', 'source': None, 'transfer_data': {'destination': 'acct_1Jd4d8PZXvb9SveU'}, 'statement_descriptor': None, 'processing': None, 'payment_method': 'pm_1KK9nvBMDq1CfeLPRyAluTXg', 'canceled_at': None, 'confirmation_method': 'automatic', 'shipping': None}}, {'type': 'Completed', 'timestamp': DatetimeWithNanoseconds(2022, 8, 16, 21, 52, 29, 980000, tzinfo=datetime.timezone.utc), 'data': {'review': None, 'shipping': None, 'metadata': {'InvoicesId': '1300237', 'Amount': '3514', 'PatientId': '142', 'OfficeId': '17003005'}, 'payment_method_options': {'card': {'installments': None, 'mandate_options': None, 'network': None, 'request_three_d_secure': 'automatic'}}, 'object': 'payment_intent', 'setup_future_usage': None, 'amount_details': {'tip': {}}, 'status': 'succeeded', 'capture_method': 'automatic', 'next_action': None, 'currency': 'usd', 'customer': 'cus_KwisQ9ltJnW6bT', 'cancellation_reason': None, 'invoice': None, 'amount_capturable': 0, 'on_behalf_of': 'acct_1Jd4d8PZXvb9SveU', 'created': 1660683136, 'amount_received': 351400, 'charges': {'object': 'list', 'total_count': 1, 'has_more': False, 'url': '/v1/charges?payment_intent=pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'data': [{'receipt_number': None, 'application': None, 'review': None, 'metadata': {'InvoicesId': '1300237', 'OfficeId': '17003005', 'Amount': '3514', 'PatientId': '142'}, 'failure_message': None, 'outcome': {'risk_score': 58, 'network_status': 'approved_by_network', 'seller_message': 'Payment complete.', 'risk_level': 'normal', 'type': 'authorized', 'reason': None}, 'object': 'charge', 'status': 'succeeded', 'application_fee': 'fee_1LXWkHPZXvb9SveUrigr5QIK', 'dispute': None, 'currency': 'usd', 'customer': 'cus_KwisQ9ltJnW6bT', 'destination': 'acct_1Jd4d8PZXvb9SveU', 'refunded': False, 'invoice': None, 'created': 1660683136, 'order': None, 'on_behalf_of': 'acct_1Jd4d8PZXvb9SveU', 'disputed': False, 'fraud_details': {}, 'paid': True, 'billing_details': {'address': {'line2': None, 'line1': None, 'state': None, 'postal_code': None, 'city': None, 'country': None}, 'email': None, 'phone': None, 'name': 'Jose Towers'}, 'source_transfer': None, 'receipt_email': 'jose@zuub.com', 'id': 'ch_3LXWkGBMDq1CfeLP1msFzCzf', 'failure_code': None, 'description': None, 'captured': True, 'payment_intent': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'amount_refunded': 0, 'application_fee_amount': 10221, 'receipt_url': 'https://pay.stripe.com/receipts/payment/CAcaFwoVYWNjdF8xRWlTbndCTURxMUNmZUxQKIOH8JcGMgbyxW8d74s6LBZDRkL7FdYpOriFgQQ53Trs_A2tWBT11omVoUor9wEzm_7UFbwSQ5WfKatn', 'balance_transaction': 'txn_3LXWkGBMDq1CfeLP1aeGb6yT', 'transfer_group': 'group_pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'amount': 351400, 'refunds': {'has_more': False, 'total_count': 0, 'object': 'list', 'url': '/v1/charges/ch_3LXWkGBMDq1CfeLP1msFzCzf/refunds', 'data': []}, 'livemode': False, 'statement_descriptor_suffix': None, 'transfer': 'tr_3LXWkGBMDq1CfeLP1z2vD84D', 'amount_captured': 351400, 'calculated_statement_descriptor': 'WWW.ZUUB.COM', 'transfer_data': {'destination': 'acct_1Jd4d8PZXvb9SveU', 'amount': None}, 'source': None, 'payment_method_details': {'type': 'card', 'card': {'mandate': None, 'three_d_secure': None, 'checks': {'address_line1_check': None, 'address_postal_code_check': None, 'cvc_check': None}, 'exp_month': 1, 'last4': '4242', 'wallet': None, 'network': 'visa', 'exp_year': 2023, 'country': 'US', 'installments': None, 'brand': 'visa', 'fingerprint': 'J0tUZqRxPXcgl545', 'funding': 'credit'}}, 'failure_balance_transaction': None, 'payment_method': 'pm_1KK9nvBMDq1CfeLPRyAluTXg', 'statement_descriptor': None, 'shipping': None}]}, 'description': None, 'application_fee_amount': 10221, 'id': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'automatic_payment_methods': None, 'last_payment_error': None, 'receipt_email': 'jose@zuub.com', 'transfer_group': 'group_pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'amount': 351400, 'payment_method_types': ['card'], 'client_secret': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT_secret_urQGrcgA8hwQnc8XiEq87Mqkg', 'statement_descriptor_suffix': None, 'livemode': False, 'source': None, 'statement_descriptor': None, 'transfer_data': {'destination': 'acct_1Jd4d8PZXvb9SveU'}, 'processing': None, 'payment_method': 'pm_1KK9nvBMDq1CfeLPRyAluTXg', 'canceled_at': None, 'confirmation_method': 'automatic', 'application': None}}], 'createTimestamp': DatetimeWithNanoseconds(2022, 8, 16, 20, 52, 15, 75000, tzinfo=datetime.timezone.utc), 'status': 'Completed', 'id': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT', 'source': 'Invoice', 'patientId': '142', 'invoicesId': [1300237], 'completeTimestamp': DatetimeWithNanoseconds(2022, 8, 16, 21, 52, 29, 980000, tzinfo=datetime.timezone.utc), 'refunds': [], 'amount': 3514, 'officeId': '17003005', 'document_id': 'pi_3LXWkGBMDq1CfeLP1w5EQ4qT'}
```