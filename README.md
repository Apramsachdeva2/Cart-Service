# Cart-Service
A REST API that provides URLs for adding, deleting and retrieving elements in CartDB

This API is built using spring boot, RestController annotation, springJDBC.

MySQL is used for database.

url:- https://apram-cart-service.herokuapp.com/cartservice/getCartItems


Send a get request to retrieve all the items present in CartDB.

Sends response status 'NOT_FOUND' in case of any Exception.
