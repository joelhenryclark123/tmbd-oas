# OpenapiClient::ListCreate200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **status_message** | **String** |  | [optional] |
| **id** | **Integer** |  | [optional][default to 0] |
| **success** | **Boolean** |  | [optional][default to true] |
| **status_code** | **Integer** |  | [optional][default to 0] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ListCreate200Response.new(
  status_message: The item/record was created successfully.,
  id: 5854,
  success: true,
  status_code: 1
)
```

