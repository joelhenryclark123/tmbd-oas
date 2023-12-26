# OpenapiClient::AccountFavoriteMovies200ResponseResultsInner

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

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountFavoriteMovies200ResponseResultsInner.new(
  adult: false,
  backdrop_path: /se5Hxz7PArQZOG3Nx2bpfOhLhtV.jpg,
  genre_ids: null,
  id: 9806,
  original_language: en,
  original_title: The Incredibles,
  overview: Bob Parr has given up his superhero days to log in time as an insurance adjuster and raise his three children with his formerly heroic wife in suburbia. But when he receives a mysterious assignment, it&#39;s time to get back into costume.,
  popularity: 67.887,
  poster_path: /2LqaLgk4Z226KkgPJuiOQ58wvrm.jpg,
  release_date: 2004-10-27,
  title: The Incredibles,
  video: false,
  vote_average: 7.702,
  vote_count: 16188
)
```

