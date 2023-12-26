# OpenapiClient::ListItemStatus200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **media_type** | **String** |  | [optional] |
| **success** | **Boolean** |  | [optional][default to true] |
| **status_message** | **String** |  | [optional] |
| **id** | **Integer** |  | [optional][default to 0] |
| **media_id** | **Integer** |  | [optional][default to 0] |
| **status_code** | **Integer** |  | [optional][default to 0] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::ListItemStatus200Response.new(
  media_type: movie,
  success: true,
  status_message: Success.,
  id: 1,
  media_id: 99861,
  status_code: 1
)
```

