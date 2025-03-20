# **Introduction - Sales Order**

A Sales Order is a document sent to your customers, confirming the items and prices of a sale. It is usually created after a quote is accepted by the customer and the items are ready to be shipped or delivered.

The workflow for a sales order in Mindx Inventory is as follows:

- Create a sales order detailing the items you are selling and their prices. Save it as a draft.

- Convert the sales order into an Invoice to send to your customer.



---

## **Creating a Sales Order**

Follow these steps to create a sales order:

- Navigate to the Sales Orders section under Sales.
- Click on + New to open the sales order creation page.
- Fill out the required fields:

| **Section**        | **Field**      | **Description**                                                              |
| ------------------ | -------------- | ---------------------------------------------------------------------------- |
| **Header Section** | Sales Order#   | Unique identifier for the sales order. Automatically generated but editable. |
|                    | Order Date     | The date when the sales order is created.                                    |
|                    | Delivery Date  | The expected date of product or service delivery.                            |
| **Dropdowns**      | Warehouse      | Select the warehouse from where the items will be shipped.                   |
|                    | Customer       | Choose the customer for whom the sales order is being created.               |
| **Items Table**    | Item           | Select the item being sold.                                                  |
|                    | Quantity       | Specify the quantity of the item being sold.                                 |
|                    | Price          | Auto-filled based on the item selection, editable if required.               |
|                    | Tax            | Apply the relevant tax percentage or rate.                                   |
|                    | Amount         | Auto-calculated based on quantity, price, and tax.                           |
| **Footer Section** | Customer Notes | Enter any specific instructions or additional information for the customer.  |
|                    | Subtotal       | Displays the total before taxes and adjustments.                             |
|                    | Tax            | Displays the total tax applied.                                              |
|                    | Total          | Displays the grand total, including tax.                                     |

- Select the Warehouse and Customer from the dropdown options.
- Add items to the order, specify their quantities, and adjust prices or taxes as necessary.
- Enter any additional details, such as customer notes or specific delivery instructions.
- Review the subtotal, tax, and total amount to ensure accuracy before finalizing the order.

!!! Tip

     Double-check the delivery date to ensure timely fulfillment of the order, especially during peak seasons.

Creating a sales order efficiently organizes your sales process and helps manage customer relationships effectively.

---

## **Converting a Quote to a Sales Order**

Mindx Inventory allows you to convert an Accepted Quote into a Sales Order. This ensures that customer requirements and agreed prices are directly transferred to the sales order.

Steps:

- Navigate to the **Quotes** section under the **Sales** .

- Select the **quote** you wish to convert.

- On the Details page, click the **Convert to Sales Order** button

- Verify the auto-filled details on the New **Sales Order** page.

- Save the sales order as a draft or send it to your customer.

!!! example "Insight"

    Streamlining the conversion process from quotes to sales orders can significantly enhance operational efficiency and minimize manual data entry errors.

---

## **View Sales Orders**

If you’ve already created sales orders, you can easily view them. Here’s how:

- Navigate to **Sales** > **Sales Orders**.
- Select the sales order you wish to view.

This enables you to track your sales, monitor customer orders, and manage your inventory effectively.

!!! Note

     Consider implementing a systematic naming or numbering convention for sales orders to enhance organization and retrieval.

---

**Next >**

- [Manage Sales Order](manage-so.md)

---

**Related >**

- [Convert Sales Order to Invoice](convert-to-invoice.md)
- [Other Action for Sales Order](other-actions.md)

---
