# Stringer

Welcome to my new gem, stringer!
It's a simple ruby gem that extends the functionality of Ruby strings

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'stringer'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install stringer

## Usage
Invoke following methods on string instance(s) to achieve desired results.

```spacify```: Concatenates undefined number of strings with a space. 
Example: Stringer.spacify("Oscar", "Vazquez", "Zweig", "Olasaba", "Hernandez", "Ricardo", "Mendoza"), will be converted to "Oscar Vazquez Zweig Olasaba Hernandez Ricardo Mendoza"


```minify```: Minifies the string depending on the argument value and shortens the string up to the number of characters in the argument and adds '...'" 
Example 1: Stringer.minify("Hello, I'm learning how to create a gem", 10)) to ("Hello, I'm...")

Example2: returns the string if the argument is less than the length of the string. That is:
Stringer.minify("Hello", 10)) comes out to be ("Hello")
   

```replacify```: Iterates over a string and replaces each instance a word with a replacement word.
Example: Stringer.replacify("I can't do this", "can't", "can") to ("I can do this")


```tokenize```: Iterates over a string and adds each word into an array.
Example: Stringer.tokenize("I love to code")) come out to be (["I", "love", "to", "code"])


```removify```: Removes each instance of a word.
Example: Stringer.removify("I'm not a developer", "not")) will become ("I'm a developer")


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/vickswift/RubyGem-Stringer. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

