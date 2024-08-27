# Alphabet Soup Problem
# make the user input the string
user_input = input("Enter string: ")
# using the join method and sorted function, to sort the string alphabetically
sorted_string = ''.join(sorted(user_input))
# output statement
print("Sorted letters: ", sorted_string)
