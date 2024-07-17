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
 - [x] Refactor Add Controller files to Controllers folder ✅ 2024-07-12
 - [x] System.Text.Json and Newtonsoft.Json are libraries that achieve something similar. However System.Text.Json yields better performance, please use this library moving forward ✅ 2024-07-15
 - [x] Please simplify your controller methods, rather than having several parameters like in the following: public IActionResult AddToCart(int productId, int quantity, bool isIncrement), you may pass a CartItemDto instead. Then you can map into into an Entity class that Entity Framework can understand ✅ 2024-07-15
 - [x] Please implement the async/await pattern in your application following these guidelines: [https://github.com/davidfowl/AspNetCoreDiagnosticScenarios/blob/master/AsyncGuidance.md](https://github.com/davidfowl/AspNetCoreDiagnosticScenarios/blob/master/AsyncGuidance.md) ✅ 2024-07-17
	 - [ ] Repository
		 - [x] ProductRepository ✅ 2024-07-17
		 - [x] CartRepository ✅ 2024-07-17
		 - [x] CategoryRepository ✅ 2024-07-17
		 - [x] ProductCategoryRepository ✅ 2024-07-17
		 - [x] Repository ✅ 2024-07-17
		 - [x] UnitOfWork ✅ 2024-07-17
	 - [ ] Services
		 - [x] AzureBlobStorage ✅ 2024-07-17
		 - [x] CartService ✅ 2024-07-17
		 - [x] CategoryService ✅ 2024-07-17
		 - [x] HomeService ✅ 2024-07-17
		 - [x] ProductService ✅ 2024-07-17
	 - [ ] Controllers
		 - [x] CartController ✅ 2024-07-17
		 - [x] CategoryController ✅ 2024-07-17
		 - [x] HomeController ✅ 2024-07-17
		 - [x] ProductController ✅ 2024-07-17
 - [ ] Implement RabbitMQ

**Updates:** 
- Added Service for CartController 
- Added Service for CategoryController
- Added Service for ProductController
- Added Truncate for cards to have same height and search for products and category
- Refactor Controller

**Plans for the future**
- Implement a Blob Container -  Azure Storage Emulator (Research) - **DONE**
- Product can belong to one or more category - **DONE**
- Session Management - **DONE**
- Add documentation as stated on the exercise instruction - **IN PROGRESS**
- System.Text.Json and Newtonsoft.Json are libraries that achieve something similar. However System.Text.Json yields better performance, please use this library moving forward - **DONE**
- Please simplify your controller methods, rather than having several parameters like in the following: public IActionResult AddToCart(int productId, int quantity, bool isIncrement), you may pass a CartItemDto instead. Then you can map into into an Entity class that Entity Framework can understand - **DONE**
- Please implement the async/await pattern in your application following these guidelines: [https://github.com/davidfowl/AspNetCoreDiagnosticScenarios/blob/master/AsyncGuidance.md](https://github.com/davidfowl/AspNetCoreDiagnosticScenarios/blob/master/AsyncGuidance.md) - **DONE**
- Implement a pagination in home page for products

**Category Management:**
- [x] Create, update, and delete product categories. ✅ 2024-07-03
- [x] Display a list of categories on the website. ✅ 2024-07-03

**Product Listings and Details:**
 - [x] Display a paginated list of products with their images, names, prices, and brief descriptions. ✅ 2024-07-03
 - [x] Images should be coming from blob container. ✅ 2024-07-11
 - [x] Implement a product search feature allowing users to search for products by name or category. ✅ 2024-07-04
 - [x] Create a product details page that shows more information about a selected product. ✅ 2024-07-03
 - [x] A product can belong to one or more categories. ✅ 2024-07-11

**Shopping Cart:**
 - [x] Allow users to add products to their shopping cart. ✅ 2024-07-03
 - [x] Users can view and manage items in their cart, update quantities, or remove items. ✅ 2024-07-03
 - [x] Display the total cost of items in the shopping cart. ✅ 2024-07-03
 - [x] Please consider session management while navigating the site, so that shopping cart retains current items. ✅ 2024-07-04

**Github Repository for CheckOutChampion** 
https://github.com/c-inodeo/CheckOutChampion