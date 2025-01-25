# **Overview**

Items are the goods or services that you deal with in your business.

Whenever you create transactions for your customers or vendors, you can add these items, and their details will be auto-populated.

## **Create Item**

To create an item in MindX Inventory:

- Go to the Items module in the left sidebar and select Items.
- Click **+ Add** Item on the right side of the page.

Enter the following details in the New Item form:

| **Field**                       | **Description**                                                                                    |
| ------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Name**                        | Enter the name of the item.                                                                        |
| **SKU**                         | Enter the Stock Keeping Unit (SKU) code for the item.                                              |
| **Measure**                     | Select the unit of measurement for the item (e.g., kg, cm).                                        |
| **Supplier**                    | Choose the preferred supplier for this item from the dropdown.                                     |
| **Tax Preference**              | Specify whether the item is Taxable or Non-Taxable.                                                |
| **Selling Price**               | The price at which you sell this item to your customers.                                           |
| **Buying Price**                | The price at which you purchase this item from your vendors.                                       |
| **Tax**                         | Select the applicable tax rate for the item.                                                       |
| **Reorder Point**               | Set the minimum stock level at which a reorder notification will be triggered.                     |
| **Advanced Inventory Tracking** | Specify additional inventory details such as opening stock, stock value, and associated warehouse. |

- Optionally, upload an image for the item using the Upload File feature (supports PNG, JPG, GIF up to 10 MB).
- Click **Save** to add the item or Cancel to discard the changes.

---

## **Import Items**

If you already have a list of items, you can import them into MindX Inventory in supported formats such as CSV, TSV, or XLS.

Steps to Import Items

- Go to the Items module and select Items.

- Click the three dot icon in the top right corner of the page.

- Select **Import Items**.

- Click Choose File to upload your file. You can download a sample file for reference by clicking Sample File.

- Choose to Skip or Overwrite records during import.

> Skip: Skips duplicate entries.
> Overwrite: Updates existing entries with matching fields (case-sensitive).

Settings During Import

- Map the fields from your file to the system fields on the Map Fields page.
- Save the mapping for future imports by checking Save these selections for future imports.
- Review the Preview window and click Import.
  > Note: The maximum file size for import is 1 MB.

## **Inventory Tracking for Items**

MindX Inventory allows you to track the stock levels of your items automatically.

For example:

- If the opening stock for Item A is 100, and you sell 70 units, the stock reduces to 30.
- If you purchase an additional 100 units, the stock increases to 130.
  This system ensures real-time inventory tracking based on your sales and purchase transactions.
