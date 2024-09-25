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

#Inverted int list
	def invert(lst):
	    lst1 = []
	    for num in lst:
	        lst1.append(num * -1)
	    return lst1

#Total amount of points for the season
	def points(games):
    points = 0
    for i in games:
        if int(i[0]) > int(i[2]):
            points += 3
        elif int(i[0]) < int(i[2]):
            points += 0
        elif int(i[0]) == int(i[2]):
            points += 1
    return points

#Sum of an array
	def sum_array(a):
 	total = 0
    	for i in a:
        	total += i
    	return total
or
	def sum_array(a):
  	return sum(a)

#Checking for 1 number to be even and the other number be false
	def lovefunc( flower1, flower2 ):
    	return (flower1+flower2)%2
or
	def lovefunc( flower1, flower2 ):
    		if (int(flower1)%2 == 0 or int(flower2)%2 == 0) and (int(flower1)%2 != 0 or int(flower2)%2 != 0):
        	return True
    	else:
        	return False

#
	def find_needle(haystack):
  		return 'found the needle at position ' + str(haystack.index('needle'))

#
	def feast(beast, dish):
    		if beast[0] == dish[0] and beast[-1] == dish[-1]:
        	return True
    	else:
        	return False
