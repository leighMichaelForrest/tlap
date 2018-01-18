# Chapter 1

## Sudoku

while puzzle is not solved:
    pick the box with the most numbers set
    get a list of the numbers not in the box
    choose a row or column with the most solutions in the row or column
    add a number to the empty box where the solution fits
    check the add
    if box does not have all 9 numbers, continue


## Picture Sliding Tile

A sliding puzzle with pictures increases the difficulty in solving the puzzle
because it requires intuition to solve. The image on two tiles may be similar,
but they are not the same, and therefore the solver needs to tell the difference.
A computer may easily solve a number puzzle because it more easily understands integer numbers,
but it needs more programming (artificial intelligence) to determine the order
of picture tiles.


## Sliding Tile Strategy

If the rows are greater than one:
    bubble up the tiles that belong in the first row
    Try to arrange the tiles in order
    work on the next row with the previous steps.


## Sam Loyd

*An old man goes to a bank with a check of $200 and asks the cashier "Give me some one-dollar bills, ten times as many twos and the balance in fives!".*

*What will the cashier do?*

### Have a basic multiple

i.e. 10 two-dollar bills and one one-dollar bills. So you have (10 * 2) + (1 * 1) = 21 dollars.

### Multiply up to two hundred dollars.

21 * 1 = 21

21 * 2 = 42

21 * 3 = 63

21 * 4 = 84

21 * 5 = 105

21 * 6 = 126

21 * 7 = 147

21 * 8 = 168

21 * 9 = 189

### Find one that is a multiple of 5, and note the factors.

21 * 5 is the only one in the list that is a multiple of 5.

### Get the difference of that product and $200

200 - 105 = 95

### Finish the problem

(95 / 5) = 19 five-dollar bills

(5 * 10) = 50 two-dollar bills

(5 * 1) = 5 one-dollar bills

### Conclusion

I would change the wording. The constraints are fairly straight forward. But Sam Loyd lived in the late 19th Century and the early 20th, and the language shows. I would make the language more contemporary to make the problem more familiar.

### Credits

[Math is Fun](https://www.mathsisfun.com/puzzles/the-cashier-s-problem.html)

## Just Jumble Strategy

1. Analyze the cartoon clue.

2. Brainstorm for any connections. The captions are usually punny, so may need some thought.

3. Put in the consonants.

4. If no matches, put the next consonant in first spot.

5. If solution matches, register that solution.

6. The final answer jump out if you have any ideas from the brainstorming.
