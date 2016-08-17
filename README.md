## lights-out-game
The lights out game is based off the wikipedia page - https://en.wikipedia.org/wiki/Lights_Out_(game)

## Tech used
Vanilla JavaScript, HTML and CSS

## Notes, issues and improvements that could be made
- Event handlers were attached in the JavaScript file although you could attach these in the HTML document. I decided to keep the HTML document as bare as possible and to instead only contain the basic HTML structure.
- A cap isn't given on the width and height for the game and doesn't scale well above the screen size by adjusting.
- The display functions are separated from the logic functions so that they are reusable. Only the display functions alter the JavaScript global variable state where as the logical functions only operate on given arguments or return new data structures.
- An algorithm to prevent users from getting unsolvable games hasn't been implemented.
- The displayBoard function re-adds the whole board, this could be improved by only updating the relevant light and adjacent lights in the array and updating only those div elements.
- Going back to vanilla DOM mutations is a lot less fun than using React haha
