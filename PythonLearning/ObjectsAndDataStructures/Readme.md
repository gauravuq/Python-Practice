## Python objects and data structures
####DataTypes
* **int** : 3,4
* **float** : 2.2,3.4
* **str** : "I am great!!" or 'Gaurav Sood'
* **lst** : Ordered sequence of objects **[10,"Lol", 200.3]**
* **dic** : Unordered Key:Value Pair of objects **{"mykey":"myvalue"}**
* **tup** : Ordered immutable sequence of objects **(10,"hello")**
* **set** : Unordered collection of unique objects **{"a","b"}**
* **bool** : **True/False**
* **None** : placeholder null value;
####Operators
**+, /, -, star, Double star for raised to Power, %**  : precedence is BODMAS;
(Python performs true division by default, Decimals are returned)
####Variables
* **Keep variable names as lowercase,Connect using _**
* **Python uses dynamic typing, that means you can reassign the variable to different data type**
* **It is case sensitive, letter is different from Letter**
####Strings
* **Strings are Immutable, though we can select each character using []**
* **They support indexing and slicing operations**
* **They support [] brackets for fetching characters or substrings**
* **str() and len() function which are used the most**
* **Reverse indexing is supported**
####Lists
* **Strings are Mutable & allows duplicate values**
* **They hold different kind of objects & list is an ordered sequence or elements**
* **They support indexing, slicing operations**
* **They support [] brackets**
* **str(),len(), sort(), pop()[from end], append()[to end] function which are used the most**
* **Supports Concatenation of Lists**
* **Reverse indexing is supported**
* **Nested Object Lists are also supported along with mixed list sort() and reverse() operations**
####Dictionaries
* **Dictionaries cannot be sorted as they don't have indexes** 
* **These contain key:value pair of objects inside {}**
* **Dictionaries can hold sub dictionaries , lists etc**
* **ordereddict is a dictionary with ordering properties**
####Tuples
* **These are very similar to list , but tuples  have immutability, elements inside cannot be changed once entered**
* **Tuples uses (), they are ordered**
* **Tuples provide data integrity in longer code structure**
* **It only has two functions: count and index**
* **It has subscript support example - tuple[] does work for access**
####Sets
* **These are collection of unordered unique elements, only unique objects**
* **These are not indexed & created using set() function or { 1,2,3,4}**
* **Once a set is created, you cannot change its items, but you can add new items, sets  have immutability**
* **It has no subscript support example - set[] does not work**
####Booleans
* **True/False Capital Always**
* **'None' can be used a placeholder or as a None value**
####Files
* **open("[FileName]") to open a file; write()- to write inside the file opened with proper mode**
* **close() to manually close a file & Closed is property which print True or False if the file is open or not**
* **with open([FileName]) as variable name: ; This command is very similar to open by resources of Java; Automatically close the resources**
* **modes of open function are r, w(OverWrites the File), a, r+, w+(OverWrites the File)**