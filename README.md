PlayBook
========

A collection of recipes/patterns that we have found useful, influenced by ThoughtBot's PlayBook

## Mission/Purpose
- Business enhancing software
- Our software maximizes the input to output ratio!
  - We want our software to to provide the maximum amount of business value with least amount of input. Given two options, pursue the option that will save our clients time, whenever possible.


## Intial thoughts/topics
- Avoid long running feature branches
- Prefer single quotes over double
- Use Interactors
- MailGun as our Emailer services
  - For Sending/Receiving we setup a mg.example.com subdomain.
  - Also each dev should get their own subddomain for testing purposes.
- Keen.io for Tracking purposes
- install Google Analytics for every Project
- New Relic
- Static Sites with Middleman
- Sites requiring the client to edit the content should be built in Harmnoy
  - Prototype Harmony sites in MiddleMan
- Prefer MiddleMan Over Harmony
- MongoDB/Mongoid
- Thin





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

## Metrics
We believe the collection and analysis of rich, actionable data will set Teagles Consulting apart from the competition. In addition to providing the foundation for our consulting services this information is pivotal in building client's trust in the form of transparency, collaboration, and insight. Our client's trust in Teagles Consulting is the keystone of all our business relationships. Review the [Metrics Playbook](/metrics) for more details.
