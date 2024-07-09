**Tasks/In Progress**
 - [x] Refactor Code - add Service layer for each controller that existed business logic ✅ 2024-07-03
 - [x] Add Search functionality, can search by name or product category - in progress as of 03/07 ✅ 2024-07-03
 - [x] Add multiple tags for Category ✅ 2024-07-08
	 - [x] Challenges: had to update my database for it to be able to add multiple category, since the last one only accepts one category ✅ 2024-07-05
	 - [x] Added Product Category many-to-many relationship, Can update the product to have many categories ✅ 2024-07-08
	 - [x] Bug: Can't create a new product with multiple Category ✅ 2024-07-08
 - [x] Add Service for HomeController - to follow ✅ 2024-07-08
 - [x] Implement a session management while navigating the site, so that shopping cart retains current items. ✅ 2024-07-04
 - [x] mplement a blob container ✅ 2024-07-09
	 - [x] had challenges with this error after using **await containerClient.CreateIfNotExistsAsync();** ✅ 2024-07-09
		 - [x] Error Message: 'The REST version of this request is not supported by this release of the Storage Emulator. Please upgrade the storage emulator to the latest version. Refer to the following URL for more information: http://go.microsoft.com/fwlink/?LinkId=392237 ✅ 2024-07-09

**Updates:** 
- Added Service for CartController 
- Added Service for CategoryController
- Added Service for ProductController
- Added Truncate for cards to have same height and search for products and category

**Plans for the future**
- Implement a Blob Container -  Azure Storage Emulator (Research) - **DONE**
- Product can belong to one or more category - **DONE**
- Session Management - **DONE**
- Add documentation as stated on the exercise instruction

**Category Management:**
- [x] Create, update, and delete product categories. ✅ 2024-07-03
- [x] Display a list of categories on the website. ✅ 2024-07-03

**Product Listings and Details:**
 - [x] Display a paginated list of products with their images, names, prices, and brief descriptions. ✅ 2024-07-03
 - [ ] Images should be coming from blob container.
 - [x] Implement a product search feature allowing users to search for products by name or category. ✅ 2024-07-04
 - [x] Create a product details page that shows more information about a selected product. ✅ 2024-07-03
 - [ ] A product can belong to one or more categories.

**Shopping Cart:**
 - [x] Allow users to add products to their shopping cart. ✅ 2024-07-03
 - [x] Users can view and manage items in their cart, update quantities, or remove items. ✅ 2024-07-03
 - [x] Display the total cost of items in the shopping cart. ✅ 2024-07-03
 - [x] Please consider session management while navigating the site, so that shopping cart retains current items. ✅ 2024-07-04

**Github Repository for CheckOutChampion** 
https://github.com/c-inodeo/CheckOutChampion