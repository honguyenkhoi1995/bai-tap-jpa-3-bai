Bai tap JPA

Chay project:
mvn spring-boot:run

Student:
GET    /api/students
GET    /api/students/{id}
POST   /api/students
PUT    /api/students/{id}
DELETE /api/students/{id}

Product:
GET    /api/products?name=phone&page=0&size=5&sort=price,desc
GET    /api/products/{id}
POST   /api/products
PUT    /api/products/{id}
DELETE /api/products/{id}

Category:
GET    /api/categories
GET    /api/categories/{id}
POST   /api/categories
PUT    /api/categories/{id}
DELETE /api/categories/{id}
GET    /api/categories/{id}/products
