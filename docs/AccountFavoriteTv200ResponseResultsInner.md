# OpenapiClient::AccountFavoriteTv200ResponseResultsInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **adult** | **Boolean** |  | [optional][default to true] |
| **backdrop_path** | **String** |  | [optional] |
| **genre_ids** | **Array&lt;Integer&gt;** |  | [optional] |
| **id** | **Integer** |  | [optional][default to 0] |
| **origin_country** | **Array&lt;String&gt;** |  | [optional] |
| **original_language** | **String** |  | [optional] |
| **original_name** | **String** |  | [optional] |
| **overview** | **String** |  | [optional] |
| **popularity** | **Float** |  | [optional][default to 0] |
| **poster_path** | **String** |  | [optional] |
| **first_air_date** | **String** |  | [optional] |
| **name** | **String** |  | [optional] |
| **vote_average** | **Float** |  | [optional][default to 0] |
| **vote_count** | **Integer** |  | [optional][default to 0] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountFavoriteTv200ResponseResultsInner.new(
  adult: false,
  backdrop_path: /bsNm9z2TJfe0WO3RedPGWQ8mG1X.jpg,
  genre_ids: null,
  id: 1396,
  origin_country: null,
  original_language: en,
  original_name: Breaking Bad,
  overview: When Walter White, a New Mexico chemistry teacher, is diagnosed with Stage III cancer and given a prognosis of only two years left to live. He becomes filled with a sense of fearlessness and an unrelenting desire to secure his family&#39;s financial future at any cost as he enters the dangerous world of drugs and crime.,
  popularity: 255.118,
  poster_path: /ggFHVNu6YYI5L9pCfOacjizRGt.jpg,
  first_air_date: 2008-01-20,
  name: Breaking Bad,
  vote_average: 8.879,
  vote_count: 11625
)
```

