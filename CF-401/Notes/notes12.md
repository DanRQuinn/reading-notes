# notes 12 06/27/23

## Morning Warmup

Lists inside of lists and data structures inside of data structures are called nested data structures.

list = ['January', 'February', 'March', 'April', 'May', 'June', 'July', and 'August', 'September', 'October', 'November', 'December']

Given a list of months, print the month and the numerical value of the month


import calendar

months = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]

for month in months:
  month_number = calendar.month_abbr.index(month) + 1
  print(f"{month}: {month_number}")

def add_2(lst):
  for items inlist:
    for i, num in enumerate(items):
      num += 2

Does this get the same result as the in class demo about 40 min into class?

after that he goes over the code challenge then th lab.

the main way to use two stacks like a queue is to move everything from one stack to another stack and then take everything out of the second stack and it will be in the same order as it was in the first stack. by removing the top item of the second stack you are removing the first item that was put in the first stack.

## lab 11

we talk about enumerate and 1 hour in he has some solutions to the lab.

if the coloum or the row was the same as the other queen then It would know that it is under attack

this gets more complicated with the diagonal. instead of rows and coloums you check the square values, 1,1 2,2 3,3 4,4 5,5 6,6 7,7 8,8 

as long as its in the bounds of the actual board you can check the diagonal.look at 10:05 for the diagonal sulution


## break then pandas

from kaggle you can add data fromn the side bar. 

today it will be cereal.csv
use markdown to import the data look at around  10 25 for what he adds.

filename="/kaggle/input/80-cereals/cereal.csv"
df = pd.read_csv(filename)

------------

df.info()

------------

df.head(10) tolook at the first 10

or

df.tail(10) to look at the last 10

------------

df['name].head(10) to look at the first 10 of the name coloum

or

df[ ['name', 'calories'] ] to look at the name and calories coloums

------------

sf[['name', 'sugars', 'rating']].sort_values('rating', ascending=False).head(10) to look at the name, sugars, and rating coloums sorted by rating in descending order and look at the first 10

------------

ave_carbo = df['carbo'].mean()
print(ave_carbo)

------------

median_carb = df['carbo'].median()
print(median_carb)

------------

min_carb = df['carbo'].min()

or

max_carb = df['carbo'].max()

## 2nd break more pandas

crab_less_ten = df[['carbo'] < 10]
print(carb_less_ten)


## lab 12 

he goes over assignment

assingment uses vgsales.csv

use the questions as markdown if it seems appropriate.

look at the data first and see which questions you want to ask

[label](https://www.kaggle.com/rogerhuba/401d22-cereal)

[label](https://www.mathsisfun.com/data/standard-deviation.html)

## code challenge 12

create a class called animal shelter that has a queue for dogs and a queue for cats. the class should have an enqueue method that takes in a dog or a cat and adds it to the appropriate queue. the class should have a dequeue method that takes in a preference of dog or cat and returns the first dog or cat in the queue. if the preference is not dog or cat then return null.

hit the way to do that is instead of dqing the value you want to dq the whole queue and then requeue the values that you dont want to dq. set up a vairable that says this person was first in line. then dq the whole queue and requeue the values that you dont want to dq. then return the person that was first in line.
