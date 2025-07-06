# Project: Contoso Powder Web Portal
 
## Overview
Contoso Powder is a demo web application for a powdered supplement subscription company. The site allows users to log in, browse a catalog of powdered supplements, add items to a shopping cart, and complete a mock checkout process. The backend uses mock data to simulate product listings and user interactions.
 
## Tech Stack
- Frontend: React with TypeScript  
- Backend: Node.js with Express  
- Styling: Fluent UI or Tailwind CSS  
- State Management: React Context or Redux Toolkit  
- Mock Data: In-memory JSON or static files  
- Authentication: Mock login flow (no real auth)
 
## Features
- User login (mocked)  
- Product catalog with 6 powdered supplement products  
- Product detail pages which show separate to the regular pages and should not just appear at the bottom of all web site pages
- Shopping cart with add/remove functionality  
- Checkout flow with order summary  
- Responsive layout using Fluent UI  
- Navigation bar with links to Home, Products, Cart, and Profile
- Beautiful look and feel for the web site, using trendy colors, centered design, everything aligned, and internet sourced imagery
- Make it UX friendly and look like in the Fluent design of the Microsoft brand, you can use https://www.microsoft.com as an example website.
- Create SVG images for products and create a JS file to convert these to PNG for use in the project
 
## User Flow
1. User lands on the login page and enters mock credentials  
2. Upon login, user is redirected to the product catalog  
3. User browses 6 products and views details  
4. User adds 2–3 products to the cart . When each item is added to the cart, there must be a user acknowledgement
5. User navigates to the cart and reviews selections  
6. User proceeds to checkout and sees a confirmation screen
 
## Mock Data
- There should be 6 sample products in the database. Generate these with a product name, product description, and product image as a PNG file.
 
## Detailed Code Generation
- Ensure the Vite entry script is in the index.html
- Ensure that index.tsx references styles from the root / and not from the current directory
- On the home page product related buttons "View" and "Add to cart" muyst be functional
- The profile page must have content
- Generate all of the code needed for the user flow above when asked
 
