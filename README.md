Blackjack is a card game which involves dealing an initial hand of 2 cards, followed by a sequence of single-card deals, or "hits", until the player either "holds", earns a score of 21 points (using rules described below), or "busts" (earns a score over 21). There are more rules for the actual game, but let's keep it simple for this assignment.

Write a Java FX application which repeatedly performs an initial 2-card Blackjack deal using a set of 52 card images.

The required png image files are organized in a folder and attached as "52card.zip" to this assignment.

A "deal" button should be provided which, when pressed, causes the deck to be randomized, or "shuffled" -- HINT: use the Collections "shuffle" method -- and display the two cards. For instance, if the cards are stored in an ArrayList named cardList, call java.util.Collections.shuffle(cardList);

Once the cards are dealt, the current total point value should be displayed. The point value is determined as follows:

Ace: 11 points (unless 2 Aces are dealt, in which case one of those Aces counts as 1 point, for a total of 12)
Face value of 2-10: 2-10 points based on face value
Jack, Queen, or King: 10 points
When the score is 21 points, highlight the score in red.

The files in the 52card folder are organized based on filename as shown here ("1.png" is the Ace of Spades, "13.png" is the King of Spades,  "14.png" is the Ace of Hearts, etc). 

![](images\fileindices.png)

You will need to devise an algorithm to encode the point values of the cards based on the current file index. How you do this is up to you, but you may not rename the files!

Sample Output:

![](images\b1.JPG)
![](images\b2.JPG)
![](images\b3.JPG)