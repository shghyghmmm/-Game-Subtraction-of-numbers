# -Game-Subtraction-of-numbers
In this game, we get a two-digit number, then subtract the second digit from the first digit.


the_number= int(input())
first_digit=round(the_number/10)
second_digit=the_number-first_digit*10
print(first_digit-second_digit)
