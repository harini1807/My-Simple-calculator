print("1-addition")
print("2-subtraction")
print("3-multiplication")
print("4-division")
option=int(input("Enter the operation to be performed:"))
if (option in [1,2,3,4]):
	num1=int(input("Enter number1:"))
	num2=int(input("Enter number2:"))
	if option==1:
		result=num1+num2
	elif option==2:
		result=num1-num2
	elif option==3:
		result=num1*num2
	elif option==4:
		result=num1//num2
else:
	print("Invalid operator")
print("The result of the operation is:",result)
	
	# My-Simple-calculator
My first program in github
