# Spp

`spp` is super pretty print library.  
It is useful for log output etc.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'spp'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install spp

## Usage

How to use spp is easy.

``` ruby
Spp::spp('hoge')
=>
========== START ==========
"hoge"
========== E N D ==========

# same as below
# puts "========== START =========="
# pp 'hoge'
# puts "========== E N D =========="
```

You can also specify modifiers with arguments.
``` ruby
Spp::spp('hoge', 'start', 'end', '😃' * 5)
=>
😃😃😃😃😃 start 😃😃😃😃😃
"hoge"
😃😃😃😃😃 end 😃😃😃😃😃
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/Madogiwa0124/spp. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Spp project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/Madogiwa0124/spp/blob/master/CODE_OF_CONDUCT.md).
