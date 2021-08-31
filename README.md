
This example use the Smiirl Custom Counter as a random generator for a "Lotto game":

# Tenet #

Each player chooses a bet on X digits.

Launch the game turn with the "Roll the dice" button: 
the counter shows the number drawn.

Use the button "Reveal Result" to show won points:

- Each misplaced digit earns 10 points.
- Each well placed number earns 100 points.
- Each well placed number (in addition to a first one) multiplies the score of the round by 2.

# Choose deployment 

You can use an already deployed app or install it locally.

## Use a hosted deployment

- Go to https://frozen-brook-19736.herokuapp.com/index.html.

## Install it in your infrastructure
- ```
  composer install
  ```
- Make shure that `roll.php` is executable.
- Use `index.html` to show the interface.
 
# Setup your parameters
First Choose 
- the number of players, 
- the size X (number of digits) of your counter, 
- the range of the digits.
- the names of players

In https://my.smiirl.com:
- Go to the `Settings` of your counter.
- Change its options to `"PUSH NUMBER"`. 
- Get the `API Parameters` of your counter 
and fill the `Counter Id` and `Counter Token` fields of the interface.

# Let's Play  

