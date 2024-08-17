# React E-commerce App Assignment

## Objective:
Students are tasked with building the front end of an e-commerce application using React. The app will involve user authentication, product listing, a shopping cart, and a checkout process. Relevant public APIs should be utilized to fetch product data.

## Requirements:

### User Authentication:

#### Sign-Up Page:
- Implement a sign-up page where new users can create an account.
- Upon sign-up, the username and password should be stored in local storage.

#### Login Page:
- Implement a login page where users can enter their credentials.
- Authenticate the user by checking the stored username and password in local storage.
- On successful authentication, redirect the user to the home page.

### Home Page (Product Listing):
- Fetch product data from a public API (use Dummy JSON API or similar).
- Filter the products to display only smartphones, laptops, and mobile accessories.
- Display the filtered products as cards, using the Figma design guide for layout and style.
- Each product card should include an image (use the `thumbnail`, `title`, `brand`, `price` fields from the JSON data) and other relevant details.

### Product Details Page:
- On clicking a product card, navigate to a detailed product page.
- Display detailed information about the selected product as per the Figma design (See the `Item-View` page in figma).

### Shopping Cart:
- Implement a shopping cart using React's Context API.
- The cart should be able to:
  - Add items.
  - Remove items.
  - Update the quantity of items.
- Cart data should be persistent across the app using the Context API.

### Cart Page:
- Create a cart page that displays the current items in the cart, fetched from the Context API.
- Allow users to add or delete items directly from this page (See the `Cart` page in figma).

### Checkout Process:
- On clicking the "Checkout" button in the sidebar, navigate to the checkout page.
- The checkout page should display the cart items and allow users to add an address and payment method.
- Implement "Add Address" and "Add Card" sections, updating the relevant information on the checkout page.
- Ensure the checkout flow follows the design guide.
- On click of buttons it should lead user to respective pages (Hint: Search up `useNavigate` hook in the react-router-dom library. 

## Design:
- Follow the provided Figma design file for all pages (Sign-Up, Login, Home, Product Details, Cart, Checkout).
- Ensure the app is responsive and user-friendly.

### [Figma Design File Link](https://www.figma.com/design/JAb0jDJx55BFmKpgOYvEX4/E-Commerce-Store---Final-Project?node-id=0-1&t=buT9nzwYIXxTIa7P-1) 

## Notes:
- Use local storage to handle user authentication.
- Leverage the Context API to manage cart state across the application.
- Make sure to filter and display only the required categories of products (smartphones, laptops, mobile accessories).
- Pay attention to details in the Figma design for a polished user interface.

## Submission:
- The assignment should be submitted by **30th August**.
- Ensure your code is clean, well-commented, and follows best practices.
