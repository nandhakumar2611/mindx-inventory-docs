Items
Items are either goods that you purchase from your vendors and sell to your customers, or, services that you provide for which you get paid. In Zoho Inventory, you can add these items with ease and manage their inventory such that, every time you create a purchase request to your vendor, its stock increases and when you sell the items, its stock decreases automatically.

The upcoming sections will guide you in detail on the various ways in which you can add your items and manage them in Zoho Inventory.

IN THIS PAGE…
Create New Item
Advanced Inventory Tracking
Track Serial Numbers
Track Batch Numbers
Import Items from Other System
Import Items from Zoho Books
Import Products from Zoho CRM
Create New Item
To create a new item in Zoho Inventory:

Go to the Items module in the left sidebar.

Click the New Item button or the + New button on the top.

create button for item
You can also create an item from a transaction on the fly. Here’s how:

Open a new sales or purchase transaction.

Go to the Item Details section and click the empty space under it.

Click the + Add New Item option from the drop-down.

Item creation from a transaction
In the New Item page, fill in the following details:

Add Primary Details
Add Sales & Purchase Details
Add Inventory Tracking Details
Primary details
Choose whether your item should be classified under Goods or Service.

Pro Tip: Service items can be used for adding packing costs, labor costs and other services. These items will not be displayed in while creating packages and shipments. You cannot track inventory for these items.
Enter the Name of the item.

Record the SKU (Stock Keeping Unit) for the item.

Insight: The SKU field will serve as one of the unique identifiers for an item. Here, you can store your item’s barcode information, so that you can scan and retrieve the item while creating transactions.
Choose from or enter a unit of measurement (E.g. Kgs, Pieces, Liters etc.) for the item in the Unit field.

Choose a category or add a new category for your item. Learn more about item categories in Zoho Inventory.

Click the Returnable Item checkbox if you accept sales returns for this item. Sales returns can be created only for those items you qualify as returnable.

Enter the HSN or SAC code for your item. If you don’t know the HSN or SAC code for your item, click the search icon next to the field to find the appropriate code.

Insight: The Central Board of Indirect Taxes and Customs (CBIC) has mandated HSN Code or SAC for items effective from 1 April 2021. If your previous year’s annual turnover is less than ₹5 crores, you will have to use a 4-digit HSN Code or SAC and if it is more than ₹5 crores, you will have to use a 6-digit HSN Code or SAC. If you had the HSN Code or SAC field enabled, the 6-digit HSN Code or SAC will be enabled in Zoho Inventory by default, to ensure that you create tax-compliant invoices from 1 April 2021.
Choose a tax preference for your item.

Item Primary Info
Upload different images of your item. You can upload up to fifteen images for an item.(File format: .gif, .png, ,jpeg, .jpg, .bmp; Max File Size: 5 MB each). Choose one picture as the primary image.

Multiple image upload
Record the dimensions of the item. This will be helpful if you want to calculate the package geometry for an order.

If applicable, you can record other product codes associated with the item in the UPC, EAN, MPN and ISBN fields.

Insight: The UPC and EAN fields are numeric fields. The MPN and ISBN are alphanumeric fields that support alphabets, numbers, spaces and even hyphens.
Item Measurements
Sales & Purchase Details
Enter the Selling Price and Purchase Price for the item.

Associate a sales account (The default account will be Sales) and a purchase account (The default account will be Cost of Goods Sold).

Pro Tip: You can also add a new account under ‘Cost of Goods Sold’ by clicking the + New Account option from the Account drop-down. You can then associate the new account to the item to keep track of the purchases.
Add a brief sales and purchase description for your item which will be displayed on all the respective transactions.

Item Sales & Purchase Info
Click the pencil icon to select the default Interstate and Intrastate tax rates for your item. This will be applied to the item automatically when its added to a transaction.

Default Tax Rates
Inventory Tracking Details
Select the Track inventory for this item option if you wish to track stock for this item. You cannot disable inventory tracking once you have recorded transactions for the item.

Insight:
If you do not want to keep stock for this item, disable this option to create a non-inventory item.
This option will be disabled by default for service items.
If you have enabled Advance Inventory Tracking option in your organization, choose whether you want to track your items by serial number or by batch number. If you don’t want to track either, choose ‘None’ and proceed.

Set the Reorder Point and add a Preferred Vendor of your choice for this item.

Insight: Setting a reorder level helps you restock items before they run out.
Item Inventory Tracking
Select an account to track the inventory for your item.

Enter the Opening Stock(if any) and the Opening Stock Value which is the average purchase price of the item. If you have enabled multi-warehouse, enter the Opening Stock and Opening Stock value for each warehouse.

