# Python Strings [資料來源](https://www.w3schools.com/python/python_strings.asp)



```python
#You can assign a multiline string to a variable by using three quotes :
#You can use three double quotes or three single quotes

a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
```

```python
#Get the character at position 5 (remember that the first character has the position 0) :

a = "Hello, World!"
print(a[5])
```

```python
#Loop through the letters in the word "apple" :

for x in "apple":
  print(x)
  
#a
#p
#p
#l
#e
```
```python
#The len() function returns the length of a string :

a = "Hello, World!"
print(len(a))

#13
```
```python
#Check if "free" is present in the following text :

txt = "The best things in life are free!"
print("free" in txt)

#True
```
```python
#Print only if "free" is present :

txt = "The best things in life are free!"
if "free" in txt:
  print("Yes, 'free' is present.")

#Yes, 'free' is present.
```
```python
#Check if "expensive" is NOT present in the following text :

txt = "The best things in life are free!"
print("expensive" not in txt)

#True
```
```python
#print only if "expensive" is NOT present :

txt = "The best things in life are free!"
if "expensive" not in txt:
  print("No, 'expensive' is NOT present.")
  
#No, 'expensive' is NOT present.
```

```python
#Create a List :

thislist = ["apple", "banana", "cherry"]
print(thislist)

#['apple', 'banana', 'cherry']
```
```python
#Lists allow duplicate values :

thislist = ["apple", "banana", "cherry", "apple", "cherry"]

print(thislist)

#['apple', 'banana', 'cherry', 'apple', 'cherry']
```
```python
#Print the number of items in the list :

thislist = ["apple", "banana", "cherry"]
print(len(thislist))

#3
```
```python
#String, int and boolean data types :

list1 = ["apple", "banana", "cherry"]
list2 = [1, 3, 7, 9, 5]
list3 = [True, False, False]

print(list1)
print(list2)
print(list3)

#['apple', 'banana', 'cherry']
#[1, 3, 7, 9, 5]
#[True, False, False]
```
```python
#What is the data type of a list?

mylist = ["apple", "banana", "cherry"]

print(type(mylist))

#<class 'list'>
```
```python
#Using the list() constructor to make a List :

thislist = list(("mango", "banana", "cherry")) # note the double round-brackets
print(thislist)

#['mango', 'banana', 'cherry']
```
```python
#Create and print a dictionary :

thisdict =	{
  "epic": "Poop",
  "human": "Hotdog",
  "year": 1964
}
print(thisdict)

#{'epic': 'Poop', 'human': 'Hotdog', 'year': 1964}
```
```python
#Print the "human" value of the dictionary :

thisdict = {
  "human": "Poop",
  "Food": "hotdog",
  "year": 1987
}
print(thisdict["human"])

#Poop
```
```python
#Duplicate values will overwrite existing values :

thisdict = {
  "human": "poop",
  "food": "hotdog",
  "year": 1987,
  "year": 2022
}
print(thisdict)

#{'human': 'poop', 'food': 'hotdog', 'year': 2022}
```
```python
#Print the number of items in the dictionary :

thisdict = {
  "human": "poop" ,
  "Food": "hotdog",
  "year": 1987,
  "year": 2022
}
print(len(thisdict))

#3
```
```python
#String, int, boolean, and list data types :

thisdict = {
  "human": "poop",
  "hotdog": False,
  "year": 1987,
  "colors": ["green", "purple", "brown"]
}

print(thisdict)

#{'human': 'poop', 'hotdog': False, 'year': 1987, 'colors': ['green', 'purple', 'brown']}
```
```python
#Print the data type of a dictionary :

thisdict = {
  "human": "poop",
  "food": "hotdog",
  "year": 1989
}
print(type(thisdict))

#<class 'dict'>
```
