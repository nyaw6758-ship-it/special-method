# special-method
This gives fair idea of what special methods are their syntax
•	__init__ (Constructor): Automatically called when a new instance of a class is created to initialize its attributes.
•	__str__ & __repr__ (String Representation): __str__ defines a user-friendly string for print(), while __repr__ provides an unambiguous string used for debugging.
•	__len__ (Length): Defines the behavior of the built-in len() function for your object.
•	__eq__ (Equality): Allows you to use the == operator to compare two objects based on their data.
•	__add__, __sub__, __mul__ (Operator Overloading): Enables the use of arithmetic operators (+, -, *) with your custom objects.
•	__getitem__ & __setitem__ (Item Access/Assignment): Allows objects to use square bracket indexing (e.g., obj[key]) to retrieve or assign values.
•	__contains__ (Membership): Defines how the in operator behaves (e.g., if item in obj:).
•	__call__ (Callable Objects): Allows an object to be "called" like a regular function using parentheses ().
•	__iter__ & __next__ (Iteration): __iter__ makes an object iterable, and __next__ defines how to move to the next item in a loop.
•	__bool__ (Boolean Evaluation): Determines if an object evaluates to True or False in conditional statements.
•	__del__ (Destructor): Called when an object is about to be destroyed or garbage collected to perform cleanup tasks.
