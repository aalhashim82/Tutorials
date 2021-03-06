Notes
===
- Python is case-sensetive
- Spaces has meaning in Python.  This is the Pythonic way of brining structure to code
- Pythonic way of naming variables: snake_case
- ```type```(3.14) to check data type
- ```print```("Hello") to print to screen
- Pythons follows the **zero indexing** system which describe *how far the element from the begining of the list*
  - ```0```: first element
  - ```-1```: last element
  - ```:```: slicing notation to slide a part of an object
- ```in``` and ```not in```: membership operators

Data Types
===
- ```flaot```: 3.14, 3.
- ```int```: 3
- ```string```: "3.14"
- ```bool```: True, False

Data Structures
===
Collection/Container of group of data types
- ```list```: mutable ordered sequence of elements, can contain mix of data types, most similar to string
  - ```winter_months = ["Dec", 1, "Feb"]```
  - winter_months[0] = "Dec"
  - winter_months[-1] = "Feb"
  - winter_months[0:2] = winter_months[:2] = ["Dec", 1]
  - len(winter_months) = 3
  - "Feb" in winter_months = True
  - "Feb" not in winter_months = False
  - "!".```join```(["O", "Nice"]) = "O!"Nice!"
  - ["1", 2, "3"].append(4) > ["1", 2, "3", 4]
- ```tuple```: imutable ordered sequence of element, to stored related related peices of inforamtion (lagitude, latitude; x-,y-,z-coordinates)
  - location = (31.3333, 66.0111)
- ```set```
- ```dictionary```
- ```compound```


Number Operations
===
- ```^``` is the bitwise operator not the power operator which is ```**```
- ```//``` for integer division which round-down
  - ```7//2 = 3``` and ```-7//2 = -4``` 
- e for scientific operation ```3e4 = 30,000```
- ```int(3.14)``` to convert to integer ```3```
- ```float(3)``` to convert to float ```3.0```
- ```methods``` are associated with different types of objects while ```functions``` are generic

String Operations
===
- "Hi" + "there" = "Hithere"
- "Hi" * 2 = "HiHi"
- ```str(3.14)``` to convert to string
- ```len("Hi") = 2```

String Methods
===
- "amin alashim".```title()``` = Amin Alhashim
- ```islower()```, ```count('a')```
- "Ali like {}".```formate```("Mohammad") = "Ali like Mohammad"
- "This is a nice code".```split```() = "This", "is", "a", "nice", "code"
- "This is a nice code".```split```(' ', 3) = "This", "is", "a", "nice code"
- "This is a nice code".```split```(None, 3) = "This", "is", "a", "nice code"

References
===
- Udacity: Introduction to Python Programming
- [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
  - you can use atom package [linter-python-pep8](https://atom.io/packages/linter-python-pep8) to use pep8 within your own programming environment in the Atom text editor
- [String Methods](https://docs.python.org/3/library/stdtypes.html#string-methods)
