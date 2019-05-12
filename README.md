# ruby-rails-utils
A note of some useful ruby utils

##### Create a hash of query parameters from url
```ruby
Rack::Utils.parse_query URI.parse(url).query
```
