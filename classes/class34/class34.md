
## Q: What is Django's Model-View-Template (MVT) architecture, and how does it differ from the more commonly known Model-View-Controller (MVC) architecture?

A: Django follows the Model-View-Template (MVT) architecture, similar to the Model-View-Controller (MVC) pattern. In MVT, the View handles user requests and interacts with the Model (data/business logic). It then passes data to the Template for presentation. In MVC, the Controller handles user input and updates the Model and View. The main difference is that in MVT, the Controller's role is merged into the View.

## Q: How does the White Noise library contribute to the efficient serving of static files in a Django application, and what are the steps to integrate it into a project?

A: The White Noise library efficiently serves static files in a Django application, especially in production environments. It eliminates the need for a separate web server to handle static files. To integrate White Noise into a project, follow these steps:

- Install White Noise using pip.
- Add the White Noise middleware to the MIDDLEWARE setting in Django's project settings.
- Configure STATIC_URL and STATIC_ROOT settings.
- Run python manage.py collectstatic to collect static files into STATIC_ROOT.
- Update the web server configuration (if applicable) to serve static files from STATIC_ROOT.
## Q: What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications, and how can it be implemented and configured in a Django project to control access to resources?

A: Cross-Origin Resource Sharing (CORS) is a security feature implemented in web browsers to prevent web pages from making requests to different domains than the one serving the web page. CORS helps protect users from potential malicious actions by restricting cross-origin requests.

To implement CORS in a Django project, follow these steps:

- Install the django-cors-headers package using pip.
- Add 'corsheaders' to INSTALLED_APPS in Django project settings.
- Add the CorsMiddleware to the MIDDLEWARE setting.
- Define allowed origins in the CORS_ALLOWED_ORIGINS setting to control access to resources from specific domains.
- Fine-tune CORS settings (if needed) for specific methods, credentials, headers, etc.
