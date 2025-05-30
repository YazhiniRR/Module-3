# Module-3
# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.
[153,147,124,102]


## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
l=[153,147,124,102]
sum=0
for i in l:
     sum=sum+i
print(sum)
```

## Output
![image](https://github.com/user-attachments/assets/7e4cd5f4-d487-4fb7-9834-61832ec5b8c8)


## Result
Thus the program that calculates the **sum of all elements** in a list has been successfully excuted.


# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
items=['goal','new','user','sit','eat','dinner']
filtered_items=[item for item in items if 'e' not in item]
print(filtered_items)
```
## Output
![image](https://github.com/user-attachments/assets/fdf76a99-c594-4186-ba89-462fd3a37aa2)

## Result
Thus program that filters out and returns all elements from a list has been excuted successfully.


# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Receive input string s.
3. Slice the string into two parts
8. Print new.

## 💻 Program
```
def remove(s):
    new=s[:3]+s[3+1:]
    print(new)
```

## Output
![image](https://github.com/user-attachments/assets/0c5cc3ba-c17d-46a3-901e-4d43d9217890)

## Result
Thus the program that accepts a string and removes the character at a specified index has been executed successfully.


# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"civic"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"civic"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
def palindrome(a):
    l=[]
    for i in a:
        l.append(i)
    l2=l[::-1]
    if l==l2:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
string =input()
palindrome(string)
```
## Output
![image](https://github.com/user-attachments/assets/58026bde-fd16-408d-961a-4b0dd5b2e87d)

## Result
Thus the program to check whether the string `"civic"` is a **palindrome** or not has executed successfully.


# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
t = ("s", 8, "a", "v", "n", "g", "u", "r", "c", "e")
print(8 in t)
print('n' in t)
```

## Output
![image](https://github.com/user-attachments/assets/ed7224d4-d29a-467a-b9db-05c4f929c8ab)

## Result
Thus the program that checks if the element 'n' and the element 8 exist within a given tuple has been executed successfully.


