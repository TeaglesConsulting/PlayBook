## Behavior Driven Development
- Avoid writing test just to write tests!

Tests should be written to express desired behavior from the outside-in. First we start with how the end user will expect the app to behave. Currently we are doing this through Rspec feature specs.

```ruby
# specs/features/listings
require 'spec_helper'

```