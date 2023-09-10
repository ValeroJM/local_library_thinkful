# Project description: Local library

This is the Thinkfull assessment at the end of the Creating Interactive Websites module.

## The Learning objectives
This project is designed to test my ability to work with large datasets and build algorithms based on those datasets. 
The learning objectives are listed below:

* Using Visual Studio Code as a text editor

* Differentiating between the three most common JavaScript error types

* Solving bugs by using error messages

* Differentiating between **let**, **const**, and **var**, and using each appropriately

* Creating an array from a string based on particular criteria and joining arrays into strings

* Writing strings that embed expressions using template literals

* Accessing all the values and keys of an object

* Using **find()**, **filter()**, **map()**, **some()**, and **every()** to solve different problems

* Using **reduce()** to solve different problems

* Using **sort()** to sort arrays in various ways


## Files Paths and Methods

Here I included all the files and functions I updated during this assessment:

* **accounts.js** - (Path: public/src/accounts.js):
    * function **findAccountById**(accounts, id) -> This function takes an "array of accounts" and an "id" and returns an "account object" that matches the "id".
    * function **sortAccountsByLastName**(accounts) -> This function takes an "array of accounts" and returns an "array of accounts" sorted by client's last name from a to z.
    * function **getAccountFullNames**(accounts) -> This function takes an "array of accounts" and returns an "array of client's full name".

* **books.js** - (Path: public/src/books.js):
    * function **findAuthorById**(authors, id) -> This function takes an "array of authors" and an "id" and returns the "author object" that matches the "id".
    * function **findBookById**(books, id) -> This function takes an "array of books" and an "id" and returns the "book object" that matches the "id".

* **home.js** - (Path: public/src/home.js):
    * function **getTotalBooksCount**(books) -> This function takes an "array of books" and returns the "Total number of books".
    * function **getTotalAccountsCount**(accounts) -> This function takes an "array of accounts" and returns the "Total number of accounts".
    * function **getBooksBorrowedCount**(books) -> This function takes an "array of books" and returns the "Total number of books that are borrowed".

## Extra test Added

Here I included all the files and scenarios I added to support the testing:

* **accounts.test.js** - (Path: public/test/accounts.test.js) 
    * Test Case: **findAccountById() should be a funtion** -> Validates the typeOf findAccountById.
    * Test Case: **findAccountById() returns an object** -> Verifies if the return typeOf findAccountById is an object.

* **main.test.js** - (Path: public/test/main.test.js) 
    * Test Case: **getTotalBooksCount() should be a funtion** -> Validates the typeOf getTotalBooksCount.
    * Test Case: **getTotalBooksCount() returns a number** -> Verifies if the return typeOf getTotalBooksCount is a number.
