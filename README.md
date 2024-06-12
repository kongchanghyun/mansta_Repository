
# Mansta Club

This is a Django project for the Mansta Club online shop.

## Installation

1. Clone the repository
2. Navigate to the project directory
3. Install the dependencies
4. Run the migrations
5. Create a superuser
6. Start the development server

```bash
git clone <repository-url>
cd myshop
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

## Usage

- Access the admin panel at `/admin/` to add and manage products.
- The main page displays the products available in the shop.

## Directory Structure

- `myshop/` - Django project settings
- `shop/` - Application for managing products
- `templates/` - HTML templates
- `static/` - Static files (CSS, JS, images)
- `media/` - Uploaded media files
