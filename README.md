# Django E-commerce Project (170186 Kulubya Hassan)

A simple Django-based e-commerce system demonstrating customer-order relationships.

## Project Overview
This project implements a basic e-commerce data model with:
- Customer management (name, email)
- Order tracking (order date, total amount)
- One-to-many relationship between Customers and Orders

## Prerequisites
- Python 3.10 or higher
- Django 5.1.3

## Installation

1. Clone the repository
bash
git clone <https://github.com/Hassan-KreateStudio/cat-one-q1.git>
cd <cat-one-q1>

2. Create a virtual environment
bash
python -m venv venv


3. Activate the virtual environment
- Windows:
bash
venv\Scripts\activate


4. Install dependencies
bash
pip install django


5. Run migrations
bash
python manage.py makemigrations
python manage.py migrate


6. Create a superuser (optional)
bash
python manage.py createsuperuser


7. Run the development server
bash
python manage.py runserver

## Project Structure
ecommerce/
├── ecommerce/ # Project configuration
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── asgi.py
├── store/ # Main application
│ ├── models.py # Data models
│ ├── migrations/ # Database migrations
│ └── admin.py
├── manage.py
├── requirements.txt
└── README.md


## Models
- Customer: Stores customer information (name, email)
- Order: Tracks orders with customer relationship, date, and amount

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License
This project is licensed under the MIT License.
