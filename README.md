PlayBook
========

A collection of recipes/patterns that we have found useful, influenced by ThoughtBot's PlayBook

## Intial thoughts/topics
- Limit long running feature branches
- Prefer single quotes over double
- Use Interactors



## Behavior Driven Development
- Avoid writing test just to write tests!

Tests should be written to express desired behavior from the outside-in. First we start with how the end user will expect the app to behave. Currently we are doing this through Rspec feature specs.

```ruby
# specs/features/listings/reviewing_spec.rb
require 'spec_helper'

describe 'Listings' do
  example 'reviewing' do

    
  end
end

```

