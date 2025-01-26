# Gadgets on Wheels

## Overview
**Gadgets on Wheels** is a full-stack web application developed to facilitate the online rental of electronic gadgets. Users can easily browse, select, and rent gadgets of their choice through a seamless online experience. The platform also features an admin panel for managing inventory and orders efficiently.

## Features

### User Features:
- **User Authentication:** Users can sign up and log in using their credentials.
- **Gadget Browsing:** Explore a variety of electronic gadgets available for rent.
- **Order Placement:** Users can place rental orders for selected gadgets.
- **Order History:** View past and ongoing orders.
- **User Profile Management:** Update personal information and rental preferences.

### Admin Features:
- **Inventory Management:** Add, update, and delete gadgets from the inventory.
- **Order Management:** Track and manage customer orders.
- **User Management:** View and manage registered users.

## Technologies Used

### Frontend:
- **HTML5** – Structure and content of the web pages.
- **CSS3** – Styling and layout of the website.
- **JavaScript** – Client-side interactivity and dynamic content.

### Backend:
- **PHP** – Server-side scripting for handling business logic and database interactions.

### Database:
- **MySQL** – Storage and management of user data, gadget inventory, and orders.

## Installation

### Prerequisites
Ensure the following are installed on your system:
- PHP (>=7.4)
- MySQL (>=5.7)
- Apache Server (XAMPP/LAMP/WAMP recommended)

### Steps to Install
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/gadgets-on-wheels.git
   ```
2. Navigate to the project directory:
   ```bash
   cd gadgets-on-wheels
   ```
3. Import the database:
   - Locate the `gadgets_on_wheels.sql` file.
   - Import it into MySQL using phpMyAdmin or command line:
     ```bash
     mysql -u root -p < gadgets_on_wheels.sql
     ```
4. Configure database connection:
   - Edit `config.php` and update the database credentials accordingly.

5. Start the server:
   ```bash
   php -S localhost:8000
   ```
6. Access the application in your web browser:
   ```
   http://localhost:8000
   ```

## Usage
- **For Users:**
  1. Sign up or log in.
  2. Browse available gadgets.
  3. Select a gadget and place an order.
  4. Track order status via profile.

- **For Admins:**
  1. Log in via the admin panel.
  2. Manage gadgets and inventory.
  3. Track and fulfill orders.

## Contribution
Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries or feedback, feel free to reach out:
- Email: support@gadgetsonwheels.com
- GitHub: [your-username](https://github.com/your-username)

---
Thank you for using **Gadgets on Wheels**!

