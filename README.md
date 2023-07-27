# expenses-tracker
This is a restful API using Springboot and PostgreSQL database with JSON web token (JWT) to add authentication. PostgreSQL is a relational database and we will use the JDBC template to interact with that. This app is for tracking expenses. Users can register and log in and then record their expense transactions in different categories. When a user logs in, they can create various categories such as Shopping, and HouseHold Billings and for each of this, they can add transactions. This is a typical one-to-many relationship. A user can have multiple categories, each category can have multiple transactions.

## Endpoints

### Register a User

> POST  /api/user/register

#### Data

```
{
    "firstName": "David",
    "lastName": "Smith",
    "email": "david@testmail.com",
    "password": "test123",
}
```

#### Response

```
{
  "token":"
}
```

### User Log in

> POST api/user/login

### Data

```
{
}
```
#### Response

```
{
}
```

### Create category

> POST api/category

```
{
}
```
#### Response

```
{
}
```

#### Response

```
{
}
```

### Get all categories

> GET api/category

```
{
}
```
#### Response

```
{
}
```

