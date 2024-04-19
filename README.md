# Pyhton-Fundamentals-for-Data-Analyst-2

### Calculate the sum of values
<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/4e73c1d7-0894-4352-addb-0fd140aadf41" /></div>

### Unique and Nunique
`Unique` and `Nunique` in the context of Python refer more to the presence of repeating or non-repeating elements in a data structure, and how to identify and manipulate those elements.
- Unique (non-repetitive)
To get the unique elements of a data structure like list, we can use set(). Set is a data structure that contains only unique elements
<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/b0135ff9-e9cc-4349-a71e-24b984b17c5a" /></div>

- Nunique (Repetitive or Duplicate) 
To get repeated or duplicate elements from a data structure, we can use various approaches, for example by using certain functions or modules, or by manually looping through the data structure.
<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/ff0ce817-24bf-472f-a7c6-9779fe2c425d" /></div>

### Call a specific column
<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/941512de-9504-40b8-ac31-08deeb345a34" /></div>
                        
As another example You can use less than `<`, more than `>`, less than equal to `<=`, not equal to `!=`. Customize the data type with the function to be used. You can also call by combining the data types used in one line. 

<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/8920f699-2b2a-4f9e-91e5-f0bc1eb886fe" /></div>

## Random library
Random library in Python is used for generating random numbers. It provides various functions for generating random integers, selecting random elements from a list, shuffling sequences, and more.
 you can use this Syntax : 
 `import random
    print(random.random())`

- Generate Random Numbers in Python
random.randint() method is used to generate random integers between the given range.
`Syntax: randint(start, end)`

<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/d76b9e1a-4716-4cc3-81d0-11023142313b" /></div>
 

- Python random.sample() function is used to return a random item from a list, tuple, or string.
  `Syntax: random.sample(sequence, length)`

<div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/a71a951c-b023-4478-9cc0-bc424cf4b927" /></div>
 
## Open, Read and Close File TXT
- Open
To open the file, use the built-in open() function. The open() function returns a file object, which has a read() method for reading the content of the file.
`Example Syntax : workfile = open ('stok.txt' , 'r')` 
  
- Read
  In the code snippet above, we read the content of the file using the read() method. 
The file content is stored in the file_content variable.
  <div align="center"><img src="https://github.com/difasafrina/Pyhton-Fundamentals-for-Data-Analyst-2/assets/113273578/058a7cd3-b2d6-4464-8847-9f660097f680" /></div>
  
- Close
`Syntax for Close File : workfile.close()`
