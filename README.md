## Simple JWT Authentication with [Django REST Framework](https://www.django-rest-framework.org/) and [Simple JWT](https://django-rest-framework-simplejwt.readthedocs.io/en/latest/)

### Obtain Token with HTTPie
`http post http://127.0.0.1:8000/api/token username=YOUR_USERNAME password=YOUR_PASSWORD`

### Obtain Token with curl
`curl -d '{"username":"YOUR_USERNAME", "password":"YOUR_PASSWORD"}' -H "Content-Type: application/json" -X POST http://127.0.0.1:8000/api/token`

### Refresh token endpoint
`http://127.0.0.1:8000/api/token/refresh`

### Test endpoint
`http://localhost:8000/hello/`