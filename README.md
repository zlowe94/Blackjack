# Blackjack
                             !!! Rules !!!
// Create a card game in which the object is to have the total sum of your card pair equal 21.
// Both the player and dealer start with two cards. 
// The player starts with two cards face up while the dealer deals themself two cards as well (one face up and one face down)
// If the player believes the sum of their card pair is higher than the dealer's they can choose to hold 
// If they want to get closer to 21 they can choose to hit their pair (add an additional card to their total)
// However, if they draw an additional card that takes them over 21 they lose
// *Note* An Ace can equal 1 or 11


// Initial deck will be set up with an array of 52 cards
// There will be four suits in total that have cards valed 1-10
// Each suit will have an Ace that can be used with a value of either 1 or 10
// Face cards ( Jack, Queen, King ) will all have a value of 10

// Shuffle the cards using a randomize function that will bring in a "fresh deck" after each game is won or loss
// Have player input their name as a variable for a more personalized game

// Initial deal has 2 cards to the player and 2 cards to the dealer.
// Both player cards are rendered face up and the dealer has one card face up and one card face down
// Save the value of each deal and compare the stored values using a compare function

Player's turn
// Link a variable to the player's card sum that counts the total number of aces used so we can keep track of the number of times a card can either be 1 or 11
// Player can select to hit or stay
// On stay their turn ends and the dealer's function is ran
// If player busts ( > 21) or gets blackjack (=== 21) render corresponding message

Dealer's Turn
// Use same ace logic from above to account for the number of aces that have already been distributed
// If the dealer's hand is < 17 an additional card will be added
// Check if dealer hand is > player's hand ( or === 21)
// If either condition above is true, display message for dealer win
// If dealer busts deliver message that player wins

Reset
//Add button to clear the game values and reshuffle the deck
// If same player keep name, if different player clear name form
 
Theme 
// USA Baseball or Atlanta Braves?
// Add green background to mimic real card table

