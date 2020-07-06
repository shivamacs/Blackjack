# Blackjack - A Gambling Card Game
Equally well known as twenty-one (21). Blackjack is a comparing card game between one or more players and a dealer, where each player in turn competes against the dealer. This project supports only single player and a computer dealer along with the basic features of Blackjack. It is developed entirely using Python GUI library - [**Tkinter**](https://docs.python.org/3/library/tkinter.html).

Here's how it looks like in action:                            
>![blackjack demo](https://github.com/shivamacs/blackjack/blob/master/BlackJack/demo.gif)

## Requirements
- Python 3.6.

## Run
- Clone this repository
- Navigate to the repository folder locally
```
~/../blackjack$ cd BlackJack/venv/src
~/../blackjack/BlackJack/venv/src$ python BlackjackGUI.py
```
## Basic Blackjack Rules
- The goal of blackjack is to beat the dealer's hand without going over 21.
- Face cards are worth 10. Aces are worth 1 or 11, whichever makes a better hand.
- Each player starts with two cards, one of the dealer's cards is hidden until the end.
- To 'Hit' is to ask for another card. To 'Stand' is to hold your total and end your turn.
- If you go over 21 you bust, and the dealer wins regardless of the dealer's hand.
- If you are dealt 21 from the start (Ace & 10), you got a blackjack.
- You will win 2.5 times the bet on having a blackjack (here).
- Dealer will hit until his/her cards total becomes 17 or higher.

## How to play
1. You have to enter the number of chips (gambling currency) you have.
2. Next, you have to enter the number of chips to bet.
3. According to the sum of your cards, you have the options to HIT or STAND.
4. You will win or lose the hand according to game rules.
5. You can play any number of hands until your chips dry out, or you can exit the game anytime.
