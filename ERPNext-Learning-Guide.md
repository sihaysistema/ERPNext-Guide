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


### 1.2 Structure
The following course or tutorial is divided into 5 modules, which will enable you to master ERPNext.

Module 1: Introduction to ERPNext
Module 2: Basic usage
Module 3: Intermediate usage
Module 4: Advanced usage
Module 5: Becoming an expert

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
#### 2.1.2 Configure your user (Video 003)
##### 2.1.2.0 Configure your desktop icons (Video 004)
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
#### 2.2.7 - Manufacture
##### 2.2.7.1 - Bill of Materials (Video 034)
	For manufacture or subcontracting
#### 2.2.8 - Projects
##### 2.2.8.1 - Internal project with tasks and progress (Video 035)
#### 2.2.9 - Assets
##### 2.2.7.2 Asset category (Video 036)
##### 2.2.7.1 Creating an asset(Video 037)
#### 2.2.10 - Web Site
##### 2.2.10.1 - Creating a Web Page (Video 038)
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

TK #Pending a procedure writeup
1.5.2 - Remote server installation