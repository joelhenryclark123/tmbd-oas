# OpenapiClient::AccountFavoriteMovies200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** |  | [optional][default to 0] |
| **results** | [**Array&lt;AccountFavoriteMovies200ResponseResultsInner&gt;**](AccountFavoriteMovies200ResponseResultsInner.md) |  | [optional] |
| **total_pages** | **Integer** |  | [optional][default to 0] |
| **total_results** | **Integer** |  | [optional][default to 0] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountFavoriteMovies200Response.new(
  page: 1,
  results: null,
  total_pages: 4,
  total_results: 80
)
```

