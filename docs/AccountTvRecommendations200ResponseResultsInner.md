# OpenapiClient::AccountTvRecommendations200ResponseResultsInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **adult** | **Boolean** |  | [optional][default to true] |
| **backdrop_path** | **String** |  | [optional] |
| **id** | **Integer** |  | [optional][default to 0] |
| **name** | **String** |  | [optional] |
| **original_language** | **String** |  | [optional] |
| **original_name** | **String** |  | [optional] |
| **overview** | **String** |  | [optional] |
| **poster_path** | **String** |  | [optional] |
| **media_type** | **String** |  | [optional] |
| **genre_ids** | **Array&lt;Integer&gt;** |  | [optional] |
| **popularity** | **Float** |  | [optional][default to 0] |
| **first_air_date** | **String** |  | [optional] |
| **vote_average** | **Float** |  | [optional][default to 0] |
| **vote_count** | **Integer** |  | [optional][default to 0] |
| **origin_country** | **Array&lt;String&gt;** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountTvRecommendations200ResponseResultsInner.new(
  adult: false,
  backdrop_path: /7bsHAsS1RDtslictkApeb7cedLL.jpg,
  id: 152483,
  name: The Boys Presents: Diabolical,
  original_language: en,
  original_name: The Boys Presents: Diabolical,
  overview: From some of the most unhinged and maniacal minds in Hollywood today comes this animated anthology series, a collection of irreverent and emotionally shocking animated short films. Each episode plunges elbow-deep into unseen crevices of The Boys Universe.,
  poster_path: /kZKfZWwFOAicgoKS2IO7oM1GuHZ.jpg,
  media_type: tv,
  genre_ids: null,
  popularity: 24.596,
  first_air_date: 2022-03-03,
  vote_average: 7.201,
  vote_count: 214,
  origin_country: null
)
```

