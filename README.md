# NODE.JS & Mongo DB Test Project

For submission, please send Github link of the test project.

## Task 1
### Create this endpoint: [POST] `/api/product`
Save a Product into Mongo database. Product should have these properties:
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
Get product detail by ID from Mongo database
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
