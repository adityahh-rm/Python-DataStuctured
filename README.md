## PYTHON DATA TYPE : DATA STRUCTURE
-----
There are 4 types of Data Structures in python, those is :
1.  **List** 
2.	**Tuple** 
3.	**Set**
4.	**Dictionary** </br>

That are used to store and organize the data in an efficient manner. We can also use these data types to **Slicing the data**. **Slicing** itself is a technique of selecting data from a data set.

### Here’s what you’ll learn in this Documentation :
* Unordered sub-list. You’ll cover the important characteristics of lists, tuples, sets, and dictionary. </br>
*	You’ll learn how to define them and how to manipulate them. </br>
*	You’ll learn how to Slicing the data. </br>
*	When you’re finished, you should have a good feel for when and how to use these object types in a Python program. </br>

#### Leggoo….

## LIST [ ]
-----
List is a type of sequence data set and its mutable. Lists need not be homogeneous and useful tool for preserving a sequence of data and further iterating over it. List can be represented by ‘[ ]’. </br></br>
Here's how to declare a List : </br>
```
  listData = [“Alpha”, 21, 3.6, “Beta”]
``` 
### Adding Data In List [ ]
We can add data at the end of the list or in the middle of the list.
* **.append(x)**
* **.insert(i, x)**
* **.extend(x)**
### Remove Data in List [ ]
We can delete data of the list.
* method **del**
* **.remove()**
* **.pop()** </br>

You can see our Documentation above, to find out how to use it. And also find another functions which we can use in List.

## TUPLE ( )
-----
Tuple is also a sequence data type that can contain elements of different data types, but these are immutable in nature so we can’t make any changes in Tuple. Tuple can be represented by ‘( )’. <br><br>
Here's how to declare a Tuple :
```
  listTuple = (“Alpha”, 21, “3.6”, “Beta”)
```
We can also Slicing Data in Tuple.

## SLICING DATA
-----
Slicing a list is a technique for trimming the values in List and Tuple. What this means is: we retrieve some values from a list or tuple member by defining a left index and a right index.

We can use 4 ways to Slicing Element from list or tuple :
-	listData[x ] ----- only one index
-	listData[x : y] ----- using index to delimit data
-	listData[ : y] ----- empty one of the index
-	listData[x : y : z] ----- using 3 indexes, and one index is used for data jump reference <br>

Find out how to use it in our documentation.

## SET {}
-----
Set is an unordered collection data type that is iterable, not allow duplicate elements, and mutable i.e we can make any changes in set, but elements are not duplicated. Python’s set class represents the mathematical notion of a set. Since sets are unordered, we cannot access items using indexes like we do in lists. Set data structure is also non-homogeneous data structure but stores in single row. Set can be represented by { }. 

Here's how to declare a Set :
```
  Set = {3, 3, 3, 4, 4, 4, 4, 5, 5, 5, 5, 5}
```

Set can use nested among all. Set can be created using set() function.

Methods for sets :
1. Adding Elements
> Insertion in set is done through set.add() function, where an appropriate record value is created to store in the hash table. 
2. Union
> Two sets can be merged using union() function or | operator. Both Hash Table values are accessed and traversed with merge operation perform on them to combine the elements, at the same time duplicates are removed.
3. Intersection
> This can be done through intersection() or & operator. Common Elements are selected. They are similar to iteration over the Hash lists and combining the same values on both the Table.
4. Difference
> To find difference in between sets. Similar to find difference in linked list. This is done through difference() or – operator.

## DICTIONARY
-----
Dictionary in Python is an ordered (since Py 3.7) [unordered (Py 3.6 & prior)] collection of data values, used to store data values like a map, which, unlike other Data Types that hold only a single value as an element, Dictionary holds key:value pair. Key-value is provided in the dictionary to make it more optimized.

In Python, a Dictionary can be created by placing a sequence of elements within curly {} braces, separated by ‘comma’. Dictionary is also a non-homogeneous data structure which stores key value pairs. Dictionary can use nested among all. Dictionary can be created using dict() function. Dictionary is mutable. But Keys are not duplicated. 

Here's how to declare Dictionary :
```
  dicti = {"Key": "Value", "Key2": "Value2"}
```

-----
#### FIND OUR FULL DOCUMENTATION ABOVE :)
