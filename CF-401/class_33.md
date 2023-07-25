# Authentication & Production Server

## Questions

- What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?

The primary purpose of JSON Web Tokens (JWTs) is to facilitate secure and stateless communication between different parties. JWTs are used to represent claims that can be transferred between a client and a server. They work by encoding data into a JSON object, which is then signed using a secret key to generate a token. The token can be sent to the server as an authorization mechanism, and the server can verify its authenticity using the same secret key. JWTs are commonly used for authentication and authorization in web applications, allowing users to access protected resources without the need for server-side sessions.

- How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?

JWT Authentication integrates seamlessly with Django REST Framework (DRF) to secure API endpoints by providing a token-based authentication mechanism. The key components involved in this process are the authentication middleware and the view classes provided by DRF. When a user authenticates, they receive a JWT token upon successful login. This token is then included in the Authorization header of subsequent API requests. The authentication middleware in DRF intercepts the token, verifies its signature using the secret key, and identifies the user associated with the token. By comparing the token data with the user's credentials, the API endpoint is secured, allowing only authorized users with valid tokens to access protected resources.

- Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

Django's built-in runserver is not suitable for production environments mainly because it is designed for development purposes and lacks certain features required for robust and high-traffic production deployments. The runserver is single-threaded, meaning it can only handle one request at a time, making it inefficient for serving concurrent requests. Additionally, it does not offer advanced security features and should not be exposed directly to the internet. For deploying a Django application in production, alternatives like Gunicorn (Green Unicorn) or uWSGI are commonly used. These application servers are designed to handle multiple requests concurrently and provide better performance and reliability. When combined with a production-ready web server like Nginx or Apache, Gunicorn or uWSGI can effectively serve Django applications in a secure and performant manner.
