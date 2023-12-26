# OpenapiClient::AccountLists200ResponseResultsInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_object_id** | **String** |  | [optional] |
| **adult** | **Integer** |  | [optional][default to 0] |
| **average_rating** | **Float** |  | [optional][default to 0] |
| **created_at** | **String** |  | [optional] |
| **description** | **String** |  | [optional] |
| **featured** | **Integer** |  | [optional][default to 0] |
| **id** | **Integer** |  | [optional][default to 0] |
| **iso_3166_1** | **String** |  | [optional] |
| **iso_639_1** | **String** |  | [optional] |
| **name** | **String** |  | [optional] |
| **number_of_items** | **Integer** |  | [optional][default to 0] |
| **public** | **Integer** |  | [optional][default to 0] |
| **revenue** | **String** |  | [optional] |
| **runtime** | **Integer** |  | [optional][default to 0] |
| **sort_by** | **Integer** |  | [optional][default to 0] |
| **updated_at** | **String** |  | [optional] |

## Example

```ruby
require 'openapi_client'

instance = OpenapiClient::AccountLists200ResponseResultsInner.new(
  account_object_id: 4bc8892a017a3c0f92000002,
  adult: 0,
  average_rating: 7.90183,
  created_at: 2019-08-27 15:13:15,
  description: ,
  featured: 0,
  id: 120174,
  iso_3166_1: US,
  iso_639_1: en,
  name: Test Alpha Sort,
  number_of_items: 6,
  public: 0,
  revenue: 586453267,
  runtime: 644,
  sort_by: 7,
  updated_at: 2023-05-05 16:49:11
)
```

