# Python Strings [資料來源](https://www.w3schools.com/python/python_strings.asp)



```python
#You can assign a multiline string to a variable by using three quotes
#You can use three double quotes or three single quotes

a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
```

```python
#Get the character at position 5 (remember that the first character has the position 0)

a = "Hello, World!"
print(a[5])
```

```python
#Loop through the letters in the word "apple"

for x in "apple":
  print(x)
  
#a
#p
#p
#l
#e
```
```python
#The len() function returns the length of a string

a = "Hello, World!"
print(len(a))

#13
```
```python
#Check if "free" is present in the following text 

txt = "The best things in life are free!"
print("free" in txt)

#True
```
```python
#Print only if "free" is present

txt = "The best things in life are free!"
if "free" in txt:
  print("Yes, 'free' is present.")

#Yes, 'free' is present.
