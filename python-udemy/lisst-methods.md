# append function
adding something to the var
list1 = [1,2,3,4,5]
newlist = list1.append[100]
print(newlist)     or print(list.append[100])

# insert function
adding at specified index location
list = [1,2,3,4,5,6]
newlist = list.insert(2,50)
print(newlist)     output : 1,50,3,4,5,6

# extend function
it is function like append but we can add more values at atime to the var
list = [1,2,3,4,5,6]
newlist = list.extend([100,200,300])
print(newlist)    output : 1,2,3,4,5,6,100,200,300

# clear function
it is delete or removes whatever in the list
list1 = [1,2,3,4,5,6]
print(list1.clear())    output : []

# remove function
Yes, remove() removes the first matching value/object. It does not do anything with the indexing
it just remove the specified value
list = [1,20,30,40,5,6]
newlist = list.remove(20)
print(newlist)    output : [1,30,40,5,6]

# pop function
pop removes the item at a specific index and returns it.
list = [10,20,30,40,50,60]
newlist = list.pop(1) 
* pop take atmost one argument        ** it removes the 1 index value
print(newlist)      output : [10,30,40,50,60]

# del removes the item at a specific index.
list = [10,20,30,40,50,60]
del list[1:6:2]
list = newlist
print(newlist)     output : [10,30,50]


# way to delete the elements in list
If you want to delete a specific object in the list, use remove method.
If you want to delete the object at a specific location (index) in the list, you can either use del or pop.
Use the pop, if you want to delete and get the object at the specific location.
 
# index function
it is used to find index of the given object or argument
list = [10,20,30,40,50,60]
print(list.index(30))
* output : 2

# count function
it counts the no of occurences in list
list = [10,20,30,40,50,60,20,50,60]
print(list.count(60))
* output : 2 

# sort function
list = [10,25,65,30,38,33]
list.sort()
print(list)
* output : [10, 25, 30, 33, 38, 65]

# reverse function
it reverse the list
list = [10,25,65,30,38,33]
list.reverse()
print(list)
* output : [33,38,30,65,25,10]

# range function
Python range() generates the integer numbers between the given start integer to the stop integer. range mostly used in for-loops.
* range syntax : range(start, stop, step)
print(list(range(1,100)))
output : it prints from 1 to 99

# .join function
The join() is a string method which returns a string concatenated with the elements of an iterable.
string.join(iterable)
test = {'Python', 'Java', 'Ruby'}
separator = '->->'
print(separator.join(test))
* output : Python->->Ruby->->Java