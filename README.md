# django.core.exceptions.ImproperlyConfigured-WSGI-application-solved



1) Read carefully, it might say "The above exception was the direct cause of the following exception: ...". And the "above exception" being you forgot to install whitehoise. Run pip install whitenoise, it worked for me

2)I used a middleware CorsMiddleware but forget to install it so after install, it works perfectly.
pip install django-cors-headers
