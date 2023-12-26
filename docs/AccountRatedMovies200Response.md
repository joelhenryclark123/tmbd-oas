# OpenapiClient::AccountRatedMovies200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page** | **Integer** |  | [optional][default to 0] |
| **results** | [**Array&lt;AccountRatedMovies200ResponseResultsInner&gt;**](AccountRatedMovies200ResponseResultsInner.md) |  | [optional] |
| **total_pages** | **Integer** |  | [optional][default to 0] |
| **total_results** | **Integer** |  | [optional][default to 0] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountRatedMovies200Response.new(
  page: 1,
  results: null,
  total_pages: 47,
  total_results: 940
)
```

