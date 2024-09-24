#Input a string return int
def string_to_number(s):
    # ... your code here
    try:
        return int(s)
    except (ValueError):
        return "Input is not valid " 

#String cutter prints everything but first and last letter
def remove_char(s):
    return s[1 : -1]

#multiplying all elements in a array by said elements 1*2*3*4=
def grow(arr):
	product = 1
	for i in arr:
		product *= i
	return product

 #return the lowest value within a array
 def findSmallestInt(arr):
    min = arr[0]
    for item in arr:
        if min > item:
            min = item
    return min

#Rock paper scissors function
def rps(p1, p2):
    beats = {'rock': 'scissors', 'scissors': 'paper', 'paper': 'rock'}
    if beats[p1] == p2:
        return "Player 1 won!"
    if beats[p2] == p1:
        return "Player 2 won!"
    return "Draw!"
    or
    def rps(p1, p2):
    if p1 == p2:
        return "Draw!"
    elif p1 == 'rock' and p2 == 'scissors':
        return "Player 1 won!"
    elif p1 == 'scissors' and p2 == 'paper':
        return "Player 1 won!"
    elif p1 == 'paper' and p2 == 'rock':
        return "Player 1 won!"
    else:
        return "Player 2 won!"

#Function to do math with 2 values and a operator
    def basic_op(operator, value1, value2):
    answer = 0
    if operator == '+':
        answer = value1 + value2
    elif operator == '-':
        answer = value1 - value2
    elif operator == '*':
        answer = value1 * value2
    elif operator == '/':
        answer = value1 / value2
    return answer

    
