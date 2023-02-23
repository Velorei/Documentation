# Site Best Friends <br/>Test Plan <br/>Version 1.0

|Site Best Friends|Version 1.0|
|---|---|
|Test Plan|23.01.2023|

# Revision history
|Date|Version|Description|Author|
|---|---|---|---|
|23.01.2023|1.0|Creating|Valeriia Dudenko|

# Table of Contents
1. Introduce
    1. Purpose
    2. Source data
    3. Scope
2. Conditions for testing
3. Testing strategy
 1. Testing types
    1. Functional testing
    2. Cross-browser testing
    3. Regression testing and verification of fixed defects
    4. Testing the design
4. Testing schedule
5. Final results
    1. Resume


# 1. Introduce
## 1.1 Purpose
The purpose of this test plan is to describe the testing process of Best Friends site (full URL http://opencart.qatestlab.net/). The document allows to get an idea of the planned work on project testing.

## 1.2. Source data
Best Friends - a site that allows users to buy products for pets, learn more about the company.

## 1.3. Scope
The purpose of testing Best Friends site is to check the correct operation of all its functions on different versions of browsers with typical use cases. A fraction of the time (20%) will be used to test atypical / potentially error-prone usage scenarios.
    
**The result of the testing process will be the following materials:**
* report of the testing team regarding the general state, giving the developers and managers of this product a picture of the site’s correct operation in various browsers;
* report of the results of testing the current coverage, typical use cases / browsers;
* documented bugs in the bug tracker of the customer;
Testing will be done manually, by the ad-hoc testing method from the perspective of the end user of the site.

# 2. Conditions for testing
The website should satisfy the user’s need for activities related to viewing products, ordering and buying, and newsletter subscription.

# 3. Testing strategy
The following test plan is formal, as understanding of the current state of the project is needed to build a detailed plan. The first run of the functional tests will give a clear idea of the level of stability of the system and the set of tests that will be performed in each configuration will be clearly defined.

This approach will give an opportunity to get a detailed report on the product being tested and to focus maximum attention on narrow places.

The customer will be provided with daily reports on the progress of testing, defects found, suggestions for improving the work of the product and its design. All detected defects will be reported to the customer's tracker as separate tickets for subsequent correction.

In the process of testing the Best Friends ad-hoc testing will be applied due to the lack of strict specification, as well as due to limited resources for the formalization of tests.

**Five stages of the testing process are planned:**
* the first stage is to analyze the technical requirements, develop a test plan, and run the functional tests partially; 
* second stage will be devoted to a detailed run of the functional tests with the detection and description of defects;
* at the third stage, cross-browser compatibility testing will be performed with a description of the defects found;
the fourth stage is to check the bugs fixed by the developers and conduct regression testing;
* the fifth stage is to test the product design with a description of the defects found. 
Thus, maximum detailing of the testing depth is achieved, which, in turn, allows to determine the spent resources more accurately, as well as allows project developers to correct defects at the earliest stages.

**OS, approved to testing:**
* MacOS Monterey 12.6
	
**Browsers, approved to testing:**
* Safari 16.0 
* Firefox 108.0.2
* Google Chrome 108.0.5359.124

The security testing and the stress testing are not conducted due to lack of testing time. 

## 3.1. Testing types
### 3.1.1 Functional testing
**Objective:**

Identify functional errors, inconsistencies with the requirements and expectations of the user through the implementation of standard as well as non-trivial test scenarios.

**Process description:**

**Registration / Authorization**

* User registration
* User authorization
* Password recovery
* Profile
* Profile editing
* Deletion of the account
* User logout from personal account
* Search
* Search by products, categories
* Management of products, categories using filters

**Product categories**

* Scrolling product cards
* Flipping product cards
* Adding products to the cart
* Adding products to the Wish List
* Quick viewing of product cards

**Product**

* Product sorting: by price, availability, manufacturer, characteristics
* Characteristics, description, product reviews tabs in the product card
* Displaying product information on the product page
* Product photo display on the product page
* The possibility of turning over the photo of the product
* Adding a specific product to the cart
* View the product in a different color and size

**Cart**

* Change a certain number of products for purchase on the product page
* Order without registration
* Go to the "Payment methods", "Shipping methods" and "Warranty information" links
* Order when fields are filled in correctly
* Ordering when the fields are filled in incorrectly
* Drop-out cart
* Display of all selected products in the cart
* Displaying the number of products
* Display of prices
* Display the amount to pay 
* Choosing a delivery method
* Choice of payment method
* Removing this product from the cart
* Display of the amount after removing the product from the cart
* Choice of delivery method
* Proceed to the payment of the product
* Banners
* Viewing special offers
* Viewing discounts and sales
* Go to the relevant pages

**Home page** 

* Correct zoom
* Return to the main page
* Information
* Sending an e-mail
* Cancellation / confirmation of the subscription
* Information about the store
* Contact information
* Call back
* Social
* Social networks
* Follow the links

### 3.1.2. Cross-browser testing

* Safari 16.0 
* Firefox 108.0.2
* Google Chrome 108.0.5359.124

### 3.1.3. Regression testing and verification of fixed defects

**Objective:**

Checking the changes made on the site in the order to make sure that the new version does not contain errors of the site

In the course of regression testing, the following types of tests will be conducted:

* Verification Tests
* Version testing
* Testing related functionality

### 3.1.4. Testing the design

**Objective:**
Verification of product design compliance with specifications

**Process description:**

* Registration form
* Personal account
* Cart page
* Site pages
* Product cards
* Main page of the site 
* Quick view of the product
* Drop-down shopping cart window 
* Checkout page
* Selected products page 
* Registration form 

# 4. Testing schedule

|Task|Workload|Start date|Expiration date|
|---|---|---|---|
|Making a test plan|5 hours|23.01.2023|23.01.2023|
|Test execution||||
|Test Analysis||||
|Summarizing||||

# 5. Final results
## 5.1. Resume
The final result of the testing should be the complete summary consequence of the testing process with the described defects and recommendations for the improvement of the product from the perspective of the end user.