Insight: Opening Stock refers to the quantity you have on hand before you start tracking inventory for the item.
Item Opening Stock
Advance Inventory Tracking
Zoho Inventory provides two advance features to track your stock flow accurately. But first, make sure to enable Advance Inventory Tracking in your item preferences and check the Track Inventory option in the New Item page to access the advanced inventory tracking options for your item.

Serial Number Tracking
Batch Number Tracking
Insight:
Your current subscription plan in Zoho Inventory must allow you to access the advanced inventory tracking features.
Each item can be tracked either by serial numbers or by batch numbers, but not both.
Track Serial Numbers
To track your item by serial numbers:

Open the new item page and fill in the necessary details.

Choose the Track Serial Number option under Advanced Inventory Tracking.

If you’ve entered an opening stock, you can add serial numbers for the given opening stock in the field below.

If you have enabled multi-warehouse in your organization, click the ellipsis icon at the end of each warehouse row and click Add Serial Numbers.

Add Serial Numbers
Enter the serial number for the opening stock given in each warehouse.

Insight:
You can enter up to 200 serial numbers for an opening stock.
You can either enter the serial numbers manually or scan the barcode of the item.
Add Serial Numbers 2
Click Save. The serial numbers will now be available for your sales transactions. You can also choose to save the item and enter the serial numbers at a later point while creating a bill.

Pro Tip: You can also add serial numbers to composite items.
Track Batch Numbers
Open the new item page and fill in the necessary details.

Choose Track Batches under Advanced Inventory Tracking.

If you’ve entered an opening stock, you can add batch details for the given opening stock in the fields below.

If you have enabled multi-warehouse in your organization, click the ellipsis icon at the end of each warehouse row and click Add Batches.

Batch tracked item creation
Enter the batch details for the opening stock given in each warehouse.

Insight: You can enter up to 100 batch numbers for an opening stock.
Batch tracked item creation 2
Field Name	Description
Batch Reference#	A unique number which will serve as a reference for you to save and track your batches in Zoho Inventory. This is not the manufacturer batch number.
Manufacturer Batch#	Batch number provided by your manufacturer.
Manufactured Date	The date on which the item was manufactured.
Expiry Date	The date until which the item is consumable.
Quantity in	Quantity of the item that you wish to add in each batch.
Insight: You can enter decimal quantity (up to 6 decimal places) for batches. For instance, a certain quantity of milk has to be divided into batches. In Zoho Inventory, you will be able to add 1.91L in batch 1 and 3.560L in batch 2 and so on.
You’ll also be able to enter batch numbers for items while recording a new bill.
Import Items
To import items into your Zoho Inventory account:

Navigate to the Items module.

Click on the Menu icon icon.

Select the Import Items option.

Items Menu
Click Upload File to browse and select the file to upload from your device.

To update the details of all your items at one go, you can choose the overwrite option while importing. Learn how.

Choose the character encoding involved from the drop-down. By default, the character encoding is UTF-8(Unicode).

Choose the File Delimiter(comma or semicolon). By default it will be comma for a .csv type file.

Click Next to proceed to mapping the fields.

Items File Upload
To overwrite duplicate records, you must choose a unique field (Item Name, Item ID or SKU) which will be mapped with the equivalent field from the import file. If the values match, then its corresponding records will be overwritten with the data in the import file. For example, if you want to update item names, you can choose Item ID or SKU as the unique field. If the SKU/Item ID that you’re trying to import exists, then its corresponding item name and other details will get updated.

Zoho Inventory finds similar fields and maps them automatically. You can make changes, if needed.

Check the box near the Save these selections for use during future imports option to automate mapping for future imports.

Click Next to proceed to the Preview window.

Items Mapping
View a summary of the number of invoices ready for import, number of skipped records and unmapped fields will be shown.

Click Previous to make any changes. If everything is ready, click Import.

Items Import Preview
Import Items from Zoho Books
Zoho Books is an in-house accounting platform that is built to seamlessly integrate with Zoho Inventory. This means that all your customer information, item information, transactions etc., entered in one of these platforms will automatically be available in the other, thus, preventing double entry.

If you already have an organization in Zoho Books, learn how you can integrate it with Zoho Inventory.

Import Products from Zoho CRM
You can pull the items into Zoho Inventory from Zoho CRM. Learn more about:

Integrating Zoho Inventory with Zoho CRM.
Configuring your product sync.
Triggering an instant sync between Zoho Inventory and Zoho CRM.
Pro Tip: The items synced from Zoho CRM will only have sales information. To enable inventory tracking for these items, you must first edit them and enable purchase information.
