# Phase 1 Project Portfolio: Ruby API + Cli

This gem was generated using
```ruby
bundle gem [gemname]
```

All files are generated, however you will to make edits to the gemspec file before running the setup. 
Course code for  Ruby is in the `lib/`. 
To experiment with that code, run `bin/console` for an interactive prompt.


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'mdolce_p1_api'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install mdolce_p1_api

## Usage Requirements

This is a project portfolio for students attending Flatiron School

## Project Requirements

-[ ] Provide a [CLI](https://github.com/learn-co-curriculum/cli-interfaces-readme#program-loop)
 
-[ ] Your [CLI application](https://github.com/learn-co-curriculum/ruby-cli-applications-readme) must provide access to data from a web page.
 
-[ ] The data provided must go at least one level deep. A "level" is where a user can make a choice and then get detailed information about their choice. Some examples are below:
    - Movies opening soon - Enter your zip code and receive a list of movies and their details.
    - Libraries near you -  Enter your zip code and receive a list of libraries and their details.
    - Programming meetups near you - Choose from an events list and receive details.
    - News reader - List articles and read an article of your choosing.
    
-[ ] Your CLI application should not be too similar to the Ruby final projects (Music Library CLI, Tic-Tac-Toe with AI, Student Scraper). Also, please refrain from using [Kickstarter](https://github.com/learn-co-curriculum/scraping-kickstarter) as that was used for the scraping 'code along'.
 
-[ ] Use good OO design patterns. You should be creating a collection of objects, not hashes, to store your data. *Pro Tip: Avoid scraping data more than once per web page - utilize objects you have already created. It will speed up your program!*

## [<a id="requirements">Flatiron School Project Requirements</a>](REQUIREMENTS.md)


## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/mrsdo/mdolce_p1_api.


## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
