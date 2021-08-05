# Learning ERPNext

## Module 1

### 1.0 Introduction
This document assumes you are curious to know what ERPNext is about and you are interested in learning how to use it.

### 1.1 Quick overview
ERPnext is a software that runs on a linux computer (on virtualbox in any OS) or a server. You access it with a web browser.
You enter information about many things related to your company or organization:

* Customers
* Suppliers
* Sales
* Accounting
* Inventory of Items (Stock)
* Projects
* Manufacturing
* Retail sales

It is also incorporating several domain specific functions for industries such as:

* Education
* Agriculture
* Healthcare
* Non-Profits


ERPNext already has basic documentation, videos and a support group with plenty of community members that can support you on your journey to learn how to use this software.

ERPNext also allows your suppliers and customers to access a portal to manage
information related to your company, and it also has a web site for e-commerce.

* Supplier and Customer Portal
* Web site
* Comercio electronico (e-commerce)

### 1.2 Structure
The following course or tutorial is divided into 5 modules, which will enable you to master ERPNext.

> * Module 1: Introduction to ERPNext
> * Module 2: Basic usage
> * Module 3: Intermediate usage
> * Module 4: Advanced usage
> * Module 5: Becoming an expert

This course is divided in 5 modules. Each module will take your learning from the general
to the more specific, in the same manner that we talk about a ship in general terms, each 
additional module will explore the topics with more specificity about the ship, such as 
propulsion systems, bilge systems, navigation, crew, etc. At the end we will reach detailed
explanations about individual ship components such as engines, pumps, compass, captain's duties, etc.
With this, you can revise the basics or go down to the details when necessary to master ERPNext.

I personally like a specific order to better refer to topics in a structured manner, so I have
numbered items by levels, separated by decimals. Each module is at a level 1. Level 2 is represented
by a level one number, separated by a decimal and another number, and then another number
that begins the ordinal count of the topic within the module.
You can refer to a specific topic by the number. This also will help when indexing.
Each sub-topic is separated by a decimal point from the number that represents the parent or principal topic.

### 1.3 Module 1 Objective
- How to access or install and configure ERPNext
You use any web browser to manage anything related to ERPNext system.

You can run it locally on a linux machine, or in a virtual server on any operating system.

Ideally you use a web server with a public IP address so you can access the service from any internet
connected device.

This module focuses on learning to set it up, configuring it and use this instance to 
satisfy the basic accounting and management needs of a business or non-profit.

### 1.4 Getting an instance of ERPNext

