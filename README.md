# Python-programming-for-beginners-
Python practice for list and algorithms 
# Lists are useful because they allow you to ​store multiple pieces of data in a single variable. ​In the security profession, you will work with a variety of lists. ​For example, you may have a list of IP addresses that have accessed a network, and ​another list might hold information on applications that ​are blocked from running on the system. ​Let's recap how to create a list in Python. In this case, ​the items in our list are the letters A through E. ​We separate them by commas and surround them with square brackets. ["a","b","c","d","e"]
# your_list[1] , we start counting the elements in the list at zero and not at one.
# Extract from the list 
your_list = ["a","b","c","d","e"]
print(your_list[1])
b
# list concatenation, Similar to strings, we can also concatenate lists with the plus sign. ​List concatenation is combining two lists into one by placing ​the elements of the second list directly after the elements of the first list.
# concatenate two lists
your_list = ["a","b","c","d","e"]
number_list = [1,2,3,4]
print(your_list+number_list)
[a,b,c,d,e,1,2,3,4]
# changing a specific element ,,,,,We combine what we learned about bracket notation ​with what we learned about variable assignment.      your_list = ["a","b","c","d","e"]                                                                                                       your_list[1] = 7 change the second element in your_list, ​which is the string "b", to the number 7,we place an equals sign to indicate ​we are reassigning this element of the list.
# ['a',7.'c','d','e']
# .insert()   ,The insert method adds an element in a specific position ​inside a list. The method takes two arguments: ​the first is the position we're adding the element to, and ​the second is the element we want to add.
# Use the insert method                                                                                                                  your_list = ["a","b","C","d","e"]                                                                                                       your-list.insert(1,7) The first argument is the position where we want to insert ​the new information.In this case,we want to insert into index 1.                                                                                                              print(your_list),,,['a',7,'c','d','e']
# .remove() ,,,method,he removed method ​removes the first occurrence of a specific element in the list. ​Unlike insert, the argument of removed is not an index value. ​Instead, you directly type the element you want to remove. ​The remove method removes the first instance of it in the list
# Use the remove method                                                                                                                  your_list = ["a","b","c","d","e"]                                                                                                       your_list.remove("d")                                                                                                                     print(your_list)   ==== ['a'.'b','c','e']
