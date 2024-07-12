Mobile E-Commerce App: Assignment 7
Design Approach
For this mobile e-commerce app, I made several design decisions to create a user-friendly experience:

Navigation:

I implemented navigation using React Navigation.
Users can access different sections of the app through a drawer menu or screen transitions.
Stack navigation handles product details and cart screens.
User Interface:

The UI follows a clean and minimalistic design.
Custom styles and colors maintain consistency throughout the app.
Product Display:

The home screen lists available products fetched from an external API.
I used a FlatList component for efficient rendering.
Product Details:

The ProductDetailScreen provides detailed information about a selected product.
Users can navigate to this screen from the product list.
Cart Management:

The CartScreen displays items added to the cart.
I manage cart state using React Context or Redux.
Data Storage:
Local Storage:

I leveraged AsyncStorage (a React Native feature) to store cart items locally.
When users add or remove items from the cart, I update the AsyncStorage data.
State Management:

I created a context (or Redux store) to handle cart state.
Functions for adding/removing items from the cart are included.
Cart data persists across app sessions.
Screenshots:

HomeScreen
![home](https://github.com/user-attachments/assets/699a7825-ab10-4aee-907d-818d38cafadf)


ProductDetailScreen
![productdetail](https://github.com/user-attachments/assets/26a12c88-09ba-4f73-a563-439f2a412811)


CartScreen
![cart ](https://github.com/user-attachments/assets/481cd9f8-0c03-44b6-9257-8bd60f530c15)


