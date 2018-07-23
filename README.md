# Deck-of-cards-library
A javascript Library for a deck of cards.

To import the library:

const deck = require('./lib.js')

To generate the deck:

Deck.generate_deck()

To print the array that holds all the cards:

Deck.print_deck()

To shuffle the deck:

Deck.shuffle()

To deal a card:

Deck.deal()

To return the recent dealt card to the top of the deck:

Deck.replace()

To remove the current deck:

Deck.clear_deck()


Class Deck that holds all of the function, which has a constructor that creates empty arrays that later generate the deck.
Then there is a function to generate the deck which recursively moves over our suits which creates a new card object for each of the values that are respective to the suits.
Then there is a function to print everything to the console.
Then there is a function to deal the deck.
Then there is a function to return the most recent played card back to the deck.
Finally there is a function that clears the deck.

![card lib in action]()
