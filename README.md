## E-commerce Application with MERN Stack and PayPal Integration
This is a E-commerce application developed using the MERN stack (MongoDB, Express.js, React, Node.js). The application allows users to browse products, manage their shopping cart, and complete purchases through integrated PayPal payment functionality. Key features include:


---

### Key Features:

1. **Product Management**:  
   - Admins can add new products.  
   - Admins can update existing products.  
   - Admins can delete products.

2. **User Authentication**:  
   - Secure login system for users.  
   - User registration functionality.  

3. **Shopping Cart**:  
   - Users can add products to their cart.  
   - Users can update product quantities in their cart.  
   - Users can proceed to checkout.

4. **Order Management**:  
   - Admins can view all customer orders.  
   - Admins can manage customer orders.

5. **PayPal Integration**:  
   - Secure PayPal integration for payment processing.  
   - Users can complete purchases via PayPal.

---

### Steps to Run the Code:

1. **Download the repository**:  
   Download the zip code or use the command:  
   ```bash
   git clone https://github.com/SHREYAS0712/E-commerce.git
   ```

2. **Install client dependencies**:  
   Navigate to the `client` folder and run:  
   ```bash
   cd client && npm install
   ```

3. **Navigate back to the root directory**:  
   ```bash
   cd ..
   ```

4. **Install server dependencies**:  
   Navigate to the `server` folder and run:  
   ```bash
   cd server && npm install
   ```

5. **Set up accounts**:  
   Create accounts for **PayPal** and **Cloudinary**.

6. **Configure API keys**:  
   Add your PayPal and Cloudinary API keys in the configuration files.

7. **Set PayPal mode**:  
   Choose whether PayPal will operate in **sandbox** or **live** mode.

8. **Add MongoDB connection**:  
   Insert your MongoDB connection string in the `server.js` file.

9. **Run the client application**:  
   Navigate to the `client` folder and start the application:  
   ```bash
   cd client && npm run dev
   ```

10. **Run the server application**:  
    Open another terminal, navigate to the `server` folder, and start the server:  
    ```bash
    cd server && npm run dev
    ```


And All SET!!
