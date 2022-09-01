# Quiz002

'''.py
#Given two numbers A and B Output TRUE if one of them is 20

'''
This is an multiline comment
'''

nA = int(input("Plese enter a number"))
nB = int(input("Plese enter a number"))
print(f"You entered {nA} and {nB}")

output = False
if nA == 20:
	output = True

if nB == 20:
	output = True

if nA + nB == 20:
	output = True

print(f"The answer to the quiz 002 is {output}")
