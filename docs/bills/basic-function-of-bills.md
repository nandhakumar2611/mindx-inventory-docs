# **Basic Functions in Bills**

Let us have a look at some of the basic functions that can be performed on Bills in Zoho Books.

IN THIS PAGE…
Create Bill
View Journal
Record Payments
Record Individual Payment
Record Bulk Payments
View Recorded Payment
Import Bills

## **Create Bill**

To create a new bill in Zoho Books:

- Go to **Purchases** > **Bills** (or press shift + b).
- Click the **+ New** button in the top right corner of the page (or press c + b).
- Fill in the required details.

| **Fields**                | **Description**                                                                                                                                                                                                                                                |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Vendor Name**           | Select the vendor whose bill you’re recording.                                                                                                                                                                                                                 |
| **Source of Supply**      | This place will be auto-selected based on the customer’s GSTIN.                                                                                                                                                                                                |
| **Destination Of Supply** | Select the place where the supply is made.                                                                                                                                                                                                                     |
| **Bill#**                 | Enter the unique bill number.                                                                                                                                                                                                                                  |
| **Order Number**          | Enter an order number for your bill.                                                                                                                                                                                                                           |
| **Bill Date**             | Enter the date on which you create the bill.                                                                                                                                                                                                                   |
| **Due Date**              | Enter the due date for bill payment.                                                                                                                                                                                                                           |
| **Payment Terms**         | Select the time frame within which you need to pay your vendor. For example, Net 15 would mean you’ll have to pay the vendor within 15 days from the date when the bill is created. When you select a payment term, the due date will be adjusted accordingly. |

![New Bill]()

- Choose if the item rates are inclusive or exclusive of tax rates.

- Select the Discount Type. This could either be at the line item level or transaction level. Learn More.

- Select the items for which you were billed in the item table and provide the customer details if you’re billing this to your customer.

  Insight: Click the ellipsis (the three horizontal dots) near the item table to associate reporting tags with the items or clone the item line.

- Add more items by clicking **+ Add** another line.

- Track other charges and landed costs by clicking **+ Add** Landed Cost.

> Pro Tip: You can update the reporting tags for all line items at once by clicking the Bulk Update Line Items option above the item table.

![Item Details]()

- Add items in bulk by clicking the dropdown next to +Add another line and selecting +Add items in bulk.

![Item Details]()

- Include Discounts and add Adjustments in the total section.

- Select the TDS rate, if applicable for the purchase. This will be applied on the Sub Total of the bill. Learn how to add TDS Rates.

- Select the TCS Rates (as per 206C - 1H), if applicable for the purchase. You can also click the Edit icon to override the calculated rate and enter the tax amount manually.

> **Notes**: The TCS will be calculated on the total amount including all charges and taxes.

---

> **Insight**: The new TCS rates will be applicable only on the amount received after 1 October 2020. You will be required to collect TCS only if your turnover had exceeded Rs 10 crore in the last financial year and the sale of goods to a customer exceeds Rs 50 lakh in the current financial year.

![Item Details]()

- Review the order and include any notes or attachments, if necessary.

- Save the transaction or submit it for approval.

- In this page, you can come across the following cases:

## **Customer Details**

![Customer Details]()

- Select the customer you want to associate to the line items in your bill. By default, the item will be Non-Billable to customer. If you make it Billable, then you can invoice the items and collect payments from them.

To make the item billable:

- Click the Edit icon, mark the Billable option.

- Select a Project to associate with the customer.

- If you had configured a default markup percentage for billable bills and expenses in Settings, the default percentage will be pre-filled. You can edit and change the markup percentage, if needed.

- Click Update.

## **Open Purchase Orders**

![Add Purchase Order Details Add Purchase Order Details]()

If you have any open puchase orders for a particular vendor, you can choose to include them in the bill. Click the purchase order option below the Item Details, select the purchase order(s) to be included, and click **Add**.

- Add notes and attach files to the bill.

- Select a **template** for your bill.

- After entering the required details, click Save as Draft or Save as Open.

---