#### 1.4.1 Trial account on  erpnext.com
The quickest and easiest way to learn it, is to open a trial account on [erpnext.com](https://www.erpnext.com)
Once set up, jump straigh to Module 2.

#### 1.4.2 - Local installation in any operating system with VirtualBox
The next easiest way is to download a pre-installed virtual image to use with Oracle's VirtualBox.
Download VirtualBox from [here](https://www.virtualbox.org/)
Since ERPNext is [open source software](https://en.wikipedia.org/wiki/Open-source_license),
 you can download a production image directly from this site and use for any purpose allowed in the license:
[https://erpnext.com/download](https://erpnext.com/download)
You run virtualBox, import the appliance and start the server. Make sure you configure the
virtual networking cards properly. I usually use a Bridged adapter to my existing WiFi
connection on a MAC so that the virtual machine gets an IP address from my router. This way, I can
access it using a local IP address on the web browser.

## Module 2:  Basic use

In this module we will learn how to use the program, how to configure the most important basics
how to find help for specific questions and we will explore the concept of the DocTypes.

The rest of the module will be an initial exploration of the program modules for

* Accounting
* Human Resources
* Stock or Inventory
* Buying
* Selling
* CRM (Customer Resource Management)
* Manufacturing
* Projects
* Assets
* Web Site

### 2.0 Module 2 objectives

- Basic operation of the Frappé/ ERPNext Framework
- Configure ERPNext to manage products and services for purchase or sale
- Configure your accounts, product and service groups
- Manage suppliers and customers
- Make a purchase cycle (from quotation to payment)
- Make a sales cycle (from a lead to receiving the customer's payment)
- Manage stock

### 2.1 Basic Operation
#### 2.1.1 How to Login (Video 002)
1. Open your web browser
2. Type the IP address or domain name for your ERPNext server in the address bar for your browser.
3. When the ERPNext access page is loaded, you should see a couple of fields requesting username and password,
	If you don't, click the link on the top right and select the menu item: "Switch to Desk"
4. Enter your username
5. Enter our password
6. Press **Sign In** or type **ENTER**
7. Ready, your ERPNext desk is shown
#### 2.1.2 Configure your user (Video 003)
##### 2.1.2.1 - Change your password
1. From the desktop, click on the top right of the screen where your user is shown
	to show a collapsible menu.
2. Click on **My Settings**
3. In the page that is loaded, scroll down and in the section
	**Change Password** click to deploy and show the field where you can enter a new password
4. Enter your new password
5. Select (or not) the options to :
	5.1 Email notification of password change
	5.2 Logout of all devices while the password is changed.
6. Scroll back up and click on **Save**

##### 2.1.2.2 - Change your language
1. From the desktop, click on the top right of the screen where your user is shown
	to show a collapsible menu.
2. Click on **My Settings**
3. In the *Language* field, click and scroll to select
4. Select one language.
5. Scroll back up and click on **Save**

##### 2.1.2.3 - Add more information
1. From the desktop, click on the top right of the screen where your user is shown
	to show a collapsible menu.
2. Click on **My Settings**
3. Scroll down and click on the  **More Information** section to deploy it
4. Add a gender
5. Add a telefono
6. Add a móvil
7. Add a date of birth
8. Add a location
9. Add a short biography
10. Select "*Mute sounds*" if you do not wish to listen to alert and confirmation sounds in ERPNext
11. Scroll back up and click on **Save**

##### 2.1.2.4 - Add a desktop backround image
1. From the desktop, click on the top right of the screen where your user is shown
	to show a collapsible menu.
2. Click on **My Settings**
3. Scroll down and click on the  **Desktop Background** section to deploy it
4. Click on **Attach**
5. Browse and select an image file in .png or .jpg format in desirable dimensions and click **Upload**
6. Check the background style, leaving it in full screen or tile as necessary.
7. Modify the image and the background style, until satisfied with your background image.

##### 2.1.2.5 - Remove a desktop backround image
1. From the desktop, click on the top right of the screen where your user is shown
	to show a collapsible menu.
2. Click on **My Settings**
3. Scroll down and click on the  **Desktop Background** section to deploy it
4. Click on x on the side of the filename attached for the Background image to eliminate it.

##### 2.1.2.6 Configure your desktop icons (Video 004)
1. From the desktop, click on the top right of the screen where your user is shown
	to show a collapsible menu.
2. Click on **Set Desktop Icons**
3. You can choose to change **By User** and your user, or choose all
4. You can also choose **Select all** and click again to unmark all
5. Select the modules that you want to show on the desktop
6. Scroll up and click on **Save**

> To move the icons, click and hold until the icons shake
	Move the icon to the desired place
	When done, click on the desk for them to stay fixed again
> To eliminate an icon, follow the same procedure above, instead click the x to erase them
##### 2.1.2.1 Add a user (Video 005)
#### 2.1.3 Frappe Framework basics (Video 006)
* Images
* Attachments
* Assignments
* Labels
* Users
* Sharing
* Time of creation and editing
* Comments
* Specific DocType action buttons
* The **Make** Button
* Duplicating documents
	I consider this particular feature of ERPNext one of the most useful for day to day
	transactions, because it allows you to copy data from an existing DocType such as a 
	purchase order and create a new one with the same items, just changing the amount and date
	or other parameters to suit this particular doctype instance.
	
##### 2.1.3.1 DocTypes: Main and supporting (Video 007)
Example: A main or master DocType is one such as Item or Sales Invoice. A supporting DocType is 
an Item Attribute or a Sales Invoice Item

* User
* Item
* Item Price
* Customizing (adding fields)
* Series and numbering

#### 2.1.4 Where to find support and help (Video 008)
[Documentation](https://erpnext.org/docs/user/manual)
[YouTube Video Channel](https://www.youtube.com/c/erpnext)
[Discussion Forum](https://discuss.erpnext.com/)
[Chapters](https://erpnext.org/chapters)

### 2.2 Program modules
#### 2.2.1 - Accounts
##### 2.2.1.1 - Company (Video 009)
##### 2.2.1.2 - Cost centers (Creating cost centers) (Video 010)
##### 2.2.1.3 - Chart of accounts or Account tree (creating accounts) (Video 011)
##### 2.2.1.4 - Journal Entry (Accounting entry) (Video 012)
##### 2.2.1.5 - Opening Entry (Video 013)
#### 2.2.2 - Human Resources
##### 2.2.2.1 - Employees (Video 014)

##### 2.2.2.2 - Branch (Video 015)
##### 2.2.2.3 - Department (Video 016)
##### 2.2.2.4 - Designation (Video 017)
#### 2.2.3 - Stock
##### 2.2.3.1 - Item Groups (creating groups) (Video 018)
##### 2.2.3.2 - Warehouse (creating warehouses) (Video 019)
##### 2.2.3.3 - Items (Video 020)
	The importance of marking (or not) the checkbox "Maintain stock"
#### 2.2.4 - Buying
##### 2.2.4.1 - Add a supplier (Video 021)
##### 2.2.4.2 - Modify suppliers (Video 022)
##### 2.2.4.3 - Add a quotation from the supplier (Video 023)
##### 2.2.4.4 - Adding a purchase (Video 024)
##### 2.2.4.5 - Full purchase Cycle: Supplier quotation, purchase order, purchase receipt, purchase invoice and payment  (Video 025)
#### 2.2.5 - Selling
##### 2.2.5.1 - Add a customer  (Video 026)
##### 2.2.5.2 - Modify customers  (Video 027)
##### 2.2.5.3 - Add quotation for the customer (Video 028)
##### 2.2.5.4 - Adding a sale  (Video 029)
##### 2.2.5.5 - CFull sales cycle:  Customer quotation, sales order, delivery note, sales invoice, payment request and payment (Video 030)
#### 2.2.6 - CRM (Customer Resource Management)
##### 2.2.6.1 - Use of CRM to increase sales and customer service (Video 031)
##### 2.2.5.2 - Leads and Opportunities (Video 032)
##### 2.2.5.3 - Campaigns (Video 033)
#### 2.2.7 - Manufacturing
##### 2.2.7.1 - Bill of Materials (Video 034)
	For manufacture or subcontracting
#### 2.2.8 - Projects
##### 2.2.8.1 - Internal project with tasks and progress (Video 035)
#### 2.2.9 - Assets
##### 2.2.7.2 Asset category (Video 036)
##### 2.2.7.1 Creating an asset(Video 037)
#### 2.2.10 - Web Site
##### 2.2.10.1 - Creating a Web Page (Video 038)
##### 2.2.10.2 - Pasos para crear una pagina web - Basado en conferencia Octubre 2017
[Rushabh - Frappe Portal, Website + Web Forms + E-commerce](https://www.youtube.com/watch?v=ruJBetD7In0)
###### 1 - Prepare su sitio si no lo ha hecho
Lanze su sitio en un servidor remoto si no lo ha habilitado.

###### 2- Planifique su estructura
En este caso, el sitio ejemplo maneja eventos. 
Cada evento tiene una imagen, un titulo, una fecha y un boton para reservar.
Luego hay contenido sobre lo que el evento posee.

Se creara un modulo para eventos publicos en ERPNext.
Luego se creará un objeto llamado "Evento".
Para reservar un ticket, crearemos un objeto "Ticket"
Esto son dos DocTypes que crearemos.
Finalmente, crearemos una vista web.

Planifique su "tema" del sitio basado en sus colores.

###### 3 - Configur your website
Let's configure the theme.
Hay un Standard theme, pero Hagamos uno nuevo.
**WebSite > Setup > Website Theme >

1. Add the theme name
2. Make sure the Apply Style checbox is marked
3. Check if it is a Custom stye
### 2.3 Module 2 Conclusion

In this module we have learned the most basic and important aspects of ERPNext.
We learned how to login, configure your user, configure your desktop icons, select your
language, access the configuration menu and added a user.

We also learned about the very important Frappé framework, which empowers ERPNext beyond just
the main and support DocTypes, especially its functionality allowing assignments of
documents to other users, attaching files to these documents, sharing individual documents
whose individual permits are restricted to certain users, track all activities on a document
chronologically and by author, including the comments and communications that can be placed directly on the DocType.
We also learned how to search for help and support.

We then initiated our exploration of the accounting modules by creating a company, cost centers,
accounts and learning how to create accounting entries.

We saw the human resource module where we created the first employee. We moved to the stock
module where we learned the importance of properly grouping items, an example of a coding scheme
the creation of a pair of warehouses and then we learned to create items.  Items are some of the most
crucial parts of ERPNext.

After this we moved to know about the Buying module where we created a supplier, modified it
made a quotation as furnished by the supplier, then a direct purchase, and finally a more formal
purchase which includes a supplier quotation, purchase order, purchase receipt, purchase invoice and payment.

We saw then the same process, now in the Selling module, where we added a customer, modified its data,
added a quotation to the customer and finally generated a more formal sale (sales cycle)

We checked how to use the CRM module to manage potential customers, allowing us to increase the 
service to the customer, create marketing campaigns and track leads until converting them to customers.

We checked the manufacturing module and its underpinning: The **Bill of Materials (BOM)** which allowed us
to define which raw materials are needed for a specific product.

The Projects module was overseen, with the creation of a simple internal project with tasks and due dates.
The assets module with its categories and assets, which we will learn how to depreciate and maintain in the next module.
The WebSite module allowed us to create a simple webpage to serve to all users accesing from the web

## Module 3: Intermediate Use
### 3.1 Intermediate use
#### 3.1.1 - Roles (Video 039)
#### 3.1.2 - Permissions (Video 040)
#### 3.1.3 - Series and Numbering (Video 041)
#### 3.1.4 - System settings (Video 042)
#### 3.1.5 - Global settings (Video 043)
#### 3.1.6 - Account settings (Video 044)
#### 3.1.7 - Configuring e-mail account (Video 045)
#### 3.1.8 - Print settings (Video 046)
#### 3.1.9 - Personalized translations (Video 047)
#### 3.1.10 - Additional Setup (Setup Module)  MORE WORK NEEDED HERE
### 3.2 Program modules
#### 3.2.1 - Accounts
##### 3.2.1.1 - Fiscal Year  (Video 048)
##### 3.2.1.2 - Currency (Video 049)
##### 3.2.1.3 - POS Configuration (Video 050) - [original video](https://youtu.be/4WkelWkbP_c)
##### 3.2.1.4 - Payment methods(Video 051)
##### 3.2.1.5 - Payment entry (Video 057)
##### 3.2.1.6 - Taxes (Selling) (Video 053)
##### 3.2.1.7 - Taxes (Buying) (Video 054)
##### 3.2.1.8 - Sales Invoice (Video 055)
Discounts:  If you apply a percentage discount over the Grand Total, the total will be:
(Sum of itm x qty - Sales tax (included)) - ((Sum of itm x qty - Sales tax (included)) * % Discount)

If you apply a total discount amount over the Grand Total, the total will be:
(Sum of itm x qty - Sales tax (included)) - (Discount Amount)
##### 3.2.1.9 - Purchase Invoice (Video 056)
##### 3.2.1.10 -  Conciliation of Payments(Video 057)
##### 3.2.1.11 - Subscriptions NO VIDEO
The subscriptions functionality in ERPNext allows you to create doctypes periodically

You may create subscriptions for documents like:

* Payment Entry
* Supplier Quotation
* Purchase Order
* Purchase Invoice
* Purchase Receipt
* Journal Entry
* Sales Order
* Sales Invoice
* Customer Quotation
* Delivery Notes

The documents will be created automatically, at the indicated time, as *Draft*
You can indicate if you wish to have them validated automatically upon creation!

Suppose that you must create a purchase invoice for a monthly property rental manually.
With subscriptions, you can create the first monthly invoice manually, and then enable the subscription
so that it automatically generates the next month's purchase invoice, on the day of your choosing.
###### 3.2.1.11.1 - Creating a subcription
1. To crate a subscription, you must have at least one document of the type you wish to repeat. If you have not done
	so, prepare the first one manually and save it.
2. To create the subscription, write this in the empty text box at the top of every ERPNext instance, aka "*Awesome Bar*": **New Subscription**
3. Enter the reference **DocType** for your subscription
4. Enter the series and number of the document that you wish to repeat, this is the same as you created in step 1
5. Select the frequency you wish for the subscription, this can be:
	* Daily
	* Weekly
	* Monthly: You must indicate the specific day of the month when you want it to be created.
	* Quarterly: You must indicate the specific day of the month in which the quarter ends when you want it to repeat.
	* Bi-anually
	* Annual: You must indicate the specific day of the month in which the year ends when you want it to repeat.
6. Indicate the initial date from where you wish to create the first one in the series.
7. Indicate the last date or until when you no longer wish more documents to be created automatically.
	* If the end date is before the next estimated date in the frequency, ERPNext will limit the creaiton of the document.
8. Indicate if you wish the document to be *Validated* at the moment of creation.
	* If you wish to automatically invoice a customer, and have automatic sending of sales invoice, check the field to 
	generate and send the sales invoice automatically.
9. Indicate if you wish to disable the subscription (even though you do not want to erase it)
10. Indicate if you wish to be alerted vía email about the creation of the DocType. When selecting the field,
	you must indicate the following.
	* E-mail subject: You can use Jinja, for dynamic messages such as "New Sales Invoice #123",
	where 123 is the actual series number of the created document by the subscription settings.
	* Email recipients, separated by a new line. You may add as many recipients as you wish.
	* Print format
	* Message: The message for the email can be formated with Jinja, so that you can use dynamic numbers, customer names, etc.
#### 3.2.2 - Human Resources
##### 3.2.2.1 - Human Resources Configuration (Video 058)
##### 3.2.2.2 - Holiday List (Video 059)
##### 3.2.2.3 - Salary structure and components (Video 060)
##### 3.2.2.4 - Payroll entry (Video 061)
##### 3.2.2.5 - Payroll entry tool (Video 062)
##### 3.2.2.6 - Configuring daily work summary (Video 063)
#### 3.2.3 - Stock
##### 3.2.3.1 - Units of Measure (Video 064)
##### 3.2.3.2 - Brands (Video 065)
##### 3.2.3.3 - Stock configuration (Video 065)
##### 3.2.3.4 - Item Variant Settings  (Video 209)
##### 3.2.3.5 - Price List (Video 066)
##### 3.2.3.6 - Stock entry (Inventory movements) (Video 067)
* Initial loading of inventory or stock
	1. Go to Stock module
	2. Select Stock entry
	3. Click on New
	4. Purpose: Material receipt
	5. Indicate destination Warehouse
	6. Enter the name or code of the product, where it says: Item Code
	7. Indicate the quantity to add or load in the inventory.
	8. Repeat for each desired product
	9. If no net rate or value is indicated by ERPNext (Purchase rat eminus sales tax), it will ask for it.
	10. Click on **Save**, and then **Submit**
##### 3.2.3.7 - Stock opening entry(Video 068)
##### 3.2.3.8 - Material request (Video 069)
##### 3.2.3.9 - Purchase Receipt (Video 070)
#### 3.2.4 - Buying
##### 3.2.4.1 - Buying configuration (Video 071)
##### 3.2.4.2 - Product Bundle(Video 001)
 Important:  If you changed the default warehouse AFTER having created a product bundle, make sure you refresh or reload the page.
##### 3.2.4.3 - Buying terms and conditions (Video 072)
##### 3.2.4.4 - Supplier scorecard (Video 073)
##### 3.2.4.5 - Supplier qualification criteria (Video 074)
##### 3.2.4.6 - Supplier qualificaiton variable (Video 075)
#### 3.2.5 - Selling
##### 3.2.5.1 - Selling Configuration (Video 076)
##### 3.2.5.2 - Industry type (Video 077)
##### 3.2.5.3 - Territory(Video 078)
##### 3.2.5.4 - Sales Partner(Video 079)
##### 3.2.5.5 - Sellers (Video 080)
##### 3.2.5.6 - Product Bundle (Video 001) - Revisited
##### 3.2.5.7 - Selling terms and conditions (Video 081)
##### 3.2.5.8 - Selling by means of POS (Video 082)
##### 3.2.5.9 - Pricing Rule NO VIDEO
1. Puedes establecer promociones en las cuales ofrece descuento en la compra de x cantidad de articulos
2. Para cliente X, el precio de venta debe ser actualizado por y cantidad
3. Los productos categorizados bajo el Grupo de Articulos especificado tienen el mismo precio de compra o venta.
4. Los clientes que pertenecen a un grupo especifico de clientes obtienen precio de venta x o un descuento del y %
5. Los proveedores bajo cierta categoría deben de tener un precio x.
6. Puedes agregar margen de venta sobre lista de compras
	6.1 Haga un listado de precios de compra y asegurese de ingresar un precio de compra en ese listado
	6.2 Haga una regla de precio en la cual indique el codigo del articulo de compra. Indique que es una regla para la venta.
	6.3 Agregue el margen porcentual que usted desea sobre el producto de compra
	6.4 Haga su factura de venta y verá el margen aplicado.
#### 3.2.6 - CRM (Customer Resource Management)
##### 3.2.6.1 - Customer Category (Video 083)
##### 3.2.6.2 - Communications (Video 084)
##### 3.2.6.3 - SMS Settings for mobile messaging from ERPNext (Video 085)
#### 3.2.7 - Manufacturing
##### 3.2.7.1 - Subcontracting (Video 086)
##### 3.2.7.2 - Production Order (Video 087)
##### 3.2.7.3 - Timesheet (Video 088)
#### 3.2.8 - Projects
##### 3.2.8.1 - Types of Projects (Video 089)
##### 3.2.8.2 - Type and Activity Cost (Video 090)
##### 3.2.8.3 - Project Tasks (Video 091)
A task is an allocation of work to be completed before a specific time.
A task can exist by itself, or it can belong to a project.

If you wish to see how you create a task from a project, follow the instructiones from project.

To make a new Task, go to **Projects > 	Tasks > New**
Enter the *Subject* or *Title* for the task.
Select if it belongs to a project, if necessary.
Enter the foreseen date from Beggining to End
You may enter the *Expected Time* of the task in hours
You may enter the progress in *Percentage*
Indicate the specific details for this task textually.

If this task depends on another, indicate the previous task here

You may also assign or share a task with colleagues on ERPNext.
##### 3.2.8.4 - Timesheet (Video 092)  [Original video](https://youtu.be/IxY-rSJsA6U)
To keep track of the time used in a task, we create a timesheet
Select activity type
Indicate start time
Indicate hours used
End time is updated.
Save the record.

In the related task you will be able to see the time spent on this task
If the task belongs to a project, then the time spent will be updated there.
#### 3.2.9 - Assets
##### 3.2.9.2 - Asset Maintenance Team (Video 093)
##### 3.2.9.3 - Asset Maintenance (Video 094)
##### 3.2.9.4 - Asset Maintenance Log Entry (Video 095)
##### 3.2.9.5 - Asset Repair (Video 096)
#### 3.2.10 - Tools
##### 3.2.10.1 - Tasks(Video 097)
##### 3.2.10.2 - Files (Video 098)
##### 3.2.10.3 - Calendar (Video 099)
##### 3.2.10.4 - Chat (Video 100)
##### 3.2.10.5 - Note (Video 101)
##### 3.2.10.6 - Activity (Video 102)
##### 3.2.10.7 - E-mail group (Video 103) 
##### 3.2.10.8 - Newsletter (Video 104)
#### 3.2.11 - Web Site
##### 3.2.11.1 - Web Site Configuration (Video 105)
##### 3.2.11.2 - Company Information Configuration (Video 106)
##### 3.2.11.3 - Contact Configuration (Video 107)
##### 3.2.11.4 - Web site Theme (Video 108)
##### 3.2.11.5 - Portal Configuration (Video 109)
##### 3.2.11.6 - Main Page (Video 110)
##### 3.2.11.7 - Blog Configuration (Video 111)
##### 3.2.11.8 - Blog Entry (Video 112)
### 3.3 Module 3 Conclusion

## Module 4: Advanced Use
What we will see here
### 4.1 Advanced Operation
#### 4.1.3 - Domain Specific Configuration
##### 4.1.3.1 - Agriculture Module (Video 113)
##### 4.1.3.2 - Hospitality Module(Video 114)
##### 4.1.3.3 - Healthcare Module (Video 115)
Presentation of the health module, link to module section 12 with details.
##### 4.1.3.4 - Education Module (Video 116)
Presentation of the Education module, link to module section 11 with details.
##### 4.1.3.6 - Services Module (Video 117)
Prepare a video of the workflow or best practices for services.
##### 4.1.3.7 - Manufacturing Module (Video 118)
Prepare a video of the workflow or best practices for manufacturing.
##### 4.1.3.8 - Shopify Module (Video 148) [ERPNext Shopify webinar](https://youtu.be/sd2p-0jATzc) 
With this integration to ERPNext:
* Whenever you add an **Item** or **Customer** to a Shopify Account, it synchronizes with ERPNext automatically adding the item or customer.
* If you add a new **Item** or **Customer** in ERPNext account, item should upload automatically to Shopify.
* You can manually force the synchronization of **Items** or **Customers**.
* You can receive orders from shopify Customers directly in ERPNext.
Requirements: Shopify Account, ERPNext server with domain name

###### 4.1.3.8.1 - Pre-configuration steps in ERPNext to make it easier
1. Create a **Price List** in ERPNext specifically for Shopify **Items**, if desired.
2. Create a specific **Warehouse** in ERPNext for **Items** sold that will keep track of items available for Shopify sales
3. Create a specific **Account** where the deposits from Shopify sales will be registered, under short term assets.
4. Create a specific naming series for shopify *Sales Orders*, if you want to differentiate them from other *Sales Orders*.
5. Create a specific naming series for shopify *Delivery Notes*, if you want to differentiate them from other *Delivery Notes*.
6. Create a specific naming series for shopify *Sales Invoice*, if you want to differentiate them from other *Invoices*.

###### 4.1.3.8.2 - Add ERPNext app to your Shopify account
* On the left sidebar in the Shopify account administration, at the bottom you will see a link for **Apps**.
* Click on the link to open the Shopify App Store
* Search for **ERPNext Connector**
* Click on **Get** to install it on your Shopify account
	This screen will notify you that ERPNext will have the ability to do the following:
	* Modify products, variants and collections
	* Modify customer details and customer groups
	* Modify orders, transactions and fulfillments

* Click on **Install App**
* Enter the data required:
	*Shop Name*: Enter the name of your shop website as provided by Shopify:  [yourstore].shopify.com
	*ERPNext Site Name*: This is the domain name where you are running ERPNext. Example: testsite.com
	*ERPNext User Id*: Enter the user ID (email address) of the user that will have access to synchronize.
	*Password*: The password associated with the ERPNext user indicated above.
* Click on the **Submit** button.
* The Shopify website should now show that the ERPNext app under the **Installed apps**
###### 4.1.3.8.2 - Configure ERPNext to connect to Shopify
Ideally, the ERPNext server will update automatically to add the Shopify connector app.
If not, make sure you install the application from **Setup > Applications > Application Installer > ERPNext Shopify**

1. To access the Shopify Settings, type this in the *Awesome Bar* on top: **Shopify settings**
2. Make sure the box entitled **Enable Shopify** is checked
3. *App Type*: **Public**
4. *Shop URL*: Enter the shop name as entered above **[your_store].shopify.com**
5. *Price List*: Select the default ERPNext Price list
6. *Warehouse*: Set the warehouse where Items will ship from, to fulfill Shopify orders.
7. *Cash/Bank Account*: Set the ERPNext account that will keep track of the  deposits fromShopify sales.
8. *Customer Group*: Although this is automatically set from Shopify, you can set it manually here.
9. *Sales Order Series*: Set the desired series to automatically generate when a shopify order is sincronized with ERPNext
10. Map Shopify Tax / Shipping to ERPNext account
	10.1 Add a row where you will define the Title of the Tax or Shipping charge
	10.2 In the same row, select the ERPNext account where you want to tally these charges
	10.3 The **Title** must equal the name of the additional items in the Shopify invoice. ??? TK
11. *Import Delivery Notes from Shopify on Shipment*: mark if you want to create a delivery note based on
	items marked as shipped on Shopify.
	11.1 You must select the **Delivery Note** series you wish for this 
12. *Import Sales Invoice from Shopify if Payment is marked*: mark if you want to create a *Sales Invoice* automatically
	if payment is added
	12.1 You must select the **Sales Invoice** series you wish to use for this.
###### 4.1.3.8.3 - Synchronize Items from Shopify to ERPNext
1. From within ERPNext, to synchronize manually go to 
	**Shopify settings** by entering it on the *Awesome Bar* and click on **Sync Shopify**
2. A message will pop up stating: 
	*"Queued for syncing. It may take a few minutes to an hour if this is your first sync."*
3. On the settings page, a yellow banner will appear letting you know that:
	*"The Last sync request is queued"*
	This message will change to 
	*Last sync request was successful*  when the latest synchronization has finished successfully.
4. If you press the **Shopify Log** button, you can view all the logs with their title 
	a confirmation of the status, and the Status wheter is was a *Success* or **Failed*
5. If you now go to **Stock > Items**, you will see the items synchronized from Shopify.
	Each item will be identified by the **Shopify Product ID**, and will also have the Shopify
	characteristics such as Description, Image, etc.
###### 4.1.3.8.4 - Synchronize Items from ERPNext to Shopify
1. Go to **Stock > Items** and open each item you want to Synchronize to Shopify
2. Each **Item** has a checkbox to **Sync With Shopify**. Make sure you check this box and **Save** the **Item**
	to confirm the changes.
3. If you also want to Synchronize the Quantity in your warehouse with Shopify, then check
	the box **Sync Quantity With Shopify**. Again, **Save** the **Item** to confirm the changes.
4. Go to **Shopify settings** and click **Sync Shopify** again to push the Items from ERPNext to Shopify.
5. If you go to your Products page in Shopify, you will see the Items you just synchronized from ERPNext.

###### 4.1.3.8.5 - Synchronizing Customers from Shopify to ERPNext
1. In **Shopify**, you can add customers that will be synchronized with ERPNext automatically.
2. In **ERPNext** go to **Shopify settings** and click **Sync Shopify** to synchronize customers.
3. All the data, including address, will be synchronized to the **Customer** entry in ERPNext.
###### 4.1.3.8.6 - Synchronizing Customers from ERPNext to Shopify
To Synchronize a **Customer** from **ERPNext** to **Shopify**:

1. Open the **Customer** document for the desired Customer.
2. Scroll down to the **More Information** section, and mark the checkbox entitled: **Sync With Shopify**
3. **Save** the **Customer** to confirm the changes.
4. Go to **Shopify settings** and click **Sync Shopify** to copy the Customer to Shopify.

###### 4.1.3.8.7 - About Sales Orders
Orders are synchronized one way only: From Shopify to ERPNext.
> ERPNext only pulls orders from shopify!
Your customers "Customer to Business (C2B)" place their orders in **Shopify**.
Your customers "Business to Business (B2B)" place their orders vía the ERPNext portal and account you provide them.
Even if you have products on your website, the link for placing an order should lead them to your Shopify shop.
Once the order has been placed by the customer, the order will synchronize automatically with ERPNext.
A Sales Order created in ERPNext will not synchronize to **Shopify**. It will only get Sales Orders from **Shopify** to **ERPNext**.
###### 4.1.3.8.8 - Delivery Notes
If **Delivery Note** checkbox is selected, ERPNext will synchronize them, and link them to related
**Sales Orders**, **Sales Invoices** or **Payments** if any.
Delivery notes will have both the **Shopify Order ID** and **Shopify Fulfillment ID** listed when they synchronize from Shopify.
Delivery Notes from Shopify synchronization will **always** be in **Draft** status, so that you can edit them and modify them before submitting them.
A submitted Delivery Note that satisfies the **Sales Order** or **Sales Invoice** means that the order has been fulfilled completely.
a Delivery Note created primarily in ERPNext, will NOT synchronize to Shopify! It works only from **Shopify** to **ERPNext**.
###### 4.1.3.8.9- Sales Invoices
If **Sales Invoice** checkbox is selected, ERPNext will create Sales Invoices.
These Sales Invoices will be linked to Delivery Notes, Sales Orders and Payments if any.
If Payment has been received, a linked **Payment Entry** will also be created in ERPNext.

###### 4.1.3.8.10 - Some additional notes
When Items are synchronized from Shopify, the unique product ID from Shopify is copied to ERPNext
so that it does not synchronize twice to Shopify from ERPNext in the next synchronization.
Price List is also updated when synchronized from Shopify.

The Shopify application has a scheduler setup that will synchronize with Shopify frequently (exact timeframe?)

Pending questions to be answered: 
What happens with VAT if included in price with Shopify?
How do we process a return from a customer:
1. With refund?
2. Without refund?

#### 4.1.2 - Data Backups (Video 149)
#### 4.1.3 - Form Customization (Video 150)
	A best practice to use here is to prepend the name of your company to field names (A good practice to prevent errors when updating. You can always copy data from one field to another (column) using mariadb commands later)
	Adding new fields to main doctypes (Customize)
#### 4.1.4 - Personalized Fields (Video 151)
		A best practice to use here is to prepend the name of your company to field names (A good practice to prevent errors when updating. You can always copy data from one field to another (column) using mariadb commands later)
		This particular instruction helps with child table doctypes
#### 4.1.5 - Custom scripts(Video 152)
#### 4.1.6 - Email notifications (Video 153)
#### 4.1.7 - Print formats (Video 154)
	Basic jinja for print templates
	Examples
#### 4.1.8 - Print Style (Video 155)
#### 4.1.9 - Print Format Builder (Video 156)
### 4.1.10 - Address Format (Video 157)

### 4.2 Program Modules
#### 4.2.1 - Accounts
##### 4.2.1.1 - Trial Balance (Video 158)
##### 4.2.1.2 - Payment request (Video 159)
##### 4.2.1.3 - Accounts receivable (Video 160)
##### 4.2.1.4 - Accounts payable (Video 161)
##### 4.2.1.5 - Bank reconciliation statements (Video 162)
##### 4.2.1.6 - Bank change summary (Video 163)
##### 4.2.1.7 - Bank guarantee (Video 164)
##### 4.2.1.8 - Fiscal rule (Video 165)
##### 4.2.1.9 - Budget (Video 166)
##### 4.2.1.10 - Budget Variance (Video 167)
##### 4.2.1.11 - Monthly Distrubtion  for Budgets (Video 168)
##### 4.2.1.12 - Period closing (Video 169)
#### 4.2.2 - Human Resources
##### 4.2.2.1 - Attendance (Video 170)
##### 4.2.2.2 - Employee Attendance Tool (Video 171)
##### 4.2.2.3 - Upload Attendance (Video 172)
##### 4.2.2.4 - Leave Application (Video 173)
##### 4.2.2.5 - Leave type (Video 174)
##### 4.2.2.6 - Leave Allocation (Video 175)
##### 4.2.2.7 - Leave Allocation Tool (Video 176)
##### 4.2.2.8 - Leave Block List (Video 177)
#### 4.2.3 - Stock
##### 4.2.3.1 - Product Attributes (Video 178)
##### 4.2.3.2 - Product Variants (Video 179)
##### 4.2.3.3 - Stock Reconciliation (Video 180)
A reconciliation allows you to enter the items that have been physically counted or observed
in a warehouse on a specific date, and an account to cost or expense the items not found. You
can also specify the cost center for this particular entry.

Each line lists the item, the warehouse and the amount actually verified in the warehouse.
ERPNext will then fetch the valuation rate (or you may enter it yourself ?).

Once the DocType has been Validated, it will post corresponding GL Entries and Stock entries.

You can make as many stock reconciliations as necessary.
##### 4.2.3.4 -  Packing List (Video 181)
##### 4.2.3.5 - Series Numbering (Video 182)
##### 4.2.3.6 - Lot Number (Video 183)
#### 4.2.4 - Buying
##### 4.2.4.1 - Inviting suppliers to the ERPNext portal  for your Company (Video 184)
When you create a quotation request, you may invite the supplier to your portal to make an offer for the request.

##### 4.2.4.2 - Entering supplier quotation on your ERPNext portal (Video 185)
#### 4.2.5 - Selling
##### 4.2.5.1 - Shipping Rule (Video 186)
##### 4.2.5.2 - Sales Analytics (Video 187)
##### 4.2.5.3 - Customer loyalty (Video 188)
#### 4.2.6 - CRM (Customer Resource Management)
###### 4.2.6.1 - SMS Entry (Video 189)
###### 4.2.6.2 - SMS Settings (Video 190)
##### 4.2.7 - Manufacturing
##### 4.2.7.1 - Open Production Orders(Video 191)
##### 4.2.7.2 - Production Orders in Progress (Video 192)
##### 4.2.7.3 - Delivered products from Production Orders (Video 193)
##### 4.2.7.4 - Completed Production Orders (Video 194)
##### 4.2.7.5 - Production Analysis (Video 195)
#### 4.2.8 - Projects
##### 4.2.8.1 - Daily work hour summary (Video 196)
##### 4.2.8.2 - Precise stock measurement (Video 197)
##### 4.2.8.3 - Gannt chart NO VIDEO
This report shows the tasks overlayed in a calendar to visualize the required time to complete the task.

You may update the progress of the task (%) form the Gantt chart

Task dependency on another will be shown with an arrow.

#### 4.2.9 - Assets
##### 4.2.9.1 - Asset movement (Video 198)
##### 4.2.9.2 - Asset depreciations and pending balance (Video 199)
### 4.3 Module 4 Conclusion
Conclusion and summary of what we saw here.

## Module 5: Becoming an expert
What to expect
### 5.1 Expert level operation
#### 5.1.1 Application installer (Video 200)
#### 5.1.2 Email alerts (Video 201)
#### 5.1.3 Standardized response (Video 202)
#### 5.1.4 Feedback trigger (Video 203)
#### 5.1.5 Email summary (Video 204)
#### 5.1.6 Account payment vía gateway (Cuenta pasarela de pago) (Video 205)
#### 5.1.7 - Check printing template (Video 206)
#### 5.1.8 - Programming advanced invoice templates (Video 207)
### 5.2 Program modules
#### 5.2.1 - Accounts
##### 5.2.1.1 - Report Gross profit (Video 208)
##### 5.2.1.2 - Purchase Invoice Trends (Video 209)
##### 5.2.1.3 - Sales Invoice Trends (Video 210)
##### 5.2.1.4 - Trial Balance for Party (Video 211)
##### 5.2.1.5 - Payment Period Based on Invoice Date (Video 212)
##### 5.2.1.6 - Sales Partner Comission (Video 213)
##### 5.2.1.7 - Item-wise Sales Register (Video 214)
##### 5.2.1.8 - Item-wise Purchase Register (Video 215)
##### 5.2.1.9 - Accounts Receivable Summary (Video 216)
##### 5.2.1.10 - Accounts Payable Summary (Video 217)
##### 5.2.1.11 - Sales Payment Summary (Video 218)
##### 5.2.1.12 - Creating and Saving Personalizados Reports (Video 219)
#### 5.2.2 - Human Resources
##### 5.2.2.1 - Appraisal (Video 220)
##### 5.2.2.2 - Appraisal Template (Video 221)
##### 5.2.2.3 - Team Updates (Video 222)
##### 5.2.2.4 - Training Program (Video 223)
##### 5.2.2.5 - Training Event (Video 224)
##### 5.2.2.6 - Training Result(Video 225)
##### 5.2.2.7 - Training Feedback (Video 226)
##### 5.2.2.8 - Loan Type (Video 227)
##### 5.2.2.9 - Employee Loan Application (Video 228)
##### 5.2.2.10 - Employee Loan (Video 229)
##### 5.2.2.11 - Vehicle (Video 230)
##### 5.2.2.12 - Vehicle Log (Video 231)
##### 5.2.2.13 - Reports
###### 5.2.2.13.1 - Employee Birthday (Video 232)
###### 5.2.2.13.2 - Employee Leave Balance (Video 233)
###### 5.2.2.13.3 - Employees working on a holiday (Video 234)
###### 5.2.2.13.4 - Employee information (Video 235)
###### 5.2.2.13.5 - Salary Register (Video 236)
###### 5.2.2.13.6 - Monthly Attendance Sheet (Video 237)
###### 5.2.2.13.7 - Vehicle Expenses (Video 238)
#### 5.2.3 - Stock
##### 5.2.3.1 - Delivery Trip (Video 239)
##### 5.2.3.2 - Quality Inspection (Video 240)
##### 5.2.3.3 - Landed Cost Voucher (Video 241)
##### 5.2.3.4 - Instalation Note (Video 242)
##### 5.2.3.5 - Serial Number Service Contract Expiry (Video 243)
##### 5.2.3.6 - Serial Number Status (Video 244)
##### 5.2.3.7 - Serial Number Warranty Expiry (Video 245)
##### 5.2.3.8 -  Stock Reports
###### 5.2.3.8.1 - Stock Ledger (Video 246)
###### 5.2.3.8.2 - Stock Balance (Video 247)
###### 5.2.3.8.3 - Stock Projected Quantity (Video 248)
###### 5.2.3.8.4 - Stock Summary (Video 249)
###### 5.2.3.8.5 - Stock Ageing (Video 250)
###### 5.2.3.8.5 - Item Price Stock (Video 251)
##### 5.2.3.9 - Additional reports
###### 5.2.3.9.1 - Ordered Items To Be Delivered (Video 252)
###### 5.2.3.9.2 - Purchased Order Items To Be Received(Video 253)
###### 5.2.3.9.3 - Item Shortage Report (Video 254)
###### 5.2.3.9.4 - Requested Items To Be Transferred (Video 255)
###### 5.2.3.9.5 - Batch-Wise Balance History (Video 256)
###### 5.2.3.9.6 - Estado de caducidad de lote de productos (Video 257)
###### 5.2.3.9.7 - Precios de los productos (Video 258)
###### 5.2.3.9.8 - Nivel recomendado de reabastecimiento de producto (Video 259)
###### 5.2.3.9.9 - Detalles de la variante del articulo (Video 260)
#### 5.2.4 - Buying
##### 5.2.4.1 - Items to Be Requested (Video 261)
##### 5.2.5.2 - Requested Items To Be Ordered (Video 262)
##### 5.2.5.3 - Material Requests for which Supplier Quotations are not Created (Video 263)
##### 5.2.5.4 - Item-Wise Purchase History (Video 264)
##### 5.2.5.5 - Supplier Addresses And Contacts (Video 265)
#### 5.2.5 - Selling
##### 5.2.5.1 - Lead Details (Video 266)
##### 5.2.5.2 - Customer Addresses and Contacts (Video 267)
##### 5.2.5.3 - Ordered Items to Be Delivered (Video 268)
##### 5.2.5.4 - Sales Person-wise Transaction Summary (Video 269)
##### 5.2.5.5 - Item-Wise Sales History (Video 270)
##### 5.2.5.6 - Bill Of Materials (BOM) Search (Video 271)
##### 5.2.5.7 - Inactive Customers (Video 272)
##### 5.2.5.8 - Available Stock For Packing Items (Video 273)
##### 5.2.5.9 - Pending SO Items For Purchase Request (Video 274)
##### 5.2.5.10 - Customer Credit Balance (Video 275)
##### 5.2.5.11 - Custom Reports for Selling (Video 276)
#### 5.2.6 - CRM (Customer Resource Management)
##### 5.2.6.1 - Lead Details (Also seen in Selling) (Video 277)
##### 5.2.6.2 - Sales Funnel (Video 278)
##### 5.2.6.3 - Prospects Engaged But Not Converted (Video 279)
##### 5.2.6.4 - Minutes To First Response for Opportunity (Video 280)
##### 5.2.6.5 - Inactive Customers (Video 281)
##### 5.2.6.6 - Campaign Efficiency (Video 282)
##### 5.2.6.7 - Lead Owner Efficiency (Video 283)
#### 5.2.9 - Assets
##### 5.2.9.1 - Asset Movement Tool (Video 284)
##### 5.2.9.2 - Asset Depreciation Ledger (Video 285)
#### 5.2.10 - Maintaining the Software
##### 5.2.10.1 - Accesing the Command Line (Video 286)
##### 5.2.10.2 - Terminal and/or iTerm (Video 287)
##### 5.2.10.3 - Creating snapshots (VirtualBox, or otther options) (Video 288)
##### 5.2.10.4 - Remote Server Installation (Video 289)
##### 5.2.10.5 - Setting up SSL with Let's Encrypt (Video 290)
##### 5.2.10.6 - The ERPNext folder: Frappe-Bench (Video 291)
##### 5.2.10.7 - Updating the Application (Video 292)
##### 5.2.10.8 - GitHub & Version control (Video 293)
##### 5.2.10.9 - Developer mode and development console on the browser (Video 294)

### 5.3 Module 5 Conclusion

## Module 6: Manufacturing (Missing or advanced topics)
These topics have been reviewed, but perhaps a couple of example videos explaining an entire workflow or more advanced concepts or cases.
Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/manufacturing)

## Module 7: Services (Missing or advanced topics)
These topics have been reviewed, but perhaps a couple of example videos explaining an entire workflow or more advanced concepts or cases.
Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/projects)

## Modulo 8: Point of Sale
## 8.1 - POS
### 8.1.1 - How it works
### 8.1.2 - Configuring POS
### 8.1.3 - How to make a POS sale
### 8.1.4 - Using without Internet access - Local data storage

Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/accounts/point-of-sale-pos-invoice)

## Module 9: Stock Module Additional Topics
## 9.1 - Stock and Distribution topics
### 9.1.1 - Purchase returns
### 9.1.2 - Sale return
### 9.1.3 - Sample Inventories

Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/stock)

## Module 10: Education
Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/education)

### 10.1 - Introduccion - ERPNext for schools - (Video 119)
https://youtu.be/f6foQOyGzdA
###10.2 - Student Application - (Video 120)
https://youtu.be/l8PUACusN3E
### 10.3 - Students Management - (Video 121)
https://youtu.be/nIUsbl0rEE0
### 10.4 - Programs & Courses - (Video 122)
https://youtu.be/1ueE4seFTp8
### 10.5 - Program Enrollment - (Video 123)
https://youtu.be/5nxWYBRHY_o
### 10.6 - Instructor - (Video 124)
https://youtu.be/rVqQYS1_02k
### 10.7 - Student Groups (Sections) - (Video 125)
Students assigned to a course
https://youtu.be/5K_smeeE1Q4
### 10.8 - Course Scheduling - (Video 126) 
Agenda for each instructor and students
https://youtu.be/iy-DBV9jI-A
### 10.9 - Student Attendance - (Video 127)
https://youtu.be/j9pgkPuyiaI
### 10.10 - Student Leave Application - (Video 128)
https://youtu.be/NwwH5t-NKBE
### 10.11 - Assessment Criteria and Grading - (Video 129)
https://youtu.be/t8ZDDq4qtIk
### 10.12 - Assessment Group - (Video 130)
A group that is assesed, a hierarchy of evaluations done in an academic year.
https://youtu.be/I1T7Z2JbcP4
### 10.13 - Assessment Plan - (Video 131)
Schedules an assessment for a specific groups of students in a specific course.
https://youtu.be/Q9CzzoYb_Js
### 10.14 - Assessment Result and Assessment Result Tool - (Video 132)
The result of the assessments registers the score of the student in a specific evaluation. The assesment result tool, allows you to enter several student results at the same time, based on an assesment plan.
https://youtu.be/U8ZRB8CM-UM
### 10.15 - Fee Structure - (Video 133)
Category for fees and fee accounts ( The fee category is combined to calculate the total to be charged per student. (Monthly fee, yearly subscription fee, etc.)
https://youtu.be/_ZkvyVnWgYk
### 10.16 - Registro de Tarifas Masivo - (Video 134)
Allows you to enter multiple fees for student groups at the same time.
### 10.17 - Fee and Payment - (Video 135)
CHow to create a single fee per student. And how to register the payment receipt.
https://youtu.be/RfWOyjgxIZM

## Module 11: Agriculture
Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/agriculture)

### 11.1 Introduction to ERPNext for Agriculture
### 11.2 Production Units and Crop Management
### 11.3 Agriculture Demonstration
### 11.4 - Basic Use
#### 11.4.1 - Land Unit
#### 11.4.2 - Crop
#### 11.4.3 - Crop Cycle
#### 11.4.4 - Agricultural Labor

### 11.5 - Basic configuration of the Agriculture Module
### 11.5.1 - Location (Land Unit)

## Module 12: Healthcare
### 2.1 - Configuration and Setup
### 2.2 - Patient
### 2.3 - Patient Appointment
### 2.4 - Vital Signs
### 2.5 - Consultation
### 2.6 - Patient Medical Record
### 2.7 - Sample Collection
### 2.8 - Laboratory Test
### 2.9 - Invoicing
### 2.10 - Physician
### 2.11 - Physician Schedule
### 2.12 - Medical Code Standards

Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/healthcare)

## Module 13: Non Profits
### 13.1 - Membership
### 13.2 - Chapter
### 13.3 - Volunteer
### 13.4 - Donor
### 13.5 - Grant Application

Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/non_profit)

## Module 14: Hospitality
### 14.1 - Restaurant
### 14.2 - Restaurant Menu
### 14.3 - Restaurant Reservations
### 14.4 - Restaurant Order Entry
### 14.5 - Hotel Room

Refer to [original documentation to verify nothing is missing](https://erpnext.org/docs/user/manual/en/hospitality)

## Module 15: Contributing and Programming
### 15.1 - Contributing Translations
#### 15.1.1 - Access to the portal
#### 15.1.2 - Adding an unlisted language
#### 15.1.3 - Accesing the portal
#### 15.1.4 - Distributing the work: Print the messages for field interviews
#### 15.1.5 - Field notes, interviewing native speakers
### 15.2 - Contrubting regional chart of accounts
### 15.3 - Contributing ideas or improvement suggestions
### 15.4 - Contributing error logs
### 15.5 - Developing Apps
#### 15.5.1 - Before developing
	Check the forums to verify if there is a project already underway addressing the issue that you have.
	Ideally you may participate in this project.
#### 15.5.2 - Developing apps
##### 15.5.2.1 - How to create an application
##### 15.5.2.2 - How to use GitHub
##### 15.5.2.3 - Creating a development server instance from scratch using VirtualBox
* These steps will lead you through setting up a Virtual Machine with a Linux .iso until you have a working ERPNext server for local use
	* These instructions are based on what has worked for us.
	* This setup is only recommended for a server that will be used locally!
###### 15.5.2.3.1 - Download and install VirtualBox
1. Visit https://www.virtualbox.org/
2. Click the big blue button: "Download Virtual Box 5.x"
3. Select your operating system.
4. Install VirtualBox
5. Corra VirtualBox
###### 15.5.2.3.2 - Download Linux
I personally like to run my development servers in Linux Server. You might also wish to use [Ubuntu Desktop](http://releases.ubuntu.com/16.04/ubuntu-16.04.4-desktop-amd64.iso.torrent).
To avoid compatibility issues I recommend [64-bit Ubuntu 16.04 LTS server](http://releases.ubuntu.com/16.04/ubuntu-16.04.4-server-amd64.iso.torrent).
Visit the [Ubuntu page](https://www.ubuntu.com/download) to select the proper version for your needs.
I suggest you use a torrent manager, you will get very fast downloads. I personally use [μTorrent](http://www.utorrent.com/)
and on a 10Mb connection I get it downloaded in under 15 minutes.

1. Go to the [Ubuntu page](https://www.ubuntu.com/download) to select the proper version for your needs
2. Once you have selected what you need, you click on it to begin the download
3. The download will be a **.torrent** file.
4. If you double click on it or open your torrent manager, you will be able to add it to the torrent list
5. Make sure you start the torrent and let it seed some time after downloading
6. The result will be a **.iso** file which will be used to setup our Development server
###### 15.5.2.3.3 - Create a Virtual Machine
1. Open VirtualBox
2. The first time you run, a welcome screen will show
3. Click on **New** in the menu bar.
	* Name: **ERPNext-dev** or similar
	* Type: **Linux**
	* Version: **Ubuntu (64-bit)**
4. Click **Continue**
5. Configure the memory size. Ideally, **1024MB**
6. Click **Continue**
7. You will be asked to create a virtual Hard Disk, select **Create a virtual hard disk now**
	* The size will be suggested, but at least **8-10GB** should suffice.
8. Click **Create**
9. You will be prompted to select the file type for the virtual hard disk image.
	* **VirtualBox Disk Image** will be selected for you, if not, choose it
10. If you do not mind the space needed for the disk, select **Dynamically Allocated**
	* I use **Fixed Size**
11. You will be prompted for the name of the virtual hard disk file
	* I use: **ERPNext-dev-[description]**
12. Click on Create
13. A new disk will be created, and the appliance added to the left bar of VirtualBox.
###### 15.5.2.3.4 - Configure your Virtual Machine
1. Configure the Virtual Machine's networking by right clicking on it and selecting **Settings**
	* On the Network tab, under Adapter 1, select **Bridged Adapter**
	* Choose your current networking device (ideally, wehre the virtual machine can get an IP assigned by DHCP)
	* Click **OK**
2. Right click on Virtual Machine and select **Settings** again.
	* Select the **Storage** tab
	* Where it says **Controller: IDE** there is an **Empty** item with a CD icon. Click it.
	* On the right pane, under **Attributes** you will see a field called **Optical Drive**. Click on the **CD Icon** beside it.
	* A menu item will pop up, and one of them will say:  **Choose Virtual Optical Disk File**. Click on it.
	* Navigate to the folder where you downloaded the **.iso** file for Ubuntu and select it.
	* Click **Open**
	* You should now see the file oyu just choose under the **Controller IDE item**
	* Click **OK**
###### 15.5.2.3.5 - Start your Virtual Machine and install Linux
1. Select the Virtual Machine and click **Start**
2. A Linux startup welcome screen will pop up asking for your default language. Use arrows to choose your language. Press **ENTER** to confirm.
3. Select **Install Ubuntu Server** and press **ENTER**
4. Select the language for installation and for the default system. Select using arrow keys and press **ENTER**
5. Select your location and press **ENTER**
6.  Detect keyboard layout. Follow prompts and press **ENTER** when done. I usually end up with a "latam" auto-detected selection.
7. Now it will proceed to install and then detect some hardware.
8. It will ask for the hostname: **ERPNext-dev** or similar is fine. Press **ENTER**
9. It will ask for a user name: **James Bond** (or your choice). Press **ENTER**
10. It will ask for a user name for your account: **james** (or your choice) Press **ENTER**
11. It will ask for a password: **moneypenny** (or your choice) Press **ENTER**
12. It will ask you to re-enter the password to confirm: **moneypenny** (or your choice above) Press **ENTER**
13. It asks for encryption of home directory. Since this is *just* a simple development server, I answer **NO** here. Press **ENTER**
14. Confirm your time zone. Press **ENTER**
15. Partition the disk and configure LVM
	* Guided - use entire disk and set up LVM
	* Select the disk displayed automatically on screen and press **ENTER**
	* Select **YES** and Press **ENTER**
	* Select **Continue** and Press **ENTER**
	* Select **YES** and Press **ENTER**
16. Installation will run.
17. It will ask for a Proxy configuration if necessary. Highlight **Continue** with *TAB* and Press **ENTER**
18. It will ask you for automatic updates. I usually select **Install Security Updates Automatically**
18. It will ask for installation of some software packages, here I select:
	* **Samba file server** -  to access the files on my local network and work with my favorite editing software.
	* **Standard system utilities**
	* **OpenSSH** - to connect to the server from other machines in the network and run terminal commands
	* Press *TAB* to highlight **Continue** and Press **ENTER**
19. It will ask to setup GRUB boot loader. Choose **YES**. Press **ENTER**
20. When complete, it will show a message and you can highlight **Continue** and Press **ENTER
###### 15.5.2.3.5 - Configure Linux Server for root user and SSH access
1. Set root password
	You will be prompted for the password for your user that you entered during installation. Then enter the root password twice to confirm.
> ```sudo passwd root```

2. Enable root user
> ```sudo passwd -u root```

	* to disable in the future:

> ```sudo passwd -l root```
3. Switch to the root user
> ```su root```
4. Open the sshd_config file to setup SSH connections

> ```nano /etc/ssh/sshd_config```

5. Modify the following in the sshd_config file:
	* Remove the "#" before the **PermitRootLogin** switch and add a **yes** at the end of that line.
	*PermitRootLogin yes*
	* Add a no where it says: **RSAAuthentication yes** so it says: **RSAAuthentication no**
	* Add a no where it says: **PubkeyAuthentication yes** so it says: **PubkeyAuthentication no**
	* Add a yes and remove the "#" where it says: **PasswordAuthentication yes**
	* Press **CTRL + X**, **Y** and **ENTER**
>	NOTE: These settings are for a development server on your local network, never use these settings in a production server!
6. Restart the OpenSSH server to make changes active, by typing in the console
> ```service ssh restart```
or 
> ```sudo systemctl restart sshd.service```

7. Find your machine's IP Address by typing:
> ```ifconfig```
	* Where it says inet addr:xxx.xxx.xxx.xxx

8. Try connecting vía a network machine or your local host (the machine hosting the virtual machine) terminal using SSH

> ```ssh root@[ip_address_of_your_vm]```

###### 15.5.2.3.6 - Configure Linux Server Samba file sharing
1. Add users, primarily the root user
> ```smbpasswd -a root```
2. Configure the server by modifying the .conf file
> ```nano /etc/samba/smb.conf```
3. When open, scroll down to the shares definition section, close to **[printers]** section, and add these lines:
>
	[ERPNext-root]
	path = /
	valid users = root
	force user = root
	read only = no
	create mask = 0755
	guest ok = yes
4. Exit and Save with **CTRL + X**, **Y** and **ENTER**
5. While we are at this, we might as well make sure the hostname is properly configured, so that
	it will be properly announced on the network when being setup, regardless of the IP.
> ```nano /etc/hostname```	

Make sure the file has at least one line with the hostname you desire, less than 15 characters in length.

6. Exit and Save with **CTRL + X**, **Y** and **ENTER**
7. Restart your Samba server:
> ```service smbd restart```	
8. Test your configuration
> ```testparm```
9. Reboot the server to have the hostname announced on the local network, using:
> ```reboot```

>**DON'T Forget to snapshot at this point.
This will enable you to browse the files on any network computer and modify them.  I have a development
server setup separately and work from other computers in the network.
###### 15.5.2.3.6 - Install ERPNext
1. First, you will need to switch to the sudo user you configured during linux installation
> IMPORTANT!  ERPNext installation will fail if you install as root
> ```su james```

2. Make sure Python and some features of it are installed.
> ```sudo apt-get update```

> ```sudo apt-get install python-minimal && sudo apt-get install build-essential python-setuptools```
2. Now, change to the /home directory
> ```cd /home```
3. Download the installation script for Frappe /ERPNext
> ```sudo wget https://raw.githubusercontent.com/frappe/bench/master/playbooks/install.py```
4. Here, you might opt to install either the production or the development version.
	This choice is up to you, but I have found my workflow progresses faster working with a
	master Production instance of ERPNext. For ERPNext core features, a develop server is best.
>```sudo python install.py --production```
5. During installation you will be prompted for a Database password for root, and an Administrator password.
6. When successful and done, a message will show:
> Frappe/ERPNext has been successfully installed!
###### 15.5.2.3.7 - Configuring your bash profile
1. To make maintenance easier, you can configure a profile file to take you directly to the frappe-bench directory
> ```sudo nano ~/.bash_profile```	
2. Add the following line:
> ```cd /home/frappe/frappe-bench/```
3. Exit and Save with **CTRL + X**, **Y** and **ENTER**
###### 15.5.2.3.7 - Starting Bench and ERPNext
1. On the command line, once installed, you might have to start the frappe-bench.
> ```cd /home/frappe/frappe-bench/```	
2. Run the start command
> ```bench start```
##### 15.5.2.4 - Planning your app
##### 15.5.2.5 - Creating your app
Before you create your app, open [this page](https://octicons.github.com/) in your web browser and find out the name of the icon
you wish to use for your application.

You also need to pick a color for the icon background square, it can be either:
Standard HTML color name: **blue**
or
Hex color value in the form: **#000000**

Find some ideas here: [https://www.w3schools.com/colors/colors_names.asp](https://www.w3schools.com/colors/colors_names.asp)

You also need to figure out which license you will use to publish your application,
and jot down the keyword for the license.

Some ideas here: [https://help.github.com/articles/licensing-a-repository/](https://help.github.com/articles/licensing-a-repository/)

If you already have a server with an instance of ERPNext running, you also need the site
name for your instance of ERPNext.

From your Terminal or iTerm, using an SSH connection or directly.

1. Navigate to the Frappe-Bench folder
> ```cd /home/frappe/frappe-bench/```
2. Create the application
>```bench new-app [your_application_name]```

Example:
> ```bench new-app my-new-app```	

3. You will be prompted for

	* A simple, one line description of your application
	* Who is publishing the app
	* E-mail of app publisher
	* Application icon: **octicon octicon-[name]**
	* Application module color: **#000000**
	* License: **gpl-3.0**
4. Install the application to your site. Repeat command for any other site where you want the app
> ```bench --site [site_name] install-app [name_of_your_app] ```

Example:

> ```bench --site site1.local install-app my-new-app```

* Note: Currently, the app is installed, but no icon will show on the ERPNext desktop
	in the web browser until you create the first DocType!

5. Create your fist DocType
	* Open your web browser and type the server address where ERPNext is hosted.
	* Login
	* Once you are on the ERPNext desktop, click on the *Awesome Bar* on top, and type:
	**new DocType**
	* Press ENTER
	* A new DocType configuration page will open
	* I suggest you create a Configuration DocType for the application first.
		* In the *Is Single* field select **YES**
		* Name: **Configuration**
	* Click on **Save**
	
6. Enable developer mode in the terminal

> ```cd /home/frappe/frappe-bench/sites/[your_site_name]```

Then, open the site_config.json file to add the line that turns developer mode on:

> ```nano site_config.json```

Add the following line:

> ```"developer_mode": 1,```

Now, exit Save and confirm: **CTRL + X, Y, ENTER**

7. Find your app in the linux directories:
To modify your application, you can access the directory where the app files in the following
folder, and select the files, modify them, etc.

> ```cd /home/frappe/frappe-bench/apps/[name_of_your_app]```

8. Optional: Configure your application folder for tracking changes with GitHub
Once inside the directory, run the following commands:

> ```git init```

It will confirm, if successful, with:
**Initialized empty Git repository in /home/frappe/frappe-bench/apps/[name_of_your_app]/.git/**

9. Add files to the local git repository
This will add all the files currently in your folder, to the local git repository

> ```git add .```

10. Now, commit your changes
This prepares the changes and places them in the staging area from where they will be pushed.

> ```git commit -m "[Add a short memo of your choice here]"```

11. Only once: If you [haven't done so](https://help.github.com/articles/create-a-repo/), go to your remote repository on GitHub or other server, and 
	click on the copy link button on the top right of the repository.
	
> ```git remote add origin [URL_that_you_copied]```

This will set the default origin repository to push and pull from. You can verify it with:
> ```git remote -v```

You should get:
> origin  https://github.com/user/repo.git (fetch)

> origin  https://github.com/user/repo.git (push)

12. Finally, push your changes onto the remote repository

**Important: The following command assumes you have nothing in the remote repository yet!**
> ```git push -u origin master --force```

For all other pushes in the future, just use:

> ```git push origin master```

##### 15.5.2.6 - Programming with Python
##### 15.5.2.7 - Programming with JavaScript
##### 15.5.2.8 - Modifying Files (Video 254)
##### 15.5.2.9  - Modificando Reports - Query report (Example: Adding columns) (Video 255)
##### 15.5.2.10 - Creating Reports - Pages  (Example: Sales Analytics, vs. Sales Analytics 2.0) (Video 258)
##### 15.5.2.11 - Creating Records to be included with Your Application
Many times, your cusotm application does not need sophisticated functionality, but instead requires useful records to become available or seamlessly appear in the ERPNext instance. Sometimes the amount of data is beyond the Data Import Tool limit. In this case we can bypass the data import tool and simply include them as a default when installing the application.

As you develop your application, add the records for the required doctypes in the most practical manner available to you.

Modify your `hooks.py` so that the `fixtures = []` variable contains the DocType records you wish to include. For example, aside from the Custom Field or Custom Script that you already consider exporting, you wish to include a specific chart of **Accounts**, a set of **Cost Centers** and a bunch of **Item Groups**, then the line in `hooks.py` should read like this:

Before:
`fixtures = ["Custom Field", "Custom Script"]`

After:
`fixtures = ["Custom Field", "Custom Script", "Account", "Cost Center", "Item Group"]`

Save the file

Now, with the records neatly entered as you wish them, (and before making a commit and push to your git server), execute the following command on your development server:

cd /home/frappe/frappe-bench/ && bench export-fixtures

This command will create 5 .json files, one for each DocType, inside the `/home/frappe/frappe-bench/apps/[app-name]/[app-name]/fixtures/` directory of  your application, like this:

custom_field.json
custom_script.json
account.json
cost_center.json
item_group.json

These files will contain all the records that you saved previously, and awhen you install the application on any server, they will be automatically loaded. The user will not have to load them on their own.
##### 15.5.2.12 - Testing
Aside from the usual code >try > fail > recode > try again > succeed cycle, tests of the python scripts are crucial to ensure that the code is doing what it is supposed to do.  Within the DocType that you are creating, it is imperative to create that least these three test files:
test_[doctype-name].py
test_[doctype-name].js
test_records.json
The Python and JavaScript files contain assertions that use the functions you coded as well as local functions and variables to explicitly confirm that the function in the software is doing what it is supposed to do. This process dramatically increases the integrity of the software, and clarifies it for those who are evaluating or auditing the code.
##### 15.5.2.13 - Creating Documentation
##### 15.5.2.14 - Publishing your Application
##### 15.5.2.15 - Application Maintenance
#### 15.5.3 - Developing ERPNext core
##### 15.5.3.1 - How to work with GitHub for contribution to core
##### 15.5.3.2 - Sending a Pull Request

## Module 16: ERPNext Hub
## Module 17: Calendar and Contacts
## Module 18: Account Consolidation for parent, child, sister companies
## Module 19: [*Reserved*] SHS Application (Revelare)
SHS made application, currently in alpha (may 2018) with the objective to contribute this to ERPNext core
## Module 20: [*Reserved*] SHS Application (GEV)
SHS made application, currently in alpha (may 2018) with the objective to contribute this to ERPNext core
## Module 21: [*Reserved*] SHS Application (Facelec)
SHS made application, currently in Version 2.1.1 (may 2018). Regionalized application for generating electronic invoices in Guatemala
## Module 22: [*Reserved*] SHS Application (Accesos Bancarios)
SHS made application, currently in planning phase (may 2018). Regionalized application for:

* Accessing bank records
* Programming payments
* Authorizing payments
* Supplementing existing conciliation programming in ERPNext

## Module 23:  [*Reserved*] Pull exchange rate from Bank of Guatemala
This module pulls the exchange rate published by the National Bank of Guatemala and makes it available to ERPNext, automatically.
## Module 24: The basics on managing and naming your warehouses
Basado en el [artículo](https://www.skuvault.com/blog/warehouse-locations-labeling-mistakes) de [Arianna Thayer](https://www.skuvault.com/blog/author/arianna-thayer)

### How to organize your warehouses
Hablar del orden de su bodega puede ser algo aburrido, puesto que tiene otras cosas más importantes
que hacer. ¿Para que ordenarlas adecuadamente?

* Reducir tiempo en buscar, obtener y utilizar insumos
* Minimizar los errores
* Minimizar desperdicios
* Cumplir con normativas de certificaciones

La combinación de esto evidentemente resulta en una reducción de costos y mejores ventas,
 los cuales se trasladan directamente a su operación. Una bodega ordenada hace las tareas más faciles, rápidas y efectivas.
 Cumplir ocn una certificación ayuda en abrir más mercados.

Entonces, si desea mejorar su operación partamos desde los estándares aceptados para manejo de bodegas.
Estos estándares surgieron despues de muchas pruebas y errores en otras organizaciones a lo largo del tiempo.
Conforme el paso del tiempo, se ha llegado a un común acuerdo desde lo informal hasta una formalidad, a lo cual
se le llama *Estándar de la industria*. Aqui veremos los concéptos básicos que puede aplicar para
tener excelentes resultados desde el inicio.

Al administrar las ubicaciones de las bodegas adecuadamente, se podrá utilizar herramientas y sistemas
comúnmente utilizados como: obtención interactiva de objetos por fase ó ubicaciónes dinámicas.

Obtencion Interactiva de Objetos por Fase (OIOF): Interactive Wave Picking, le permite a la persona encargada
de obtener objetos en bodega, de hacer su ruta eficiente, desglosando el total de articulos que recogerá
en una sola lista que asegura que solo recorra una vez cada pasillo o estantería.  Si tengo 5 pedidos
con un total de 20 objetos, algunos de ellos repetidos, el sistema OIOF me desplegará la lista de tal manera que
pase recogiendo cantidades de objetos a obtener, para cuando retorne a mi punto de partida, ya los asigne a
los pedidos correspondientes.

https://www.skuvault.com/features/interactive-wavepicking.php
https://en.wikipedia.org/wiki/Wave_picking
https://www.skuvault.com/features
https://en.wikipedia.org/wiki/Warehouse_management_system

Ubicaciónes dinámicas: En un sistema de ubicación dinámica, se permite que la ubicación de los productos
cambie de posición en las ubicaciones de bodega. Un ejemplo de esto es que los productos más
comunes puedan ser almacenados mas cercanos a la ubicación donde se empacan o utilizan.

http://microchannel.com.au/company-blog/march-2015/warehouse-management-static-vs-dynamic-slotting
https://www.youtube.com/watch?v=31GfSd0oIzg

Ambas estructuras mencionadas arriba le permiten reducir el tiempo de obtención de los objetos.

### Terminology
Previo a sugerirle como nombrar sus bodegas, clarifiquemos la terminología.

**Location**: Un area designada y etiquetada en su bodega, en donde una persona va a obtener los objetos
para un pedido. Tipicamente se identifica con una serie de codigos alfanumericos (que pueden incluir codificacion en barra) que pueden usarse
para rápidamente registrar la salida o ingreso de un producto en sus sitema de administración de bodega (almacén)

**Bin**: Es cualquier tipo de almacenamiento *adentro* de uno o mas espacios o ubicaciones para
el producto almacenado. (Por ejemploi: Un contenedor de clavos, otro de tornillos, etc.). Esta es la ubicación mas específica
que se sugiere utilizar en una bodega. Ocasionalmente se puede intercambiar con el término **Ubicación**.

**Shelf**: El siguiente nivel de ubicación a la cual se le coloca nombre es el **Entrepaño** o **Fila**.
Este es el espacio horizontal que atraviesa la enteridad de la Estantería en donde se ubica.

**Rack**: (Also: **Unit** or **Section**) Se refiere a la seccion de unidades o modulos
que contienen Entrepaños para almacenar los productos. Dependiendo de la bodega, las **Estanterías** se pueden identificar
como una unidad entera a lo largo de un **Pasillo**, o como secciones de **Entrepaños** largos. Se puede imaginar
lo descrito como un montón de libreras alineadas en una fila, con cada librera en su propia **Estantería** dentro de
la fila de **Estanterías**.

**Aisle**: La siguiente forma de indicar ubicación es por **Pasillo**, el cual se
define como el espacio entre sus **Estanterías** por el cual se puede mover usted o su maquinaria de bodega (Montacargas, etc.)

Si deseamos ver una jerarquía de su bodega, lo lógico es entonces definirla de lo general a lo específico como:
#### General Location > Warehouse Group > Warehouse > Aisle > Rack > Shelf > Bin


### How to name your Warehouses
Para nombrar su bodega, asegúrese de elejir algo que le funcione, y sea consistente en el esquema que elijió.

Las mejores prácticas para nombrar sus bodegas es la siguiente:

1. Numere los **Entrepaños** del suelo hacia arriba. De esta forma, si necesita agregar 
	entrepaños, no tiene que volver a etiquetarlos. Por ejemplo, si tiene una **Estantería**
	con cuatro **Entrepaños**, siendo el superior etiquetado como **#1**, y el de hasta abajo como
	el **#4**, si desea agregar ubicaciones (**Entrepaños**), su nueva ubicación (supongamos 
	que es el **Entrepaño #5**) quedaría encima del **Entrepaño #1**. Evidentemente esto le complica todo.
2. Es recomendable que cuando desee utilizar numeración en las ubicaciones, utilice un 
	cero en todos los numeros inferiores a diez (Por Ejemplo: 01, 02, 03, etc.).  Esto le permite a su
	sistema leer las ubicaciones alfanuméricas codificadas en código de barras, correctamente. 
	Además, le simplifica la lectura a su personal, puesto que se acostumbran a leer dos dígitos siempre.
3. Sea consistente. Un sistema inconsistente de etiquetado le herá más dificil el trabajo a sus empleados.

Debido a que la variedad de productos que se almacenan es muy cambiante, en algunos casos se necesita
mucho detalle, y en otros se necesita menos detalle (Ej. Bodega que almacena neumáticos 
de vehiculo versus una que almacena componentes para computadoras)

#### Two methods

##### Serpentine
Experts suggest that you arrange your warehouse in serpentine fashion, which allows your staff
to move about in a snake or "S" like fashion by weaving in and out of the aisles to drop off or pick up the required items.
In cases where you use the *Interactive Wave Picking* methodology, it reduces the amount of time used 
to obtain all those items necessary to fullfill the requirements.

The structure would look like this:
![Estanteria-FS-Serpentina](/activos/imagenes/Estanteria-FS-serpentina.png)

##### Standard


# THIS DOCUMENT IS A WORK IN PROGRESS!
