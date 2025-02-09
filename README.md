 E-commerce Website

This is a full-stack e-commerce website built using React JS, MongoDB, Express JS, and Node JS. The platform provides users with a seamless shopping experience, offering features like user authentication, product listings, shopping cart functionality, and order management. 

Note: This is a PRactive project from a YouTube channel and is intended for learning purposes to practice building full-stack applications.

![Screenshot 2025-01-16 000814](https://github.com/user-attachments/assets/11c1ac72-2e03-453b-9fa7-299ebd3f6b46)


 Tech Stack

- Frontend: React JS
- Backend: Node JS, Express JS
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)
- Other Tools: Axios (for API calls), bcrypt (password hashing)

 Features

- User Authentication: Users can sign up, log in, and manage their profile.
- Product Listings: Browse a wide range of products, view product details, and search by category.
- Shopping Cart: Add items to the cart, update quantities, and proceed to checkout.
- Order Management: Users can view their past orders and track their order status.
- Admin Panel: Admin users can add, update, or remove products from the store.

 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/VaishnaviiMishra/E-commerce.git
   ```

2. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```

3. Install dependencies for the frontend:
   ```bash
   cd frontend
   npm install
   ```

4. Set up environment variables:

   - Create a `.env` file in the root of both the backend and frontend folders.
   - Add the following variables to the backend `.env`:
     ```
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

   - Add the following variables to the frontend `.env`:
     ```
     REACT_APP_API_URL=http://localhost:5000
     ```

5. Run the application:

   - Start the backend server:
     ```bash
     cd backend
     npm start
     ```

   - Start the frontend development server:
     ```bash
     cd frontend
     npm start
     ```

6. Open the application in your browser at `http://localhost:3000`.

 Usage

1. **Sign Up / Log In**: Create an account or log in to start shopping.
2. **Browse Products**: Explore the products by categories or search bar.
3. **Add to Cart**: Select the products and add them to the shopping cart.
4. **Checkout**: Go to the checkout page, enter shipping details, and place an order.

 Screenshots

(Include screenshots of key pages like home page, product page, and cart)

 Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

 Acknowledgments

- Inspired by the modern e-commerce platforms
- Special thanks to the open-source community for providing libraries and tools used in this project.
- This project was developed as part of a PRactive course from a YouTube channel for learning and practice purposes.

