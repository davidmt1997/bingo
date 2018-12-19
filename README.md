# bingo

This was assigned to me as a final project for my Client Side Programming class ar NMU.

We had to make an app using Node.js and storing some info in a Mongo database. I decided to make a bingo app. It consists of a login page, in which new users are added to the database. Next there's the home page, in which each client can purchase up to 5 bingo cards, each of them costs 20 virtual coins (amount of money also stored in the database) and they can start playing.

The server is in charge of approving the purchase of cards and next, when the game starts, generating random numbers. 

Once the game is going on, each client has some buttons that they can press to claim that they have a vertical line, four corners, postage stamp(4 numbers forming a square) or the whole card(bingo). The client will receive an amount of money once they press the button and their claim is correct. The game finishes once a client calls bingo, and the amount of money earned altogether with a victory is updated in the databse.
