# Zeno

Zeno is the scaffolder for ETA/OS. It is an application which can be used
by developers to quickly generate new ETA/OS projects (i.e. setup a quick
project structure).

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'zeno'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install zeno

## Usage

To generate a new ETA/OS application run:

```bash
zeno app --root ../relative/path/to/etaos <application-name>
```

If you want to read the full usage documentation, run
```bash
zeno --help
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then,
run `rake spec` to run the tests. You can also run `bin/console` for an 
interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`.
To release a new version, update the version number in `version.rb`, and then
run `bundle exec rake release`, which will create a git tag for the version,
push git commits and tags, and push the `.gem` file to
[rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on [GitLab](https://git.bietje.net) at
https://git.bietje.net/etaos/zeno. This project is intended to be a safe,
welcoming space for collaboration, and contributors are expected to adhere to
the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

