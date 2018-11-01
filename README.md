### ffaker
---
https://github.com/ffaker/ffaker

```
gem install ffaker
require 'ffaker'


```

```ruby
require 'ffaker'
FFaker::Name.name
FFaker::Internet.email

FFaker::Name.unique.name

FactoryGirl.define do
  factory :project do
    name { FFaker::Name.name }
    no { FFaker::Product.model }
  end
end

project_just_created = create(:project)
project_just.created.name

```

```
```


