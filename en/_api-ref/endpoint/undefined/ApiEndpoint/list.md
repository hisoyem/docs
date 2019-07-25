---
editable: false
---

# Method list

 

 
## HTTP request {#https-request}
```
GET undefined/endpoints
```
 
## Query parameters {#query_params}
 
Parameter | Description
--- | ---
pageSize | 
pageToken | 
 
## Response {#responses}
**HTTP Code: 200 - OK**

```json 
{
  "endpoints": [
    {
      "id": "string",
      "address": "string"
    }
  ],
  "nextPageToken": "string"
}
```

 
Field | Description
--- | ---
endpoints[] | **object**<br>
endpoints[].<br>id | **string**<br>
endpoints[].<br>address | **string**<br>
nextPageToken | **string**<br>