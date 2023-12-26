# OpenapiClient::ListClear200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **items_deleted** | **Integer** |  | [optional][default to 0] |
| **status_message** | **String** |  | [optional] |
| **id** | **Integer** |  | [optional][default to 0] |
| **status_code** | **Integer** |  | [optional][default to 0] |
| **success** | **Boolean** |  | [optional][default to true] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ListClear200Response.new(
  items_deleted: 1,
  status_message: Success.,
  id: 10,
  status_code: 1,
  success: true
)
```

