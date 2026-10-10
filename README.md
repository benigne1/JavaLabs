
# Individual Lab 1

Reg Number: 225062986

## What is this?

Two small Java programs.

1. **BicycleRental.java** - tells you how much to pay for renting a bicycle.
2. **MushroomGuesser.java** - guesses a mushroom from your answers.

## How to run

1. Open the folder in a terminal.
2. Type this to prepare the program:

       javac BicycleRental.java

3. Type this to start it:

       java BicycleRental

For the mushroom program, use `MushroomGuesser` instead of `BicycleRental`.

## Program 1: Bicycle Rental

You type:
- the hour you start (0 to 23)
- the hour you stop (1 to 24)

The program shows how much you pay.

Prices for each hour:
- 0 to 7 and 21 to 24: 500 RWF
- 7 to 14 and 19 to 21: 1000 RWF
- 14 to 19: 1500 RWF

Example:

    Start hour: 6
    End hour: 8
    You pay: 1500 RWF

## Program 2: Mushroom Guesser

Think of a mushroom. The program asks questions and finds it.

Type **1** for yes and **2** for no.

Example:

    Does it grow in a forest? 1
    Does it have a convex cup? 2
    Does it have gills? 2
    Cepe de bordeaux
