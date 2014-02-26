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

Actionable data will set Teagles apart from others. Providing rich data allows us to form the best decisions for our client's business. In addition, it builds our clients trust in the form of transparency, showing decisions based on fact, and inviting collaboration. Our client's trust in us is the keystone in our business relations.

[Metrics Playbook](/metrics)
