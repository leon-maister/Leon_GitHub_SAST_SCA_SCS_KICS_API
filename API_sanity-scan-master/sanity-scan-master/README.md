# sanity-scan

## Prerequisite
- java 11

## Usage
```
curl --location --request POST 'http://localhost:8080/user/insert' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "lior",
    "password": "Aa123456!",
    "email": "koko@domain.com",
    "info": "something funny"
    
}'

curl --location --request GET 'http://localhost:8080/user/get/firstName/byEmail/koko@domain' \
--header 'Content-Type: application/json' \
--data-raw ''

```
