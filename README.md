# PhoneControls
Form a game controller for a JS game from multiple devices all connected to node.js server over the LAN

This is currently deployed at [http://phone-controls.herokuapp.com](http://phone-controls.herokuapp.com)

That URL launches the main game, which can be played using the keyboard.

To connect another device as a key, add that key's ascii value after the URL, like so:
[http://phone-controls.herokuapp.com/38](http://phone-controls.herokuapp.com/38)
(This will be an up arrow input)

Clicking or tapping on the page of the remote key input will simulate that key event in the game.

ASCII Values you might need:
* Left arrow: 37
* Up arrow: 38
* Right arrow: 39
* Down arrow: 40
* Spacebar: 32
* A: 65
* B: 66
* S: 83

You can modify the index.html with anything that uses key inputs as long as the jQuery and Socket code remain intact.
