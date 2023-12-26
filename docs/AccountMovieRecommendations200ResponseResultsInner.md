# OpenapiClient::AccountMovieRecommendations200ResponseResultsInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **adult** | **Boolean** |  | [optional][default to true] |
| **backdrop_path** | **String** |  | [optional] |
| **id** | **Integer** |  | [optional][default to 0] |
| **title** | **String** |  | [optional] |
| **original_language** | **String** |  | [optional] |
| **original_title** | **String** |  | [optional] |
| **overview** | **String** |  | [optional] |
| **poster_path** | **String** |  | [optional] |
| **media_type** | **String** |  | [optional] |
| **genre_ids** | **Array&lt;Integer&gt;** |  | [optional] |
| **popularity** | **Float** |  | [optional][default to 0] |
| **release_date** | **String** |  | [optional] |
| **video** | **Boolean** |  | [optional][default to true] |
| **vote_average** | **Float** |  | [optional][default to 0] |
| **vote_count** | **Integer** |  | [optional][default to 0] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountMovieRecommendations200ResponseResultsInner.new(
  adult: false,
  backdrop_path: /9sfVyE3sP2dkCwDyV7UlYP5TAAR.jpg,
  id: 823754,
  title: Bo Burnham: Inside,
  original_language: en,
  original_title: Bo Burnham: Inside,
  overview: Stuck in COVID-19 lockdown, US comedian and musician Bo Burnham attempts to stay sane and happy by writing, shooting and performing a one-man comedy special.,
  poster_path: /ku1UvTWYvhFQbSesOD6zteY7bXT.jpg,
  media_type: movie,
  genre_ids: null,
  popularity: 11.904,
  release_date: 2021-07-22,
  video: false,
  vote_average: 8.178,
  vote_count: 352
)
```

