# User API Specification

## Create User
Endpoint : POST /api/users

Request Body :

```json
{
  "nama" : "Alfan",
  "usia" : 21
}
```

Response Body (success) :

```json
{
  "data": {
    "id" : "random string",
    "nama": "Alfan",
    "usia": 21
  }
}
```

Response Body (failed) :

```json
{
  "error": "Invalid input data"
}
```

## Update User
Endpoint : PUT /api/users/{id}

Request Body :

```json
{
  "nama" : "Alfan",
  "usia" : 22
}
```

Response Body (success) :

```json
{
  "data": {
    "id" : "random string",
    "nama": "Alfan",
    "usia": 22
  }
}
```

Response Body (failed) :

```json
{
  "error": "User not found"
}
```

## Get User
Endpoint : GET /api/users

Response Body (success) :

```json
{
  "data": {
    "id" : "random string",
    "nama": "Alfan",
    "usia": 21
  }
}
```

Response Body (failed) :

```json
{
  "error": "User not found"
}
```

## Delete User
Endpoint : DELETE /api/users/{id}

Response Body (success) :

```json
{
  "message": "User deleted successfully"
}
```

Response Body (failed) :

```json
{
  "error": "User not found"
}
```

Screenshot
<img width="2880" height="1704" alt="Screenshot 2026-03-02 120036" src="https://github.com/user-attachments/assets/5e96389d-9780-458b-9434-ce4feba7c654" />
<img width="2880" height="1704" alt="Screenshot 2026-03-02 120051" src="https://github.com/user-attachments/assets/c608f76e-3e23-49a5-9ca3-4c9d9ccb2fb9" />
<img width="2880" height="1704" alt="Screenshot 2026-03-02 120106" src="https://github.com/user-attachments/assets/61e5b8d8-0459-4975-92a1-d2f59e7c9403" />


