# OpenapiClient::AccountRatedMovies200ResponseResultsInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **adult** | **Boolean** |  | [optional][default to true] |
| **backdrop_path** | **String** |  | [optional] |
| **genre_ids** | **Array&lt;Integer&gt;** |  | [optional] |
| **id** | **Integer** |  | [optional][default to 0] |
| **original_language** | **String** |  | [optional] |
| **original_title** | **String** |  | [optional] |
| **overview** | **String** |  | [optional] |
| **popularity** | **Float** |  | [optional][default to 0] |
| **poster_path** | **String** |  | [optional] |
| **release_date** | **String** |  | [optional] |
| **title** | **String** |  | [optional] |
| **video** | **Boolean** |  | [optional][default to true] |
| **vote_average** | **Float** |  | [optional][default to 0] |
| **vote_count** | **Integer** |  | [optional][default to 0] |
| **account_rating** | [**AccountRatedMovies200ResponseResultsInnerAccountRating**](AccountRatedMovies200ResponseResultsInnerAccountRating.md) |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountRatedMovies200ResponseResultsInner.new(
  adult: false,
  backdrop_path: /dUVbWINfRMGojGZRcO6GF1Z2nV8.jpg,
  genre_ids: null,
  id: 120,
  original_language: en,
  original_title: The Lord of the Rings: The Fellowship of the Ring,
  overview: Young hobbit Frodo Baggins, after inheriting a mysterious ring from his uncle Bilbo, must leave his home in order to keep it from falling into the hands of its evil creator. Along the way, a fellowship is formed to protect the ringbearer and make sure that the ring arrives at its final destination: Mt. Doom, the only place where it can be destroyed.,
  popularity: 79.298,
  poster_path: /6oom5QYQ2yQTMJIbnvbkBL9cHo6.jpg,
  release_date: 2001-12-18,
  title: The Lord of the Rings: The Fellowship of the Ring,
  video: false,
  vote_average: 8.4,
  vote_count: 22626,
  account_rating: null
)
```

