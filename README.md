# Data collections
## Lists, Tuples, Dictionaries


### Lists
#### What are lists?
- lists are a simple array in python
- correct syntax []
- lists are mutable
- ARRAY INDEX START AT 0 

```
shopping_list = ["bat", "milk", "bread"]
print(shopping_list)
# find out the type of shopping list
# find out the len of shopping list

print(len(shopping_list))
print(type(shopping_list))
```
code runs and returns this:

![image](https://user-images.githubusercontent.com/110176257/182355574-a208e5b6-8c24-41ce-98f9-d2e49d66840d.png)

#### Next we learn to add to a list, delete from a list, and replace items in a list:

```
# how to add to list
shopping_list.append("oreos")
print(shopping_list)

# how to delete from list
shopping_list.remove("milk")
print(shopping_list)

# how to replace an item
shopping_list[0] = 'milk' # replaces bat with milk 
print(shopping_list)
```
This code will return the following:


![image](https://user-images.githubusercontent.com/110176257/182364255-c678b747-1940-4707-bb90-8aeb98ac9941.png)

#### Next we show that a list can contain many different data types
Lists can even contain other lists:
```
# creating a list with different data types
mixed_list = [1, 2, 3, 3.14, "one", "two", "three", ["this", "is", "a", "list"]]
print(mixed_list)


# print index 2 and 3 from the mixed list
print(mixed_list[1], mixed_list[2]) # outcome would be 2 3
print(mixed_list[1:3]) # prints a list with 2 and 3
```
This code returns:

![image](https://user-images.githubusercontent.com/110176257/182365520-44f42a05-4be3-472e-86c7-ee5a6f957f39.png)




