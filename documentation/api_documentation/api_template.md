#### **Endpoint URL**

Brief description of what the endpoint does

**HTTP Method:** `HTTP_METHOD`

**Path:** `/endpoint/path`

**Request Parameters:**
> - `param_name` (type, optional): Brief description of the parameter

**Request Body:**
> - `body_param_name` (type, optional): Brief description of the parameter

**Response:**
> - Status Code: HTTP_STATUS_CODE
> - Content Type: CONTENT_TYPE

**Example Request:**
```http
HTTP_METHOD /endpoint/path
Host: example.com
Content-Type: application/json

{
  "body_param_name": "value"
}
```

**Example Response:**
```http
HTTP/1.1 HTTP_STATUS_CODE
Content-Type: CONTENT_TYPE

{
  "example": "response"
}
```
**Note:**
> Useful notes
> ...
