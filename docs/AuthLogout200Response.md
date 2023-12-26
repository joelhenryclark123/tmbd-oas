# OpenapiClient::AuthLogout200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **status_message** | **String** |  | [optional] |
| **success** | **Boolean** |  | [optional][default to true] |
| **status_code** | **Integer** |  | [optional][default to 0] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AuthLogout200Response.new(
  status_message: The item/record was deleted successfully.,
  success: true,
  status_code: 13
)
```

