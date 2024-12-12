# E-Mart Management System

The E-Mart Management System is a comprehensive application designed to streamline operations in a retail environment. The system includes functionalities for login authentication, user registration, product and order management, and automated email notifications for customer communication.

---

## Features

1. **Login and Registration System**
   - Secure login with username and password.
   - User registration with validation and security questions.
   - Forgot password functionality for password recovery.

2. **Product and Inventory Management**
   - Add, update, delete, and search products.
   - Manage categories and expiry dates for inventory.

3. **Order Management**
   - Add and update customer orders.
   - Calculate subtotal, tax, and total amounts.

4. **Email Notifications**
   - Send email notifications with purchase details to customers.
   - Option to attach PDF bills in emails.

5. **Graphical User Interface (GUI)**
   - Easy-to-use GUI using Tkinter.
   - Dynamic forms for user interaction.

---

## Installation

### Prerequisites
- Python 3.x
- Required Python libraries:
  - `tkinter`
  - `Pillow`
  - `smtplib`
  - `mysql-connector-python`
  - `pdf-mail`

### Steps to Install
1. Clone this repository:
   ```bash
   git clone https://github.com/TusharFodse/StoreManagement.git
   ```

2. Navigate to the project directory:
   ```bash
   cd e-mart-management-system
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Configure your MySQL database with the provided scripts to set up the `store` database and tables.

---

## Usage

### Starting the Application
1. Run the `login7.py` file to start the application:
   ```bash
   python login7.py
   ```

2. Use the GUI to log in, register users, and manage products and orders.

### Sending Emails
- Configure email credentials in `sendingMail.py`.
- Ensure that the Gmail account used allows less secure app access or has an app password enabled.

---

## File Structure

- `login7.py`: Main entry point for the application, handles user authentication.
- `sendingMail.py`: Handles email functionality, including sending bills.
- `store.py`: Manages store operations, including product and order management.

---

## Security

- Ensure sensitive credentials like email passwords are stored securely (use environment variables or secret managers).
- Enforce strong password policies for user accounts.

---

## Contributions

Contributions are welcome! Please submit a pull request or raise an issue to report bugs or request features.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact

For questions or feedback, please contact [tusharfodse@gmail.com].


