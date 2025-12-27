Project description
A lightweight Django e-commerce demo that implements product listing, search, user auth, and PayPal sandbox integration. Includes a simple store app with product/category models, templates, and views; static/media handling with WhiteNoise; and SQLite for local development.

Key features

Product catalog, search and detail pages (see store.views.home and store.views.product).
User authentication and profile handling (see store.views.login_user).
PayPal sandbox integration and static file handling configured in ecom.settings.
Templates under the store app, e.g. search.html.
Models for products and categories in store.models.Product.
Quick start

Install dependencies: see requirements.txt.
Run local server:
Apply migrations and start server via manage.py
