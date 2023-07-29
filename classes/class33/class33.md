
## Q: What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?

### A: JSON Web Tokens (JWTs) are used for authentication and authorization in web applications and APIs. They encode user information (claims) into a secure token. JWTs consist of three parts: header, payload, and signature. The server creates the token by encoding the header and payload, generating a signature with a secret key, and sending it to the client. The client includes the JWT in requests, and the server decodes it using the secret key to validate and extract user information.
## Q: How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?

A: Django REST Framework (DRF) supports JWT Authentication for securing API endpoints. The integration involves:

1- Installing required packages (djangorestframework and djangorestframework_simplejwt).

2- Configuring Django settings for authentication.

3- Creating views to generate JWT tokens for authenticated users.

4- Protecting API endpoints with @authentication_classes and @permission_classes decorators.

5- Storing the received JWT securely on the client-side.
6- Including the JWT in subsequent API requests' Authorization header.

DRF validates the JWT and grants access to authenticated users to requested resources.


## Q: Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

A: Django's runserver is not production-ready due to:

1- Lack of performance optimizations.

2- Single-threaded nature, limiting concurrent request handling.

3- Insufficient security features.

4- No load balancing support.


 For production, consider using:

1- uWSGI: A high-performance application server.

2- Gunicorn: Easy-to-set-up, works well with Nginx.

3- mod_wsgi: For Apache HTTP Server users.

4- Daphne and ASGI servers: For Django Channels and WebSocket support.

Use a production-ready web server like Nginx or Apache to serve static files, handle SSL, and act as a reverse proxy. Employ containerization (e.g., Docker) or cloud platforms (e.g., AWS, Google Cloud) for scalability and ease of deployment. Always prioritize security measures for the server and application.
