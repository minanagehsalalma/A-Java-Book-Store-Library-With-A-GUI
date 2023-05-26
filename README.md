# A Java Book Store Library With A GUI
A Java Book Store Library With A GUI That allows adding and removing books , with an admin and a customer interface

# The Gui Version 
It's made of Five Classes : 
1. Main 2. Book 3. Customer 4. User 5. Cart

# The Console Version 
It's made of Five Classes : 
1. Main 2. Book 3. Customer 4. User 5. Cart


https://github.com/minanagehsalalma/A-Java-Book-Store-Library-With-A-GUI/assets/20546638/e3e6579b-c769-4204-aa49-d29d8b82934c

# Usage 
- Just Run The EXE file or The already Built JAR file it requires Minimum JRE version `1.8.0`
OR
- Import the Version Of the program you like , be selecting its zip file into the import option of NetBeans 
![image](https://github.com/minanagehsalalma/A-Java-Book-Store-Library-With-A-GUI/assets/20546638/6f7dab98-f629-4c6f-ba82-b477d35e975f)


# General Code Flow:

1. The `Books` class represents a collection of book objects, with methods to add, remove, and search for books. Each book is represented by an instance of the `Book` class, which has fields for the book's ID, title, author, price, and quantity.

2. The `Cart` class represents a shopping cart, with methods to add and remove books, print the contents of the cart, and search for books by ID.

3. The `Customer` Creates a `Cart` object.

4. The `Main` class is the One that runs the program. It creates a `Books` object, a `Customer` object, and a `Scanner` object for user input. It then loops through a menu of options that allows the user to interact with the bookstore, including printing all books, printing all books in the cart, adding a book to the cart, removing a book from the cart, and exiting the program.

5. When the user chooses to add a book to the cart, the `Customer` class prompts the user to enter the ID of the book they want to add. If the book exists, it is added to the cart.

6. When the user chooses to remove a book from the cart, the `Customer` class prompts the user to enter the ID of the book they want to remove. If the book exists in the cart, it is removed from the cart.

7. When the user chooses to print all books or print all books in the cart, the corresponding method in the `Books` or `Cart` class is called to display the relevant information.

8. When the user chooses to exit the program, the program terminates.

Overall, the program allows users to interact with a bookstore by browsing and adding books to a cart.
