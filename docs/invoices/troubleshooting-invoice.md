Troubleshooting
You can troubleshoot the issues that you could face for invoices in Zoho Books.

Online Payments
Online Payments
When your customers try to make online payments to you from the Customer Portal, they may encounter errors in certain cases. Let us take a look at some of the error codes that could show up, what they mean and what you can do to resolve them.

Error Code What went wrong? What can you do?
CP1003 The link generated may have been associated to a deleted customer. Verify that the associated customer still exists.
CP3001 The merchant account is not enabled for reference transactions. Hence, payment could not be processed. Enable reference transactions in your merchant account.
CP3002 The gateway has been configured with invalid credentials or some change has been done on the merchant account which leads to invalid configurations. Re-enter the correct credentials by going to Settings > Integrations.
CP3003 The payment has been declined due to the fraud detection filters set up in your merchant account. Verify if the transaction was fraudulent or not. Moderate your fraud filters, if necessary.
CP3004 The transaction has been declined as the payment gateway couldn’t verify the address of the customer. Enable the address fields for your payment gateway from Settings > Integrations > Card Verification Settings.
CP3005 A new transaction request has been submitted within a few minutes of the previous request with similar information (such as the amount and credit card/bank account), but for different invoices. Make sure there is some time gap between the two transactions.
CP4001 The transaction amount is less than the minimum amount allowed by the payment gateway. This may be due to the discounts or credits applied. Make sure that the transaction amount is greater than the minimum transaction amount.
CP4003 The payment gateways that you’ve configured don’t support the transaction currency. Configure a payment gateway which supports the transaction currency.
