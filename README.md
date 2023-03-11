# OOP'S:
Object-oriented programming is like building a factory assembly line, where each component has a specific role and works together
to produce a final product. In Python, objects are created from classes, which are like blueprints or templates for creating objects.
A class defines the properties and behaviors that an object will have, and you can create multiple instances of the same class, each 
with its own unique set of data. For example, you could define a class called "Person" with properties like name, age, and address, 
and behaviors like walking, talking, and eating. You could then create multiple instances of the "Person" class, each representing a
different person with their own unique data. OOP is a powerful programming paradigm that can help make your code more modular, reusable
,and easier to maintain. By breaking your program down into smaller, more manageable objects, you can focus on developing each component
independently and then combine them together to create a more complex system.

# Library-OOP'S:

This code defines a class named "Farwah_Library" which contains methods to perform basic library operations such as displaying available
books,lending a book, adding a book, and returning a book. The class has a class-level variable named "dct" which is an empty dictionary.
This dictionary will be used to keep track of the books that are currently lent out and their respective borrowers.The "init" method takes
two parameters, "name" and "list". "name" represents the name of the library, and "list" is a list of available books. These parameters 
are used to initialize the instance variables "name" and "list" respectively. The "continuee" method is a static method that displays 
the available operations that can be performed on the library.The "Display" method simply returns a formatted string that display the 
available books.The "Lend" method takes user input for the name of the book and the borrower's name. It first checks if the book is 
available in the library's "list" variable. If the book is available, it the checks if the book is currently lent out to someone else by 
checking if the book is present in the "dct" dictionary. If the book is not already lent out, it adds an entry to the "dct" dictionary 
with the book name as the key and the borrower's name as the value. If the book is already lent out, it returns a message indicating who 
has already borrowed the book.The "Add" method takes user input for the name of the book that the user wants to add to the library. It 
then appends the book to the library's "list" variable and returns a message indicating that the book has been added.The "Return" method 
takes user input for the name of the book that the user wants to return and the borrower's name. It first checks if the book is currently
lent out to the borrower by checking if the book is present in the "dct" dictionary and if the borrower's name is present as the value. 
If the book is currently lent out to the borrower, it removes the entry from the "dct" dictionary. If the book is not currently lent out
to the borrower, it returns a message indicating that the book was not borrowed by the borrower.The main code block creates an instance 
of the "Farwah_Library" class and provides a menu for the user to select which operation to perform. The programloops until the user decides to quit.
