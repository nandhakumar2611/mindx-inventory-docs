Customer/Vendor Preferences
Let’s have a look at the various settings you can configure for the Customers/Vendors module in Zoho Books.

IN THIS PAGE
Basic Settings
Field Customisation
Custom Buttons & Links
Multi-currency Transactions for Each Contact
Enabling Multi-currency Transactions for Each Contact
Creating Transactions in Different Currencies
View Multi-currency Details of Customers and Vendors
Recording Payments Received or Made
Reports
Advanced Search
Basic Settings
You can choose which fields of your customer/vendor will be displayed in your transaction PDF, and also create multiple customers/vendors with similar details.

To configure your Customers/Vendors preferences:

Go to Settings on the top right corner of the page.
Select Customers and Vendors under Preferences.
Customers/Vendors Preferences
If you want to create multiple customers/vendors with the same Customer/Vendor Display Name, then check Allow duplicates for contact display name.
Enable the Customer Credit limit.
Click the Insert Placeholder drop-down button.
Select the fields that you want to display in your transaction PDF.
You can even remove the fields from placeholder box or add additional text in it.
Field Customization
You can add multiple custom fields for the Customers/Vendors module and assign different data types for each of them. Learn more about Field Customisation.

Custom Buttons & Links
You can create new buttons in the Customers/Vendors module to perform specific actions for your transactions, or to open external links. You can create them using deluge script and execute actions based on the functions you add. Learn more about Custom Buttons & Links.

Multi-currency Transactions for Each Contact
Zoho Books enables you to create transactions for your customers and vendors in different currencies. Let us understand how this works in Zoho Books with the help of a scenario.

Scenario: Rockvan, Inc. is an investment management corporation based in New York City. One of their clients, QP Banks, is a multinational conglomerate in different countries. Rockvan, Inc uses the Multi-currency Transactions for Each Contact feature in Zoho Books to invoice QP Banks based on the currency used in the country where they operate.

Note: This feature is available only for certain plans of Zoho Books. Visit the pricing page to check if it’s available in your current plan.

Note: Zoho Books fetches the exchange rates automatically for the foreign currency in real-time while you create transactions. These exchange rates are fetched from our third-party service provider Open Exchange Rates against the base currency of your organisation. However, suppose you want to enter the rates manually, disable exchange rate feeds first, and enter the exchange rates manually.

Enabling Multi-currency Transactions for Each Contact
Before enabling Multi-currency Transactions for Each Contact for customers and vendors, ensure that you update the credit limit in the base currency for all customers.

If you have created custom views, workflows, or webhooks using parameters such as receivables, payables, or unused credits, ensure that you edit the following for Customers and Vendors:

Custom Views: While updating the criteria, select Receivables BCY, Payables BCY, and Unused Credits BCY as the fields instead of Receivables, Payables, and Unused Credits.
Changing custom view criteria for multi-currency
Workflow Rule: While updating the triggers, select Receivables BCY and Payables BCY as the fields instead of Receivables and Payables.
Changing workflow trigger for multi-currency
Webhooks: While updating parameter values, select Receivables BCY and Payables BCY as the parameters instead of Receivables and Payables.
Changing the webhook entity parameters for multi-currency
You will have to enable Multi-currency Transactions for Each Contact to record transactions in different currencies.

Go to Settings on the top right corner of the page.
Select Customers and Vendors under Preferences.
Slide the toggle next to Multi-currency Transactions for Each Contact to Enabled.
Click Save.
Enable Multi-currency Transactions for Each Contact
Note: You cannot disable Multi-currency Transactions for Each Contact once you have created transactions in other currencies for your customers or vendors.

Creating Transactions in Different Currencies
Now that you have enabled Multi-currency Transactions for Each Contact, you can create transactions for your customers or vendors in other currencies.

Select the Sales or Purchases transaction you want to create.
Click the + New button in the top right corner of the transaction’s list page.
Enter the transaction details.
Click the currency drop-down next to Customer Name and select the currency in which you want to create the transaction.
Click Save.
Creating a transaction using a different currency
View Multi-currency Details of Customers and Vendors
Contact List Page
The receivables, payables and unused credits for different currencies will be listed below the customer’s or vendor’s default currency.

Changes in contact list page after enabling Multi-currency
Contact Details Page
Receivables or Payables will be displayed as a table. It contains the outstanding receivables or payables, unused credits, and the currency in which you have recorded transactions for your customers or vendors.

Changes in contact details page after enabling Multi-currency
Customer and Vendor Statements
The Statement section contains the breakdown of all the currencies in which you have created transactions.

Changes in customer and vendor statement after enabling Multi-currency
Recording Payments Received or Made
You can also record payments in currencies you have invoiced your customers or recorded vendor bills.

Go to Payments Received to record customer payment or Payments Made to record vendor payment.
Select the currency in which you want to record the payment.
Enter the Amount Received if you are recording customer payment or Payment Made if you are recording vendor payment.
Enter the amount for each unpaid invoice or bill.
Click Save.
How to record payment received in a particular currency
Suppose you record a payment in a currency for which you have no transactions for the customer or vendor. In that case, the payment will be recorded as an excess payment.

Recording payment received in a currency in which you have not created any invoice
Reports
We have added Collapse All Currencies and Expand All Currencies buttons for reports that support Multi-currency Transactions for Each Contact.

Collapse All Currencies displays transactions created in the default currency of the customers or vendors.

Expand All Currencies displays all the transactions created for your customers or vendors.

The following reports support Multi-currency Transactions for Each Contact:

AR Aging Summary Report
AP Aging Summary Report
Customer Balances Report
Customer Balances Summary Report
Vendor Balances Report
Vendor Balances Summary Report
Purchase Orders By Vendors Report
Changes in reports that support Multi-currency
Advanced Search
When performing an advanced search, you can use the currency field as a filter to search for transactions of a particular currency.

Performing advanced search using the currency field Result of advanced search performed using currency field as filter
