Item Preferences
Let’s have a look at the various settings you can configure for the Items module in Zoho Books.

IN THIS PAGE…
Basic Settings
Field Customization
Custom Buttons & Links
Basic Settings
To configure your item preferences:

Go to Settings on the top left corner of the page.
Select Items under Items.
Item Preferences
From this page, you can configure the following preferences for your items:

Decimal rate for item quantity
The decimal rate for item quantity comes into play when you are creating transactions (like invoices). By default, this rate is two. You can select any decimal rate of your choice.

Duplicate item name
Prerequisite: Before you can enable duplicate item name, you will have to mark the Stock Keeping Unit (SKU) field as active and mandatory. Here’s how:

Go to Settings on the top left corner of the page.
Select Items under Items.
Switch to the Field Customization tab.
Hover over the SKU field and click the dropdown button at the right end of the field.
Select the Mark as Active option and the Mark as Mandatory option. The SKU field will be made active and mandatory.
Enabling Allow duplicate item names allows you to create or import multiple items with the same name, that may have varied specifications like size and colour. Let’s look at a scenario to understand how this feature will help you.

Scenario: Let’s say Zylker sells a laptop with the item name Dell Precision 360, and the laptop models are in two colours Silver and Metallic Blue. While the item name is the same for both items, the colour differs. Now, each laptop model can be allotted a unique SKU to easily track each item’s movement.

Once you enable this option, you will have to enter the SKU in the SKU field to create an item which will enable you to identify each item with a unique SKU. Also, when you import items, SKU will be used as the primary field for mapping items.

If you had previously added items to Zoho Books without SKU, you can export the items, add the SKUs to the file, import the items back into Zoho Books and overwrite the existing items.

HSN Code or SAC
The Central Board of Indirect Taxes and Customs (CBIC) has mandated HSN Code or SAC for items effective from 1 April 2021. By enabling this option, a unique 4-digit/6-digit HSN code or SAC can be associated with an item based on your business’s annual turnover.

Out of Stock Warning
Every time your stock falls below zero or runs in negative, you will be sent a notification. You can view this by clicking the Bell icon on top of the page.

Reorder Point
If you have set a reorder point while creating an item, you can enable the notification option to send you a reminder when your stock drops below it. This will help you from running out of stock.

Click Save if you’ve made changes to any of the item preferences.
Field Customization
In Zoho Books, the Items module has default fields which can be configured. For example, the Selling Price, Purchase Price, Item Image and SKU. You can configure user level access for these fields or perform various actions on them.

To view the default custom fields:

Go to Settings on the top left corner of the page.
Select Items under Items.
Switch to the Field Customization tab.
Click + New Custom Field on the top right corner of the page.
Default Custom Fields
Configure Access
You can configure different levels of user access for the certain default custom fields. Here’s how:

Hover over the field for which you can configure access and click the Dropdown icon.
Select Configure Access.
Configure Access for Custom Fields
Set the desired level of user permissions.
Click Save.
User Access for Custom Fields
Default Field Actions
You can perform various actions on the default fields in Items such as:

Mark as Inactive
If you want to disable the field temporarily, you can mark it as inactive.

Mark as Active
You can mark a field you have marked inactive as active

Show field in all PDF
The field is displayed in the transaction PDF

To perform actions on default custom fields:

Hover over the field for which you can configure access and click the Dropdown icon.
Select the desired action to be performed.
Default Custom Field Actions
Custom Buttons & Links
You can create new buttons in the Items module to perform specific actions for your transactions, or to open external links. You can create them using deluge script and execute actions based on the functions you add. Learn more about Custom Buttons & Links.
