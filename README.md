# ruby-rails-utils
A note of some useful ruby utils

```ruby
# Create a hash of query parameters from url
Rack::Utils.parse_query URI.parse(url).query

# Decode query parameters
URI.decode(query)
```
