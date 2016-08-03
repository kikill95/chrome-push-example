### Snippet from Postman

URL: https://android.googleapis.com/gcm/send

HEADERS:
    Content-Type: application/json
    Authorization: key=<****>

BODY:
    {
        "notification": {
            "title": "Portugal vs. Denmark",
            "text": "5 to 1"
        },
        "registration_ids": [
            "<id from Chrome console>"
        ],
        "data" : {
            "hello": "world"
        }
    }
