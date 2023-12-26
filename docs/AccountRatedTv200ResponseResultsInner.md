# OpenapiClient::AccountRatedTv200ResponseResultsInner

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
| **account_rating** | [**AccountRatedTv200ResponseResultsInnerAccountRating**](AccountRatedTv200ResponseResultsInnerAccountRating.md) |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountRatedTv200ResponseResultsInner.new(
  adult: false,
  backdrop_path: /2yZXtM2Kky1Sy0kachbDlwybl3y.jpg,
  genre_ids: null,
  id: 1705,
  origin_country: null,
  original_language: en,
  original_name: Fringe,
  overview: FBI Special Agent Olivia Dunham, brilliant but formerly institutionalized scientist Walter Bishop and his scheming, reluctant son Peter uncover a deadly mystery involving a series of unbelievable events and realize they may be a part of a larger, more disturbing pattern that blurs the line between science fiction and technology.,
  popularity: 145.5,
  poster_path: /sY9hg5dLJ93RJOyKEiu1nAtBRND.jpg,
  first_air_date: 2008-09-09,
  name: Fringe,
  vote_average: 8.11,
  vote_count: 2053,
  account_rating: null
)
```

