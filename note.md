```ruby
ActiveModelSerializers::Adapter::Attributes#serializable_hash
# call
ActiveModel::Serializer#serializable_hash
# call
ActiveModel::Serializer::Association#serializable_hash
# call
ActiveModel::Serializer#serializable_hash
or call 
# ActiveModel::Serializer::CollectionSerializer#serializable_hash
```


```ruby
# Active model 
ActiveSupport::ToJsonWithActiveSupportEncoder#to_json
AEncoding.json_encoderctiveSupport::JSON.encode 
ActiveSupport::JSON::Encoding::JSONGemEncoder#encode
```

```ruby
ActiveModelSerializers::Adapter::Base#as_json
```
