# CedPalindrome

ced_palindrome est ma 1ére Ruby gem - Learn Enough Ruby To Be Dangerous 

## Installation

Pour installer ced_palindrome, ajouter cette ligne à votre application Gemfile:

$ gem "ced_palindrome"

Puis installer:

$ bundle install 

or install directly using **gem** :

## Usage

ced_palindrome ajoute une méthode **palindrome?** à la class **String**
$ irb
>> require 'mhartl_palindrome'
>> "honey badger".palindrome?
=> false
>> "deified".palindrome?
=> true
>> "Able was I, ere I saw Elba.".palindrome?
=> true
>> phrase = "Madam, I'm Adam."
>> phrase.palindrome?
=> true

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
