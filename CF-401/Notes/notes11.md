# Notes for class 10

## Stacks and Queues

Queue knows front and end

Stack knows top

linked list knows head

the properties of a class are the actual values you assign to the class

## Code Challange 11

implement a new queue class using two stacks

a queue is a first in first out data structure what goes in comes out in same order

a stack is a last in first out data structure what goes in comes out in reverse order

How could you use a stack to make queue like things?  

you can take everything out of one stack and put it in another stack and then take it out of the second stack and it will be in the same order as it was in the first stack

Logan, Andrew, Anthony, Jared
Moving to a new stack
Jared, Anthony, Andrew, Logan

in the sudo code we are going to use enqueue and dequeue

add your own test and make whiteboard.

## warmup

go through this code and explain it

import random
suits = ('Hearts', 'Diamonds', 'Spades', 'Clubs')
card_names = ('Two', 'Three', 'Four', 'Five', 'Six', 'Seven', 'Eight', 'Nine', 'Ten', 'Jack', 'Queen', 'King', 'Ace')
values = {'Two': 2, 'Three': 3, 'Four': 4, 'Five': 5, 'Six': 6, 'Seven': 7, 'Eight': 8, 'Nine': 9, 'Ten': 10,
          'Jack': 10, 'Queen': 10, 'King': 10, 'Ace': 11}


class Card:
    def __init__(self, suit, value):
        self.suit = suit
        self.value = value

    def __str__(self):
        return f'{self.value} of {self.suit}'


class Deck:
    def __init__(self):
        self.deck = []
        self.dealt = []
        for suit in suits:
            for card in card_names:
                self.deck.append(Card(suit, card))

    def __str__(self):
        return f'{[value for value in self.deck if print(value)]}'

    def deal(self):
        single_card = self.deck.pop(random.randrange(len(self.deck)))
        self.dealt.append(single_card)
        return single_card

## num py arrays

javascript and python are not stricly type languages

numpy arrays are bulit for optemization

you need to know your data type in a numpy array

numpy arrays are not mutable

numpy arrays are not dynamic

numpy arrays are not flexible

numpy arrays are not iterable

python is good at using other languages

numpy was written in c wich is extemely optemized

## Lab 11

need __init__ inside cheesboard class

kaggle is jyupiter notebook

need to make kaggle public and shareable
