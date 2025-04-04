

# e-commerce-application-follow-along



Key Features of the Project:

In this project, I will be building an E-Commerce app using the MERN stack (MongoDB, Express.js, React.js, Node.js). Here is what I will be learning and working on:



REST API Creation: I will learn how to build scalable APIs to manage users, products, and orders, and get hands-on experience with backend development.



User Authentication: I will implement secure login and registration for users, which is a crucial part of any app that handles sensitive data.

Database Schema Design: I will explore MongoDB to design data models that are efficient and scalable for an e-commerce platform.

Backend Development: I will set up a server with Node.js and Express.js to handle requests, API routes, and interact with the database.

Frontend with React: I will use React to build dynamic, user-friendly interfaces, like product lists and shopping carts.






### Milestone 2:

Key Achievements

Project Structure: Organized the project into frontend and backend directories for better maintainability. Backend set up with Node.js to handle server-side logic, and the frontend set up with React to build the user interface.
React Frontend Setup: Initialized a React app to manage the UI, allowing the e-commerce platform to be interactive.
Node.js Backend Setup: Configured a basic Node.js server to lay the foundation for upcoming API integrations and user authentication.
Tailwind CSS Configuration: Integrated Tailwind CSS for utility-first, responsive styling to enhance UI development speed.
Login Page Development: Designed and built a functional Login Page with form validation and styling using Tailwind.





### Milestone 3:

In this milestone, we focused on building the foundation for the backend of our e-commerce application. The key objectives were to set up a server, connect it to a database, and establish a solid folder structure to keep our code organized.

Backend Folder Structure: We created a structured hierarchy for organizing backend code. This includes dedicated folders for routes, controllers, models, and middleware. This structure will make it easier to scale the project as more features are added in future milestones.

Server Setup: We initialized a Node.js server using the Express framework. The server is now configured to handle API requests, and it listens on a designated port for incoming requests.

Database Connection: We integrated MongoDB into the project to store and manage data. The server is now connected to MongoDB, enabling efficient data storage and retrieval.

Error Handling: Basic error-handling mechanisms were added to ensure that the server can respond with clear error messages for better debugging and user feedback.





### Milestone 4:

In Milestone 4, we focused on enhancing the backend by creating a User Model, setting up a User Controller, and enabling file uploads using Multer. These features are key to handling user data and media effectively in the e-commerce app.

User Model: We created a User Model, which defines how user data is stored in the database. This includes fields such as name, email, and password. We used MongoDB schemas to design the structure and validation rules for each user.

User Controller: The User Controller was developed to manage user-related requests, such as creating a new user and retrieving user information. This controller acts as the manager that handles data processing and communication between the frontend and the database.

File Uploads with Multer: We integrated Multer to enable file uploads, allowing users to upload images (e.g., profile pictures). Multer manages the file storage and ensures that the files are saved securely in the backend.





### Milestone 5:

In Milestone 5, we focused on building the Sign-Up Page for the frontend, where users can register by entering their details. This page includes essential fields such as name, email, and password, providing a clean and user-friendly interface for registration.

Frontend UI Development: We designed the Sign-Up Page using HTML and CSS. The page was structured to be intuitive, ensuring users can easily input their data to create an account.

Form Validation: Form validation was added to ensure that user inputs are accurate and meet the required format. For example, we validated the email format and enforced a minimum password length to enhance security. This step helps avoid errors and ensures only valid data is submitted to the backend.

UI/UX Enhancements: The design is simple yet effective, allowing users to smoothly enter their details. We focused on making the form clean and responsive, ensuring it works across devices.





### Milestone 6:

In this milestone, we focused on building the foundation for the backend of our e-commerce application. The key objectives were to set up a server, connect it to a database, and establish a solid folder structure to keep our code organized.

Backend Folder Structure: We created a structured hierarchy for organizing backend code. This includes dedicated folders for routes, controllers, models, and middleware. This structure will make it easier to scale the project as more features are added in future milestones.

