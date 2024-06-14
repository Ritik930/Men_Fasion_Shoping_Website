# Men's Fashion Shopping Website

This is a simple men's fashion shopping website built with HTML, CSS, JavaScript, PHP, and SQL. The website allows users to log in, browse product categories, add products to the cart, and checkout.

## Project Structure

Men_Fashion_Shop/
├── css/
│   └── style.css
├── php/
│   ├── db.php
│   ├── cart-add.php
│   ├── cart-remove.php
│   ├── cart.php
│   ├── login_script.php
│   ├── logout_script.php
│   ├── products.php
│   ├── signup_script.php
│   └── success.php
├── index.php
├── login.php
├── signup.php
├── watch.php
├── tshirt.php
├── jeans.php
├── shoes.php
└── checkout.php

## Features

- User authentication (login and signup)
- Product browsing by categories (Watches, T-Shirts, Jeans, Shoes)
- Adding products to the cart
- Viewing cart items
- Checkout process

## Database Schema

The database contains the following tables:

- `users`: Stores user information
- `products`: Stores product details
- `cart`: Stores items added to the cart by users
- `orders`: Stores completed orders


## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/Men_Fashion_Shop.git
   cd Men_Fashion_Shop
   ```

2. **Database Setup:**
   
   - Create a database and import the schema provided above.
   - Update the database connection details in `php/db.php`.

3. **Run the Project:**

   - Ensure you have a local server set up (like XAMPP or WAMP).
   - Place the project files in the server's root directory.
   - Access the project through your web browser (e.g., `http://localhost/Men_Fashion_Shop/`).

## Usage

1. **Login or Signup:**
   - Navigate to the login page and either log in with existing credentials or sign up for a new account.

2. **Browse Products:**
   - Once logged in, you can browse products by category.

3. **Add to Cart:**
   - Add desired products to your cart.

4. **Checkout:**
   - Proceed to the checkout page to view and confirm your order.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License.
```

