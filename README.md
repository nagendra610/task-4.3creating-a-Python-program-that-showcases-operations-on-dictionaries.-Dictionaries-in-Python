# task-4.3creating-a-Python-program-that-showcases-operations-on-dictionaries.-Dictionaries-in-Python
Defining a dictionary with key-value pairs of different data types in python
#Create a Dictionary: Define a dictionary with key-value pairs of different data types.({'name': 'Alice', 'age': 30, 'city': 'New York'}
dictionary={'name': 'Alice', 'age': 30, 'city': 'New York'}
print(dictionary)
#Access Values: Access values using keys.
print(dictionary['name'])
print(dictionary['age'])
#Modify Dictionary: Update values, add new key-value pairs, and remove existing pairs.
dictionary['name']= "James"
print(dictionary)
dictionary.pop('city')
print(dictionary)
#Iterate Over Dictionary: Use loops to iterate over keys or values.
for k in dictionary:
    print("KEY:",k)
print(dictionary.items())

