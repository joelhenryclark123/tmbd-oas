# OpenapiClient::DefaultApi

All URIs are relative to *https://api.themoviedb.org*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**account_favorite_movies**](DefaultApi.md#account_favorite_movies) | **GET** /4/account/{account_object_id}/movie/favorites | Favorite Movies |
| [**account_favorite_tv**](DefaultApi.md#account_favorite_tv) | **GET** /4/account/{account_object_id}/tv/favorites | Favorite TV Shows |
| [**account_lists**](DefaultApi.md#account_lists) | **GET** /4/account/{account_object_id}/lists | Lists |
| [**account_movie_recommendations**](DefaultApi.md#account_movie_recommendations) | **GET** /4/account/{account_object_id}/movie/recommendations | Recommended Movies |
| [**account_movie_watchlist**](DefaultApi.md#account_movie_watchlist) | **GET** /4/account/{account_object_id}/movie/watchlist | Watchlist Movies |
| [**account_rated_movies**](DefaultApi.md#account_rated_movies) | **GET** /4/account/{account_object_id}/movie/rated | Rated Movies |
| [**account_rated_tv**](DefaultApi.md#account_rated_tv) | **GET** /4/account/{account_object_id}/tv/rated | Rated TV Shows |
| [**account_tv_recommendations**](DefaultApi.md#account_tv_recommendations) | **GET** /4/account/{account_object_id}/tv/recommendations | Recommended TV Shows |
| [**account_tv_watchlist**](DefaultApi.md#account_tv_watchlist) | **GET** /4/account/{account_object_id}/tv/watchlist | Watchlist TV Shows |
| [**auth_create_access_token**](DefaultApi.md#auth_create_access_token) | **POST** /4/auth/access_token | Create Access Token |
| [**auth_create_request_token**](DefaultApi.md#auth_create_request_token) | **POST** /4/auth/request_token | Create Request Token |
| [**auth_logout**](DefaultApi.md#auth_logout) | **DELETE** /4/auth/access_token | Logout |
| [**list_clear**](DefaultApi.md#list_clear) | **GET** /4/list/{list_id}/clear | Clear |
| [**list_create**](DefaultApi.md#list_create) | **POST** /4/list | Create |
| [**list_delete**](DefaultApi.md#list_delete) | **DELETE** /4/{list_id} | Delete |
| [**list_item_status**](DefaultApi.md#list_item_status) | **GET** /4/list/{list_id}/item_status | Item Status |


## account_favorite_movies

> <AccountFavoriteMovies200Response> account_favorite_movies(account_object_id, opts)

Favorite Movies

Get a user's list of favourite movies.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
account_object_id = 'account_object_id_example' # String | 
opts = {
  page: 56, # Integer | 
  language: 'language_example' # String | 
}

begin
  # Favorite Movies
  result = api_instance.account_favorite_movies(account_object_id, opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_favorite_movies: #{e}"
end
```

#### Using the account_favorite_movies_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountFavoriteMovies200Response>, Integer, Hash)> account_favorite_movies_with_http_info(account_object_id, opts)

```ruby
begin
  # Favorite Movies
  data, status_code, headers = api_instance.account_favorite_movies_with_http_info(account_object_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountFavoriteMovies200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_favorite_movies_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_object_id** | **String** |  | [default to &#39;&lt;&lt;account_object_id&gt;&gt;&#39;] |
| **page** | **Integer** |  | [optional][default to 1] |
| **language** | **String** |  | [optional][default to &#39;en-US&#39;] |

### Return type

[**AccountFavoriteMovies200Response**](AccountFavoriteMovies200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_favorite_tv

> <AccountFavoriteTv200Response> account_favorite_tv(account_object_id, opts)

Favorite TV Shows

Get a user's list of favourite TV shows.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
account_object_id = 'account_object_id_example' # String | 
opts = {
  page: 56, # Integer | 
  language: 'language_example' # String | 
}

begin
  # Favorite TV Shows
  result = api_instance.account_favorite_tv(account_object_id, opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_favorite_tv: #{e}"
end
```

#### Using the account_favorite_tv_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountFavoriteTv200Response>, Integer, Hash)> account_favorite_tv_with_http_info(account_object_id, opts)

```ruby
begin
  # Favorite TV Shows
  data, status_code, headers = api_instance.account_favorite_tv_with_http_info(account_object_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountFavoriteTv200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_favorite_tv_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_object_id** | **String** |  | [default to &#39;&lt;&lt;account_object_id&gt;&gt;&#39;] |
| **page** | **Integer** |  | [optional][default to 1] |
| **language** | **String** |  | [optional][default to &#39;en-US&#39;] |

### Return type

[**AccountFavoriteTv200Response**](AccountFavoriteTv200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_lists

> <AccountLists200Response> account_lists(account_object_id, opts)

Lists

Get all of the lists you've created.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
account_object_id = 'account_object_id_example' # String | 
opts = {
  page: 56 # Integer | 
}

begin
  # Lists
  result = api_instance.account_lists(account_object_id, opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_lists: #{e}"
end
```

#### Using the account_lists_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountLists200Response>, Integer, Hash)> account_lists_with_http_info(account_object_id, opts)

```ruby
begin
  # Lists
  data, status_code, headers = api_instance.account_lists_with_http_info(account_object_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountLists200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_lists_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_object_id** | **String** |  | [default to &#39;&lt;&lt;account_object_id&gt;&gt;&#39;] |
| **page** | **Integer** |  | [optional][default to 1] |

### Return type

[**AccountLists200Response**](AccountLists200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_movie_recommendations

> <AccountMovieRecommendations200Response> account_movie_recommendations(account_object_id, opts)

Recommended Movies

Get a user's list of recommended movies.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
account_object_id = 'account_object_id_example' # String | 
opts = {
  page: 56, # Integer | 
  language: 'language_example' # String | 
}

begin
  # Recommended Movies
  result = api_instance.account_movie_recommendations(account_object_id, opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_movie_recommendations: #{e}"
end
```

#### Using the account_movie_recommendations_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountMovieRecommendations200Response>, Integer, Hash)> account_movie_recommendations_with_http_info(account_object_id, opts)

```ruby
begin
  # Recommended Movies
  data, status_code, headers = api_instance.account_movie_recommendations_with_http_info(account_object_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountMovieRecommendations200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_movie_recommendations_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_object_id** | **String** |  | [default to &#39;&lt;&lt;account_object_id&gt;&gt;&#39;] |
| **page** | **Integer** |  | [optional][default to 1] |
| **language** | **String** |  | [optional][default to &#39;en-US&#39;] |

### Return type

[**AccountMovieRecommendations200Response**](AccountMovieRecommendations200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_movie_watchlist

> <AccountMovieRecommendations200Response> account_movie_watchlist(account_object_id, opts)

Watchlist Movies

Get a user's movie watchlist.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
account_object_id = 'account_object_id_example' # String | 
opts = {
  page: 56, # Integer | 
  language: 'language_example' # String | 
}

begin
  # Watchlist Movies
  result = api_instance.account_movie_watchlist(account_object_id, opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_movie_watchlist: #{e}"
end
```

#### Using the account_movie_watchlist_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountMovieRecommendations200Response>, Integer, Hash)> account_movie_watchlist_with_http_info(account_object_id, opts)

```ruby
begin
  # Watchlist Movies
  data, status_code, headers = api_instance.account_movie_watchlist_with_http_info(account_object_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountMovieRecommendations200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_movie_watchlist_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_object_id** | **String** |  | [default to &#39;&lt;&lt;account_object_id&gt;&gt;&#39;] |
| **page** | **Integer** |  | [optional][default to 1] |
| **language** | **String** |  | [optional][default to &#39;en-US&#39;] |

### Return type

[**AccountMovieRecommendations200Response**](AccountMovieRecommendations200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_rated_movies

> <AccountRatedMovies200Response> account_rated_movies(account_object_id, opts)

Rated Movies

Get a user's rated movies.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
account_object_id = 'account_object_id_example' # String | 
opts = {
  page: 56, # Integer | 
  language: 'language_example' # String | 
}

begin
  # Rated Movies
  result = api_instance.account_rated_movies(account_object_id, opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_rated_movies: #{e}"
end
```

#### Using the account_rated_movies_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountRatedMovies200Response>, Integer, Hash)> account_rated_movies_with_http_info(account_object_id, opts)

```ruby
begin
  # Rated Movies
  data, status_code, headers = api_instance.account_rated_movies_with_http_info(account_object_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountRatedMovies200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_rated_movies_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_object_id** | **String** |  | [default to &#39;&lt;&lt;account_object_id&gt;&gt;&#39;] |
| **page** | **Integer** |  | [optional][default to 1] |
| **language** | **String** |  | [optional][default to &#39;en-US&#39;] |

### Return type

[**AccountRatedMovies200Response**](AccountRatedMovies200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_rated_tv

> <AccountRatedTv200Response> account_rated_tv(account_object_id, opts)

Rated TV Shows

Get a user's rated TV shows.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
account_object_id = 'account_object_id_example' # String | 
opts = {
  page: 56, # Integer | 
  language: 'language_example' # String | 
}

begin
  # Rated TV Shows
  result = api_instance.account_rated_tv(account_object_id, opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_rated_tv: #{e}"
end
```

#### Using the account_rated_tv_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountRatedTv200Response>, Integer, Hash)> account_rated_tv_with_http_info(account_object_id, opts)

```ruby
begin
  # Rated TV Shows
  data, status_code, headers = api_instance.account_rated_tv_with_http_info(account_object_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountRatedTv200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_rated_tv_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_object_id** | **String** |  | [default to &#39;&lt;&lt;account_object_id&gt;&gt;&#39;] |
| **page** | **Integer** |  | [optional][default to 1] |
| **language** | **String** |  | [optional][default to &#39;en-US&#39;] |

### Return type

[**AccountRatedTv200Response**](AccountRatedTv200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_tv_recommendations

> <AccountTvRecommendations200Response> account_tv_recommendations(account_object_id, opts)

Recommended TV Shows

Get a user's list of recommended TV shows.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
account_object_id = 'account_object_id_example' # String | 
opts = {
  page: 56, # Integer | 
  language: 'language_example' # String | 
}

begin
  # Recommended TV Shows
  result = api_instance.account_tv_recommendations(account_object_id, opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_tv_recommendations: #{e}"
end
```

#### Using the account_tv_recommendations_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountTvRecommendations200Response>, Integer, Hash)> account_tv_recommendations_with_http_info(account_object_id, opts)

```ruby
begin
  # Recommended TV Shows
  data, status_code, headers = api_instance.account_tv_recommendations_with_http_info(account_object_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountTvRecommendations200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_tv_recommendations_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_object_id** | **String** |  | [default to &#39;&lt;&lt;account_object_id&gt;&gt;&#39;] |
| **page** | **Integer** |  | [optional][default to 1] |
| **language** | **String** |  | [optional][default to &#39;en-US&#39;] |

### Return type

[**AccountTvRecommendations200Response**](AccountTvRecommendations200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## account_tv_watchlist

> <AccountTvRecommendations200Response> account_tv_watchlist(account_object_id, opts)

Watchlist TV Shows

Get a user's TV watchlist.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
account_object_id = 'account_object_id_example' # String | 
opts = {
  page: 56, # Integer | 
  language: 'language_example' # String | 
}

begin
  # Watchlist TV Shows
  result = api_instance.account_tv_watchlist(account_object_id, opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_tv_watchlist: #{e}"
end
```

#### Using the account_tv_watchlist_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountTvRecommendations200Response>, Integer, Hash)> account_tv_watchlist_with_http_info(account_object_id, opts)

```ruby
begin
  # Watchlist TV Shows
  data, status_code, headers = api_instance.account_tv_watchlist_with_http_info(account_object_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountTvRecommendations200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->account_tv_watchlist_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_object_id** | **String** |  | [default to &#39;&lt;&lt;account_object_id&gt;&gt;&#39;] |
| **page** | **Integer** |  | [optional][default to 1] |
| **language** | **String** |  | [optional][default to &#39;en-US&#39;] |

### Return type

[**AccountTvRecommendations200Response**](AccountTvRecommendations200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## auth_create_access_token

> <AuthCreateAccessToken200Response> auth_create_access_token(opts)

Create Access Token



### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
opts = {
  auth_create_request_token_request: OpenapiClient::AuthCreateRequestTokenRequest.new({raw_body: 'raw_body_example'}) # AuthCreateRequestTokenRequest | 
}

begin
  # Create Access Token
  result = api_instance.auth_create_access_token(opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->auth_create_access_token: #{e}"
end
```

#### Using the auth_create_access_token_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AuthCreateAccessToken200Response>, Integer, Hash)> auth_create_access_token_with_http_info(opts)

```ruby
begin
  # Create Access Token
  data, status_code, headers = api_instance.auth_create_access_token_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AuthCreateAccessToken200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->auth_create_access_token_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **auth_create_request_token_request** | [**AuthCreateRequestTokenRequest**](AuthCreateRequestTokenRequest.md) |  | [optional] |

### Return type

[**AuthCreateAccessToken200Response**](AuthCreateAccessToken200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## auth_create_request_token

> <AuthCreateRequestToken200Response> auth_create_request_token(opts)

Create Request Token



### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
opts = {
  auth_create_request_token_request: OpenapiClient::AuthCreateRequestTokenRequest.new({raw_body: 'raw_body_example'}) # AuthCreateRequestTokenRequest | 
}

begin
  # Create Request Token
  result = api_instance.auth_create_request_token(opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->auth_create_request_token: #{e}"
end
```

#### Using the auth_create_request_token_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AuthCreateRequestToken200Response>, Integer, Hash)> auth_create_request_token_with_http_info(opts)

```ruby
begin
  # Create Request Token
  data, status_code, headers = api_instance.auth_create_request_token_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AuthCreateRequestToken200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->auth_create_request_token_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **auth_create_request_token_request** | [**AuthCreateRequestTokenRequest**](AuthCreateRequestTokenRequest.md) |  | [optional] |

### Return type

[**AuthCreateRequestToken200Response**](AuthCreateRequestToken200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## auth_logout

> <AuthLogout200Response> auth_logout(opts)

Logout

Log out of a session.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
opts = {
  auth_create_request_token_request: OpenapiClient::AuthCreateRequestTokenRequest.new({raw_body: 'raw_body_example'}) # AuthCreateRequestTokenRequest | 
}

begin
  # Logout
  result = api_instance.auth_logout(opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->auth_logout: #{e}"
end
```

#### Using the auth_logout_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AuthLogout200Response>, Integer, Hash)> auth_logout_with_http_info(opts)

```ruby
begin
  # Logout
  data, status_code, headers = api_instance.auth_logout_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AuthLogout200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->auth_logout_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **auth_create_request_token_request** | [**AuthCreateRequestTokenRequest**](AuthCreateRequestTokenRequest.md) |  | [optional] |

### Return type

[**AuthLogout200Response**](AuthLogout200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## list_clear

> <ListClear200Response> list_clear(list_id)

Clear

Clear all of the items on a list.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
list_id = 56 # Integer | 

begin
  # Clear
  result = api_instance.list_clear(list_id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->list_clear: #{e}"
end
```

#### Using the list_clear_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListClear200Response>, Integer, Hash)> list_clear_with_http_info(list_id)

```ruby
begin
  # Clear
  data, status_code, headers = api_instance.list_clear_with_http_info(list_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListClear200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->list_clear_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **list_id** | **Integer** |  |  |

### Return type

[**ListClear200Response**](ListClear200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## list_create

> <ListCreate200Response> list_create(opts)

Create

Create a new list.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
opts = {
  auth_create_request_token_request: OpenapiClient::AuthCreateRequestTokenRequest.new({raw_body: 'raw_body_example'}) # AuthCreateRequestTokenRequest | 
}

begin
  # Create
  result = api_instance.list_create(opts)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->list_create: #{e}"
end
```

#### Using the list_create_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListCreate200Response>, Integer, Hash)> list_create_with_http_info(opts)

```ruby
begin
  # Create
  data, status_code, headers = api_instance.list_create_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListCreate200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->list_create_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **auth_create_request_token_request** | [**AuthCreateRequestTokenRequest**](AuthCreateRequestTokenRequest.md) |  | [optional] |

### Return type

[**ListCreate200Response**](ListCreate200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## list_delete

> <AuthLogout200Response> list_delete(list_id)

Delete

Delete a list.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
list_id = 56 # Integer | 

begin
  # Delete
  result = api_instance.list_delete(list_id)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->list_delete: #{e}"
end
```

#### Using the list_delete_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AuthLogout200Response>, Integer, Hash)> list_delete_with_http_info(list_id)

```ruby
begin
  # Delete
  data, status_code, headers = api_instance.list_delete_with_http_info(list_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AuthLogout200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->list_delete_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **list_id** | **Integer** |  |  |

### Return type

[**AuthLogout200Response**](AuthLogout200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## list_item_status

> <ListItemStatus200Response> list_item_status(list_id, media_id, media_type)

Item Status

Check if an item is on a list.

### Examples

```ruby
require 'time'
require 'openapi_client'
# setup authorization
OpenapiClient.configure do |config|
  # Configure API key authorization: sec0
  config.api_key['sec0'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['sec0'] = 'Bearer'
end

api_instance = OpenapiClient::DefaultApi.new
list_id = 56 # Integer | 
media_id = 56 # Integer | 
media_type = 'media_type_example' # String | 

begin
  # Item Status
  result = api_instance.list_item_status(list_id, media_id, media_type)
  p result
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->list_item_status: #{e}"
end
```

#### Using the list_item_status_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListItemStatus200Response>, Integer, Hash)> list_item_status_with_http_info(list_id, media_id, media_type)

```ruby
begin
  # Item Status
  data, status_code, headers = api_instance.list_item_status_with_http_info(list_id, media_id, media_type)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListItemStatus200Response>
rescue OpenapiClient::ApiError => e
  puts "Error when calling DefaultApi->list_item_status_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **list_id** | **Integer** |  |  |
| **media_id** | **Integer** |  |  |
| **media_type** | **String** |  |  |

### Return type

[**ListItemStatus200Response**](ListItemStatus200Response.md)

### Authorization

[sec0](../README.md#sec0)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

