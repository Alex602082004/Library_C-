# Library_C#

# INSTRUCTIONS

## IMPORTS (THE PACKAGES I HAVE INSTALLED FROM NuGet):
`System.Data.SQLite`


## THE USE OF DATABASE:

- In the StartUp directory, the path to the repository in Main.cs must be replaced with the location of the project where you have downloaded it or where it is stored on your computer, 
while retaining the final segment as 'books.db'.


## DESCRIPTION:

- To launch the application, you must click the arrow next to the file name StartUp, and then double-click on Main.cs.
- The second step is to click on the green arrow located in the upper right corner of the screen to launch the application in the console.
- Upon opening the console, you will have 10 options to choose from, such as adding a book to the inventory, removing a book if it exists, or sorting the inventory by title or author, among others.
- If a title or author is requested and the input is not available in stock, nothing will be displayed as it is not present in the library.
- I have added one new parameter to the book: the number of books borrowed for requirement number 6.
- If you rent a book, the number of times that book has been rented will increase by one, and if you return it, that number will decrease.

!!! Upon the conclusion of the program (option 10) , the database will be cleared. !!!


## WHAT CAN LEAD TO ERROR MESSAGES IN THE CONSOLE:

- When a book is added, using strings instead of integers for the quantity.
- In any option where an ID is required, if the provided ID does not exist, the program will display an error in the console.
 

## REQUIREMENT 7:

- For this requirement, I have developed two stock sorting functions (options 8 and 9), namely sorting by title and sorting by author, both arranged in ascending order.


## *FUN FACT*

- Today, I learned C# and successfully completed this project.

# I hope you enjoy it and have a great time! 😁
