# OpenapiClient::AuthCreateRequestToken200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **status_message** | **String** |  | [optional] |
| **request_token** | **String** |  | [optional] |
| **success** | **Boolean** |  | [optional][default to true] |
| **status_code** | **Integer** |  | [optional][default to 0] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AuthCreateRequestToken200Response.new(
  status_message: Success.,
  request_token: eyJhbGciOiJIfsISNiIaInR5cCI6IkpXVCJ9.eyJuYmYiOjE0NzIwNTQ1ODEsInZlcnNpb24iOjEsImV4zCI6MTQ3MjA1NTQ4MSwiYXXkIjoiM2Y4Nzg1N2JlMjA5ZDM1MTk4MzNiMzAwYTEzZDBlMqIiLCJzY29wZXMiOlsicGVuZGluZ19yZXF1ZXN0X3Rva2VuIl0sImp0aSI6Nd0.e0t83AUvwywXPBb-hSAY_J_y4TjcwA0w98GhCCQM1dA,
  success: true,
  status_code: 1
)
```