## **View Journal**

After you have recorded a bill, a corresponding journal will be created for it.

To view the journal:

- Go to **Purchases** > **Bills**.
- Select the desired bill.
- In the overview page, scroll down and click Display Journal (or) click **More** > **View Journal**.

![ Display Journal]()

---

## **Record Payment**

You can choose record the payments you’ve made towards your bills either individually or in bulk.

### **Record Individual Payment**

You can manually record payment for a bill. Here’s how:

- Go to **Purchases** > **Bills**.
- Select the bill for which you wish to record payment.
- Click the Record Payment button in the top right corner of the page.

![Manual Payments]()

- Fill in the required details.

![Record Manual Payments]()

| **Fields**        | **Description**                                                                                                                                     |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Payments Made** | Enter the amount to pay the vendor. By default, the total amount is auto-populated. You can also choose to pay a part of the payment.               |
| **Tax Deducted**  | Mark this box if there is any tax deducted while making payment to the vendor. Enter the Amount Withheld and the Tax Account which tracks this tax. |
| **Payment Date**  | Enter the date you make the bill payment.                                                                                                           |
| **Payment Mode**  | Choose from the different payment modes or configure one of your own.                                                                               |
| **Paid Through**  | Choose the account which tracks this payment.                                                                                                       |

- Add **Notes** and Attach Files to the payment.

- If you wish to send an email notification about the payment to your vendor, mark the box Send a Payment Made - email notification and select the vendor’s email address.

- Click Save.

### **Record Bulk Payments**

Filter and record payments you’ve made towards various bills at once using bulk payments. You can record payments made to the same vendor or multiple vendors. Here’s how you can:

- Go to **Purchases** > **Bills**.

- Filter your bills by their status. You can choose either Open, Overdue, Unpaid or Partially Paid filter by clicking the All Bills filter.

![Filter]()

- Select the bills for which you would like to record the payment.

- Click the More dropdown and select Record Bulk Payment.

![Record Bulk Payments]()

- Select the Paid Through account and Payment Mode.

- Enter the dates on which you made the payment to various vendors.

  - Enter the Reference Number, if any. The Transaction ID can be used as a reference number if you’ve made the payment online.
  - Verify and select the bills for which you’ve made the payment by marking the checkbox.

  ![Bulk Payments]()

  - Click **Save**.

  ***

## **View Recorded Payments**

You can view all the payments that you have recorded for a bill. Here’s how:

- Go to **Purchases** > **Bills**.

- Select the bill for which you have recorded a payment.

- Click the Payments Made tab on top of the page.

![Payments Made Actions]()

From here, you can hover over the payment and click the Edit or Delete icon to perform the desired action.

---

## **Import Bills**

If you already have a list of all the bill of your vendors, you can import them into Zoho Books in the CSV, TSV or XLS format.

To know the format of the import, i.e. the columns and data to be included in the import file, you can download the sample import file which we’ll be looking at in the steps below.

- Go to **Purchases** > **Bills**.
- Click the **Hamburger** icon in the top right corner of the page.
- Select **Import Bills**.

![Import Bills]()

- Click the Choose File button under Upload file. You can download the sample file for your reference by clicking sample file.
- You can Link bills to its corresponding Purchase Orders by marking this box.

> Insight: The file size cannot be more than 1 MB.

- Choose the Character Encoding and File Delimiter for your file.

> Insight: Character Encoding is used to pair numbers with characters. By default, the Unicode Transformation Format (UTF-8) encoding is used which supports a wide range of characters that go beyond 8 bits.

> Insight: The Field Delimiter is used to separate two values in a row. While importing bills, the default file delimiter is comma (,) .

- Click Next.

![Select File]()

- Ensure that all the fields are mapped correctly in the Map Fields page.

- Mark the box Save these selections for use during future imports if you want to use the similar import format next time.
- Click Next.

![Map Fields]()

- In the Preview window, click Import.

Next >
Functions in Bills

Related

Overview - Bills
Manage Bills
Other Actions for Bills
Bill Preferences
