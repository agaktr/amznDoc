# SETTINGS

By clicking on `Settings` on the right of the window, you can adjust various table settings for better UI experience.

https://www.loom.com/share/91a8247086a74d0aa43b8541cf9d65e0

# STOCK STATUS REPORT

On this screen, you can view the current stock of both active and inactive products along with their manufacturing cost. 

By clicking the `Export .xlsx` a `.zip` file will be downloaded containing both tables as `.xlsx` files.

[stock-status-1656001878830.zip](https://github.com/agaktr/amznDoc/files/8969076/stock-status-1656001878830.zip)

https://www.loom.com/share/b4883a9398c2481ab31580b922d3ea02

# STOCK ENDURANCE 

## Calculate (Step 1)

This screen is the start of our order application. Here we can observe the needed stock of each SKU based on our `Days for stock to globally last` input. 

Before starting the supplier order, enter the amount of days in the `Days for stock to globally last` input and click `Calculate` button in order for the SKU table to be refreshed.

When done, click the `Start supplier order` button to enter the next procedure.

https://www.loom.com/share/25d0c77cc2f2444581955dcf1e669763

## Start supplier order (Step 2)

In the start of the supplier order procedure, we can click on the SKU column to deactivate whole Item from order or click on a Marketplace column to deactivate only that marketplace.

When done, click the `Start stock calculation` button to enter the next procedure.

https://www.loom.com/share/37aabf53437e49179bb303eeee60a627

## Start stock calculation (Step 3)

On this procedure, items order amount has been rounded up to the nearest 50 items. 

The excess items have already been added up in `Order` column on different marketplaces.

Click on any `Order` column to manually edit the order amount.

When done, click the `Start pricing report` button to enter the next procedure.

https://www.loom.com/share/64f179fe20a94cd6bd06ff329d2f05c2

## Start pricing report (Step 4)

On this procedure, you can review the total cost of the order.

By clicking the `Export XLSX` a `.xlsx` file with the table will be exported.

When finished, click on "Save report" to add the order entry on the database.

After saving, you will be redirected to the order screen where you can print the supplier orders.

[order-report.xlsx](https://github.com/agaktr/amznDoc/files/8969078/order-report.xlsx)

https://www.loom.com/share/d7f55473b2a2447f858a51edbb714d5c

# ORDERS
#### All orders

By clicking `show` button on any order, you will be redirected to the order screen where you can print the supplier orders.

<img src="https://user-images.githubusercontent.com/45101051/175343984-4bcb43dd-bfee-444e-99f0-bd29410b248f.png" alt="image" width="400">

## Order (Step 5)

By selecting `Report status` and clicking `Save` button, you can change the order status and mark it as completed.

By clining on any `Print` button on the Cards/Boxes/China Supplier/India Supplier you can directly print the order and send it to the corresponding supplier.

https://www.loom.com/share/db61684a88654dd7bca5ad68b5b026a1

# Shipments
## New Shipment (Step 6)

After the shipment has arrived from the manufacturers, upload the SKU/quantity `.xlsx` file by clicking the `Save` button.

This will create a new Shipment object in the database and it will redirect you to the shipment interface.

https://www.loom.com/share/d310c49c60e84b3dba7573b33af3708f

#### All Shipments

By clicking `show` button on any shipment, you will be redirected to the shipment interface.

<img src="https://user-images.githubusercontent.com/45101051/175348176-ca223c13-68e3-4a8a-8d4e-f60e1daf6281.png" alt="image" width="400">

## Shipment (Step 7)

In this panel you observe the shipped items and the "wants" of each marketplace.

By clicking `Calculate shipments` button and clicking `Save` button, shipped items will be distributed to all warehouses based on their demand so they all last the same amount of time.

With red color are the items that currently they need more items than we bought and with green the items that require less than we bought.

By clicking the `Download XLSX` a `.xlsx` file with the table will be exported that you can manually edit so you can create a FBA Workflow with it.

[shipment-report.xlsx](https://github.com/agaktr/amznDoc/files/8969083/shipment-report.xlsx)

https://www.loom.com/share/f2d90aad98e44d3bb267e8ebdf078993

# FBA Workflows
## New Workflow (Step 8)

After editing the shipment file, upload it by clicking the `Save` button.

This will create a new FBA Workflow object in the database and it will redirect you to the workflow interface where you can start the distribution procedure.

https://www.loom.com/share/aec393f936de4b6c9a0ab4459ff9929f

#### All Workflows

By clicking `show` button on any workflow, you will be redirected to the workflow interface.

<img src="https://user-images.githubusercontent.com/45101051/175351304-dfe900dd-6999-438d-ba60-296c0e0c1f6a.png" alt="image" width="400">

## Workflow (Step 9)

In this panel you observe the distributed items on each warehouse.

By clicking the `Download Manifest` a `.zip` file will be downloaded containing all countries manifest file which can be uploaded directly to amazon to start the FBA process.

https://www.loom.com/share/8ae9ecef52d249b487ccd99e62949aed
