# API Deployment

## Questions

- According to "Django Settings Best Practices," the key principles for organizing and configuring Django settings in a project involve using separate settings files for different environments, utilizing environment variables for sensitive information, keeping default settings separate, and using secure methods to manage secrets like Django's built-in django-environ.

- The White Noise library improves the serving of static files in a Django application by handling them efficiently without relying on a separate web server like Apache or Nginx, enhancing performance and simplifying deployment. To integrate White Noise, you need to install it, add its middleware to the MIDDLEWARE setting in Django, collect static files using python manage.py collectstatic, and configure the web server to serve dynamic requests to Django and static files through White Noise.

- Cross-Origin Resource Sharing (CORS) is a security feature used in web applications to control access to resources from different domains, preventing unauthorized access to resources from web pages not on the same origin as the server. In a Django project, CORS can be implemented and configured using the django-cors-headers library. By adding the library to the project, defining allowed origins, methods, and headers in the settings, and applying CORS settings globally or to specific views, you can control access to resources and enhance the security of your web application.