Server Setup: We initialized a Node.js server using the Express framework. The server is now configured to handle API requests, and it listens on a designated port for incoming requests.

Database Connection: We integrated MongoDB into the project to store and manage data. The server is now connected to MongoDB, enabling efficient data storage and retrieval.

Error Handling: Basic error-handling mechanisms were added to ensure that the server can respond with clear error messages for better debugging and user feedback.





### Milestone 7: Login Endpoint 📝

Create a login endpoint to authenticate users. Users provide their email/username and password. The backend compares the entered password (hashed with bcrypt) to the stored password. If valid, a JWT token is generated and returned for subsequent requests.

Dependencies: bcryptjs, jsonwebtoken.

Test via POST /api/auth/login with email and password in the request body.

Response: Success with a token, or error for invalid credentials.




### Milestone 8: Product Card Component 🌟

In this milestone, we focus on creating a reusable product card component for your e-commerce app. The goal is to showcase product details (e.g., name, image, price) in a visually appealing way, making it easy for users to browse products.

Steps Completed:
1. Card Component: Designed a reusable card that accepts product details as props.
2. Homepage Layout: Implemented a grid/flexbox layout to display multiple cards neatly.
3. Dynamic Rendering: Used array mapping to dynamically render cards for each product





### Milestone 9: Product Input Form 🌟

In this milestone, we focused on creating a frontend form for adding products to your e-commerce app. This form allows users to input detailed information about products, including multiple images, which will eventually be saved to a database and displayed on the product homepage.

Steps Completed:

Product Form: Built a form to input details like product name, description, price, category, and quantity.

Multiple Image Input: Added functionality for users to upload multiple images for each product.

Dynamic Data: Set up the form to eventually save the product data and display it dynamically on the product homepage.






### Milestone 10: Product Schema & Endpoint Creation

In this milestone, I created a Mongoose schema to define the structure for storing product data in MongoDB. The schema includes fields like name, description, price, and image URL, with proper validation to ensure data integrity (e.g., required fields, correct data types).

I also built a POST endpoint that receives product details, validates the input data, and stores it in the database. This ensures that only valid product information is saved, maintaining a clean and reliable database.

Additionally, I explored optional features like creating admin roles for restricted access to product uploads. This milestone strengthens the backend process of handling product data, making it ready for display on the frontend in future milestones.




### Milestone 11 🌟

In this milestone, we learned how to display products dynamically on the home page using data stored in MongoDB. We built an endpoint to fetch all the products and a frontend function to display them using a product card component.




### Milestone 12 - Created an endpoint that will send data by filtering with my mail and send data from mongodb. It will receive data at frontend and will display that data dynamically using product card created earlier.

### Milestone 13 - Updating the product
This Express.js route updates a product in a MongoDB database, handling file uploads using multer. It validates input data, updates product details (name, description, category, tags, price, stock, email), and modifies images if new ones are uploaded. Errors are handled with appropriate status codes, ensuring robust error management and smooth database updates.

### Milestone 14 - Delete the product
This e-commerce application is built with Node.js, Express, MongoDB, and React, providing full-stack functionality for product management. It includes RESTful APIs for adding, updating, and deleting products. The /delete-product/:id endpoint allows secure product removal. Error handling ensures reliability. Ideal for scalable and dynamic online stores.


### Milestone 15 - Added Nav bar
Added the nav component to all the pages and make the navigations to all this pages smooth and easy. Nav component with links to all pages: -Home -My-products -Add product -cart


### Milestone 16 - Added new page to display each product.
Added add quantity and add to card button.

### Milestone 17 - Updated the user schema to store cart products .
Created an end point to receive the product details and store in database.

### Milestone 18 - Created an endpoint to receive request from cart page.
Created an backend endpoint to fetch all the products inside cart with user mail.

