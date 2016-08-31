# Twilreapi::Worker

[![Build Status](https://travis-ci.org/dwilkie/twilreapi-worker.svg?branch=master)](https://travis-ci.org/dwilkie/twilreapi-worker)

A collection of workers for [Twilreapi](https://github.com/dwilkie/twilreapi)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'twilreapi-worker'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install twilreapi-worker

## Workers

### Twilreapi::Worker::Job::OutboundCallJob

Initates an outbound call through DRb.

## Usage

### ActiveJob (Rails)

See [twilreapi](https://github.com/dwilkie/twilreapi)

### Plain Ol' Ruby

See [twilreapi-sidekiq](https://github.com/dwilkie/twilreapi-sidekiq)

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/dwilkie/twilreapi-worker.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

