# AWSLambda

Some practice lambda functions using Go and Python

## Testing Command using curl

``` sh
curl --header "Content-Type: application/json" \
  --request POST \
  --data '{"username":"xyz","password":"xyz"}' \
  http://localhost:3000/api/login
```
