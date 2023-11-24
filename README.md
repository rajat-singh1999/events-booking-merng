# Events-Booking(MERN+GQL)

Event booking webapp using MERN and GQL (MERNG?!?!👀️)
I am still working on this one, the entire frontend(R in MERNG) part is left... 😄

## Installation

go for ```npm i``` should work.

## Usage

after node_modules installation you might want to configure a ```nodemon.json``` file like so:

```
{
    "env": {
        "MONGO_USER": "<your_mongo_atlas_db_username>",
        "MONGO_PASSWORD": "<your_mongo_atlas_db_password>",
        "MONGO_DB": "<db_name_of_your_choice>",
        "JWT_SECRET_KEY": "<jwt_secret>" //for authentication using jwt
    }
}
```

You may run the queries and mutations using POSTMAN or any other tool that supports GQL.
You can determine the synatax by looking into the ```graphql/schema/ind.js``` file.

## Contributing

I should be able to add the frontend using React, but contribution for frontend are welcome using any framework or tool!

## Contact

- Rajat
- rsingh1734@gmail.com
