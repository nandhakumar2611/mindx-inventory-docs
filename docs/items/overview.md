Items
Items are the goods or services that you deal with in your business.

Whenever you create transactions for your customers or vendors, you can add these items and their details will be auto-populated.

IN THIS PAGE…
Create Item
Import Items
Create Item

To create an item in Zoho Books:

Go to the Items module in the left sidebar and select Items.
Click + New in the right side of the page.
Enter the Type, Name and other details.
New Item
Sales Information

Fields Description
Rate Rate at which you sell the item to your customers. This rate will be reflected on your sales transactions like invoices, sales orders, etc.
Account Account used to track sales of the item.
Description Add notes related to sales of the item.
Purchase Information

Fields Description
Rate Rate at which you buy the item from your vendors. This rate will be reflected on your purchase transactions like bills, purchase orders, etc.
Account The Cost of Goods Sold account is used for tracking the purchase made for items in Zoho Books.
Description Add notes related to purchases of the item.
Default Tax Rates
Click the Edit icon next to the default tax rates and enter the default GST to be applied on the item (can be changed in transactions).

Intra State Tax Rate: GST applicable on the item’s supply within your registered state
Inter State Tax Rate: GST applicable on the item’s supply outside your registered state
Inventory Information

To enable inventory for the item:

Select the box Track Inventory for this item.
Fill in the required fields.
Track Inventory
Fields Description
Account Account which tracks the inventory of the item. By default, it is Inventory Asset.
Opening Stock Quantity of the item which you have in hand on the opening balance date.
Opening Stock rate per unit Cost at which you purchased the item for the opening stock.
Reorder Point After the stock of the item reaches this level, you will receive a notification.
Preferred Vendor The vendor from whom you wish to purchase this item.
Associate Tags
You can also associate reporting tags to items in Zoho Books.

After entering all the required details, click Save.
Note:
Fields in red are mandatory, others are optional.

Inventory for Items
In Zoho Books, you can enter an opening stock for your items. Whenever you make sales or purchase transactions for items in Zoho Books, this stock gets auto-calculated accordingly. For example, let’s say you enter the opening stock for item A as 100. Then, you make an invoice for a customer by selling 70 units of Item A . Now, the stock will get reduced to 30 (100-70). You now decide to purchase 100 units of item A from your vendor and create a bill for the same. Now the stock will be increased to 130 (100+30). This is how inventory tracking works in Zoho Books.

Import Items
If you already have a list of items, you can import them into Zoho Books in the CSV, TSV or XLS format.

To know the format of the import, i.e. the columns and data to be included in the import file, you can download the sample import file which we’ll be looking at in the steps below.

Go to the Items module and select Items.
Click the Hamburger icon in the top right of the page.
Select Import Items.
Click the Choose File button under Upload file. You can download the sample file for your reference by clicking sample file.
Click Next.
Choose File
You can choose to Skip or Overwrite records. If you choose to overwrite records, you will have to choose a unique field (Item Name, Item ID or SKU) which will be mapped with the equivalent field from the import file. If the values match, then its corresponding fields will be overwritten with the data in the import file.
Note: These fields are case-sensitive and will only be overwritten if the value in field name matches in both the import file and Zoho Books.

Insight: The file size cannot be more than 1 MB.

Choose the Character Encoding and File Delimiter for your file.
Insight: Character Encoding is used to pair numbers with characters. By default, the Unicode Transformation Format (UTF-8) encoding is used which supports a wide range of characters that go beyond 8 bits.

Insight: The Field Delimiter is used to separate two values in a row. While importing bills, the default file delimiter is comma (,) .

Click Next.
Overwrite Records
Ensure that all the fields are mapped correctly in the Map Fields page.
Mark the box Save these selections for use during future imports if you want to use the similar import format next time.
Click Next.
Overwrite Records Map Fields
In the Preview window, click Import.
Import Items