### Milestone 19- Cart Page with Quantity Update
   -Create a Cart Page that displays products inside the cart using the endpoint built in Milestone 18.

   -Implement Quantity Controls for each product, allowing users to increase or decrease quantity using + and - buttons.

   -Build Backend Endpoints to update product quantity in the cart.

   -Update the README with a short guide on using the new API endpoints.


### Milestone 20- User Profile & Data Sharing
   -Create a Backend Endpoint to send all user data via email.

   -Develop a Profile Page in the frontend to display user details.

   -Display Profile Photo, Name, Email, and Addresses on the profile page.

   -Ensure Secure Data Handling while fetching and sending user information.

### Milestone 21: Address Form
Created a frontend form to collect address details.

Captured Country, City, Address1, Address2, Zip Code, Address Type.

Implement form validation and dropdowns for selection.

📌 Implementation

Create AddressForm.jsx component.

Use controlled inputs with validation.

Style and structure for a user-friendly UI.

### Milestone 22: Store Address in User Profile
Added a new POST /api/user/address endpoint.

Stores user address in the database under the User model.

Validates user existence before saving the address.

Handles errors like missing data, invalid user, and server issues.

### Milestone 23 🎯
In this milestone:

✅ Add a "Place Order" button inside the cart.

✅ Create a "Select Address" page to display all saved addresses and allow users to choose a delivery address.

✅ Write a Mongoose schema to store order details.


### Milestone 24 🎯
In this milestone:

✅ Create an Order Confirmation page.

### Milestone 25 📝
An API endpoint was created to receive product details, user email, and address.

The user ID is retrieved using the provided email.

Separate orders are stored for each product with the same address in the MongoDB orders collection.

The implementation follows the existing order schema and ensures data integrity.

### Milestone 26 📝
An API endpoint was created to receive the user's email.

The user ID is retrieved using the provided email.

Using the retrieved _id, all orders associated with the user are fetched.

The response contains all orders belonging to the user.

### Milestone 27: My Orders Page
 
 Welcome to Milestone 27! 
 
 In this milestone, we focused on creating the frontend page that displays all user orders.
 
 
### Milestone 28: Cancel Order Feature
Welcome to Milestone 28!

In this milestone, we focused on adding a cancel order feature to the my-orders page and creating a backend endpoint for handling order cancellations.

 ### Milestone 29📝
 Created a PayPal Developer Account and logged into the PayPal Developer Dashboard.
 
 Located the Client ID in the sandbox accounts and saved it in the project.
 
 Updated the Order Confirmation Page to include two payment options:
 
 Cash on Delivery (COD)
 
 Online Payment
 
 Implemented radio buttons to toggle between COD and Online Payment.
 
 Set up logic so that PayPal buttons only appear when the Online Payment option is selected.

### Milestone 30📝
Implemented online payment using PayPal API using the client key you created earlier.

Downloaded NPM package called react-paypal-js that will provide an component called PayPalScriptProvider which will display online payment methods like credit or debit card etc.

# Milestone 31: Implementing Global State Management with Redux

Welcome to Milestone 31! 🎯 In this milestone, we focus on implementing global state management using Redux in a React application. By the end of this milestone, you will learn how to use Redux for managing global states like storing a user's email across various components.


### Milestone 32 🎯
Implemented Redux for global state management, enabling seamless state access across all pages.


### Milestone 33 🎯
Implemented JWT authentication with tokens stored in cookies for secure user sessions.

# Milestone 34: Implementing Authentication with JWT

Milestone 34 covers JWT validation using cookies for secure authentication. The token is extracted from the browser cookie, sent to the server, and verified via middleware. If valid, access is granted; otherwise, it is denied. This ensures only logged-in users can access protected pages, strengthening security and session management.

# Milestone 35: Implementing Protected Routes with JWT

Milestone 35 focuses on deploying your project. You'll deploy the backend using a hosting service, obtain the deployment link, and update the frontend to use it instead of localhost. Then, you'll deploy the frontend and ensure both parts work seamlessly. By the end, you'll have a fully deployed and functional website.
