# A REST based sample app with python django

1.initializing a virtual environment
```
python3 -m venv env
. env/bin/activate 
```

2.Install requirements
```
pip install django
pip install djangorestframework
```
3.Open the file ( shoppingcart)
```
cd shopping_cart 
```
4.apply the migration (set up database)
```
python3 manage.py migrate  # Initialize database
```
5.Create the username and password
```
python3 manage.py createsuperuser
```
6.Run the app
```
python3 manage.py runserver
```
7.Accessing URLs

Admin interface for creating the cart items etc.
http://127.0.0.1:8000/admin/

For listing the cart items
http://127.0.0.1:8000/api/cart-items/