# Generate API key

Generate an API key for a user. 

## Query

```plain
POST /api/v1/user/{id}/key/renew
```

with: 

- `id`: id of the user

##  Request Body Example

!!! Example "" 
    
    ```json
    {
      "password": "thehive1234"
    }
    ```

The following fields are required: 

- `password`: (String)

##  Response 

### Status codes

- `200`: if the API key have succesfully been generated
- `401`: Authentication error
- `403`: Authorization error

### Response Body Example

!!! Example ""

    ```plain
      BOXTE+Cq0qrZcHhTK4j0LpT/TVW5auOz
    ``` 