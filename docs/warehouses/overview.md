# **Warehouses - Overview**

In Zoho Inventory, you can add multiple warehouses which represents the physical storage buildings where you keep stock. While creating orders, you can choose the warehouse from/to which you want to dispatch (sales) or receive (purchase) stock. You can also issue transfer orders to perform inventory transfers between warehouses.

## **Enable multiwarehouse**

To enable multi-warehouse management in Zoho Inventory:

- Go to Settings > Warehouses.
- Click Enable Multiwarehouse. You can now start adding more warehouses.

## **Add new warehouse**

To add a new warehouse to your organization:

- Go to Settings > Warehouses.
- Click on the + New button on the top.
- Enter the details of the warehouse and click Save. Your new warehouse will get added.

## **Change warehouse status**

- Designate a primary warehouse
- Deactivate & reactivate warehouse

### **Designate a primary warehouse**
When you enable multiwarehouse in Zoho Inventory, your first warehouse is created by default with the organization address and is set as the Primary Warehouse. Whenever a transaction is created for an item the stock of the primary warehouse gets affected.

To change the primary warehouse:

- Go to Settings > Warehouses.
- Click the Gear icon drop-down button next to the warehouse of your choice.
- Select Mark as primary.
- Confirm your selection in the pop-up that follows. The warehouse will now be marked as the primary warehouse.

### **Deactivate & reactivate warehouse**
If a warehouse is temporarily not in use, you can change it’s status to Inactive.

```Pro Tip: When you deactivate a warehouse, the warehouse stock will also be frozen and cannot be used in transactions. Before doing so, it is recommended that you transfer its stock to an active warehouse.```

**To deactivate a warehouse:**

- Go to Settings > Warehouses.
- Click the Gear icon drop-down button next to the warehouse of your choice.
- Select Mark as Inactive.

The warehouse will now be marked as Inactive and won’t be available for use in transactions.

```Pro Tip: To deactivate the current primary warehouse, you must first designate another warehouse as primary warehouse and follow the steps mentioned above.```

**To reactivate a warehouse:**

- Click the Gear icon drop-down button next to the inactive warehouse.
- Select Mark as Active.

The warehouse will now be active and available for transactions.

## **Edit warehouse**

To edit the details of an existing warehouse:

- Go to Settings > Warehouses.
- Click the Edit button next to the warehouse of your choice.
- Make the necessary changes and click Save.


## **Delete warehouse**
If a warehouse is no longer operational, you can delete it in Zoho Inventory. To delete a warehouse:

- Go to Settings > Warehouses.
- Click the Gear icon drop-down button next to the warehouse of your choice.
- Select Delete and confirm your selection in the following pop-up. The warehouse will be deleted.

```Note: You cannot delete a warehouse which has transactions associated with it. Instead, you can mark the warehouse as inactive.```

## **Warehouse Restrictions**

When you enable multi-warehouse management in Zoho Inventory, all warehouses are initially accessible to all users. To limit their access rights, you can set up restrictions and map users with specific warehouses, so that they can view only those warehouse details.

### **Enable Restrictions**

To enable restrictions on warehouses:

1. Go to Settings, then Warehouses.
2. Enable multi-warehouse if you’ve not done it already. Otherwise, proceed to the next step.
3. Click the Enable Restrictions button in the banner that reads Set up user-level restrictions on warehouses. Only Admins can enable this.
4. Choose whether the users can issue transfer orders to All Warehouses or only to the Permitted Warehouses, in the following pop-up.
5. Click Enable.
6. You can change your transfer order preferences by clicking Configure on the top.

### **Configure Permissions**

Once you’ve enabled warehouse restrictions, you can configure permissions for each warehouse:

To set permissions for a warehouse:

1. Click the Gear icon next to a warehouse name.
2. Select Configure Permissions.
3. In the Configure Permissions pop-up, choose the Only selected users option and proceed to select the users from the drop-down for whom you want to provide access to that particular warehouse.
4. Click Save.

Alternatively, you can also go to a user’s page to assign warehouses to them. To do so:

1. Go to Settings, then Users & Roles.
2. Select the user for whom you want to assign warehouses.
3. Go to the Permitted Warehouses section under the More Details tab. You can view the list of warehouses for which the user has access to.
4. Click Configure.
5. Click the warehouse names on the left to add them to the list of permitted warehouses.
6. Select the warehouse that should act as the primary warehouse for this user.
7. Click Save.

### **End Result**

When you’ve set up permissions, the following changes take effect:

- The dashboard and reports remain unchanged for users with access to all warehouses, whereas, restricted users can only view the sales and purchase information in the dashboard and reports of the permitted warehouses.
- Users can view the transactions in the list page if it contains at least one permitted warehouse. However, they cannot open a transaction unless all the warehouses listed in it are accessible to them.
- Restricted users cannot view the overall stock-on-hand details in the item list page. They can, however, view the accounting and physical stock of each item for the permitted warehouses.
- Organizations that have warehouse restrictions enabled are indicated by a lock icon next to their organization name.
- Non-admin users with permissions to create/edit warehouses can:
    - Create warehouses and assign permitted users to them.
    - Modify the list of permitted users for the warehouses they have access to.

## **Disable Warehouse Restrictions**
To remove the restrictions on warehouses:

1. Go to Settings, then Warehouses.
2. Click the Gear icon in the top-right corner.
3. Choose Disable User Restrictions from the drop-down.
4. Click the Disable button in the pop-up to confirm your action.

## **Disable multiwarehouse**
To disable multi-warehouse management in your organization:

- Go to Settings > Warehouses.
- If your organization has more than one warehouse, it is necessary to delete all the warehouses first.
- Click the Disable Multiwarehouse option on the top right corner of the page.