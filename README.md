# E-commerce Platform

## Overview
This project is a comprehensive e-commerce platform built using Django for the backend and React for the frontend. It provides a seamless shopping experience with a wide range of functionalities including a shopping cart, payment integration, product rating and review system, and an admin area for managing customers, products, and orders.

## Features
- **Full-Featured Shopping Cart**: Supports PayPal and credit/debit card payments for secure and diverse payment options.
- **Product Rating & Review System**: Allows customers to provide feedback and rate products.
- **Admin Area**: Facilitates efficient management of customers, products, and orders.
- **Advanced Product Features**: Includes search, carousel display, and pagination for a dynamic user interface.
- **Real-World Project**: Built in a linear and progressive manner, ensuring robust functionality and scalable architecture.

## Technologies Used
- **Backend**: Django
- **Frontend**: React
- **Payment Integration**: PayPal API, Stripe API
- **Database**: PostgreSQL
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Docker, AWS

## Installation

### Prerequisites
- Python 3.x
- Node.js
- PostgreSQL
- Docker (for deployment)

### Backend Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ecommerce-platform.git
    cd ecommerce-platform
    ```
2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```
3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Set up the PostgreSQL database and update the database settings in `settings.py`.
5. Run the migrations:
    ```bash
    python manage.py migrate
    ```
6. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```
7. Start the development server:
    ```bash
    python manage.py runserver
    ```

### Frontend Setup
1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```
2. Install the dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm start
    ```

## Usage
- Access the frontend at `http://localhost:3000`.
- Access the backend at `http://localhost:8000`.
- Admin area can be accessed at `http://localhost:8000/admin`.

## Contributing
Contributions are welcome! Please create an issue or submit a pull request for any changes or improvements.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
