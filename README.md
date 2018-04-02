# Rules of Set

The game of set has 81 cards. Each card has 4 attributes which are background color, icon color, icon and icon count. Also each attribute has 3 types. For example count can be 1, 2 or 3. Shapes are either cloud, heart or asterisk, and so on. Hence number of cards become 3^4 = 81. 

The objective of the game is to find all the sets.

A set is a collection of 3 cards such that for any given attribute, the 3 chosen cards have either the same or mutually different value of the attribute.

This game comes with infinite mode and daily mode. In infinite mode, every time you find a set, the cards will be replaced by some other cards. In daily mode, a new deck of cards are generated every day and you compete with other players.

To run the game, run the below commands and open localhost:5858 on browser 
```
npm install
node server.js
```