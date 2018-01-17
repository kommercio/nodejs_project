# NODE.JS & Mongo DB Test Project

## Task 1
### Create this endpoint: [POST] `/api/product`
Save a Product into a database. Product should have these properties:
- id
- name
- price

If successful, this endpoint must return a JSON response and `201` status code.
```
{
  "data": {
    "product": {
      "_id": "507f191e810c19729de860ea",
      "name": "Product 1",
      "price": 100000
    }
  }
}
```

## Task 2
### Create this endpoint: [GET] `/api/product/{id}`
Get product detail by ID
If successful, this endpoint must return a JSON response and `200` status code.
```
{
  "data": {
    "product": {
      "_id": "507f191e810c19729de860ea",
      "name": "Product 1",
      "price": 100000
    }
  }
}
```
