# CedPalindrome

ced_palindrome est une simple gem Ruby - Learn Enough Ruby To Be Dangerous 

## Installation

Pour installer ced_palindrome, ajouter cette ligne à votre application Gemfile:

$ gem "ced_palindrome"

Puis installer:

$ bundle install 

or install directly using **gem** :

$ gem install ced_palindrome

## Usage

ced_palindrome ajoute une méthode **palindrome?** à la class **String**
et peut-être utilisé comme suit:

$ irb
>> require 'ced_palindrome'
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
