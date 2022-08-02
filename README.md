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

Lists in python are very flexible,
you can see in the code above you can see that `mixed_list` contains integers, strings, floats, and a list. 


# Tuple
- Tuples are immutable - cannot make changes
- Syntax for tuples is ()
- use case of tuples is data which doesnt get changed
- e.g. date of birth, place of birth, planet inhabited

```
# creates a tuple
essentialdata = ("city", "DOB", "planet")
print(essentialdata)

# prints type
print(type(essentialdata))


# Tuple is array, arrays start at 0 (indexing)
print(essentialdata[1]) # outcome is "DOB"


# essentialdata[2] = "galaxy"    You cant do this, tuple is IMMUTABLE

```



tuples can be mixed
```
mixedtuple = ("string", 7, 3.13, [1, 3, 5, 8])

print(mixedtuple)

print(type(mixedtuple))
```
this returns:

![image](https://user-images.githubusercontent.com/110176257/182384903-829492d8-3a50-48a9-90b9-1c47d3bb2476.png)

# Dictionaries (Dict)
- syntax is {} with : to signify key value pair
 ```
devopsstudents = {
    "key" : "value",
    "name" : "maiks"

}

print(devopsstudents)
print(type(devopsstudents))
```
This code returns:

![image](https://user-images.githubusercontent.com/110176257/182385800-f7bf49e9-c89a-4f43-ad79-6b3d5ce064f7.png)

```
devopsstudents = {
    "key" : "value",
    "name" : "maiks",
    "stream" : "tech",
    "completed_lessons" : 3, # different data types allowed
    "completed_lesson_names" : ["lists", "tuples", "dictionaries", "operators", "built-in methods"]

}
devopsstudents.__delitem__("stream")
devopsstudents["completed_lessons"] = 2
devopsstudents["completed_lesson_names"].remove("operators")
print(devopsstudents)


```

this returns:

![image](https://user-images.githubusercontent.com/110176257/182390074-4932cd88-47cd-4c85-90ea-df2d29e71c00.png)

