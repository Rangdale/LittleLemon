# Little Lemon Backend API

Menu API:
GET /restaurant/menu/
POST /restaurant/menu/
GET /restaurant/menu/<id>/
PUT /restaurant/menu/<id>/
DELETE /restaurant/menu/<id>/

Booking API (Protected):
GET /restaurant/booking/tables/
POST /restaurant/booking/tables/
GET /restaurant/booking/tables/<id>/
PUT /restaurant/booking/tables/<id>/
DELETE /restaurant/booking/tables/<id>/

Authentication:
POST /auth/users/                (Register)
POST /auth/token/login/         (Login)
POST /auth/token/logout/        (Logout)

Token Endpoint:
POST /restaurant/api-token-auth/

Note:

* Use Token Authentication for Booking API
* Add header: Authorization: Token <your_token>
LittleLemon
