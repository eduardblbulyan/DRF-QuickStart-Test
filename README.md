# Testing


### Via `curl`

```shell
bash: curl -u admin -H 'Accept: application/json; indent=4' http://127.0.0.1:8000/users/
```

**Response**

```shell
Enter host password for user 'admin':
{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "url": "http://127.0.0.1:8000/users/1/",
            "username": "admin",
            "email": "admin@example.com",
            "groups": []
        }
    ]
}
```

Or you can access via `http://127.0.0.1:8000/users/`