# WordDoWord

## _This is our custom ruby library (gem)_   
### Our goals
Сreate a ruby library (gem) with a clean architecture

## Team
1. Danil Eroshenko
2. Feodor Poddubnyak
3. Egor Voronin

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/word_do_word`. To experiment with that code, run `bin/console` for an interactive prompt.

## Installation

Add this line to your Gemfile:

gem 'word_do_word'

And then execute:

bundle install

Or install the library yourself using the command:

gem install word_do_word

Here is an example of how to use the word_do_word library:

require 'word_do_word'
## Documentation

You can find project documentation in the ./doc

## Usage

Use our gem for frequency analysis of text files. The input is the path to the folder with files in .txt format.
Our gem counts data from all files and returns a list of words found in the files, indicating the number of occurrences for each word.
You can install stop sheets and carry out limmetization.

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/word_do_word.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
