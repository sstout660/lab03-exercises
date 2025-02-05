#Welcome to lab03 :)

#Find All Duplicates:
#Write a function (or static method in the case of Java) that accepts a list of integers and returns a list of only those integers that appear more than once.

#Describe Different Approaches to Solving This Problem
#Describe the two different ways to figure out all of the duplicate values of a list of integers in english. The first solution is the nested loop solution. The second solution is to use a dictionary or a map (similar to the containsPair method we wrote in class. Describe both in as much detail as you can (with no code) and describe the trade-offs between the two solutions.

        The most straightforward method (in my opinion) to figure out all of the duplicate values of a list of integers is to use a nested loop to compare each value with all of the values that come after it in the list. While this is easy to conceptualize and code, it is not very efficient, requiring the function to iterate through the entire list (almost) n^2 times.

        Another approach would be to convert the list of integers into a hashmap one at a time, and checking if each integer is already included. If it is, we add that number to the "duplicates" list. This way we only have to iterate through the list once