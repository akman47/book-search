# Book Search

## Description
A MERN Google Books API search engine application where users can search for new books to read and keep a list of books to purchase or read

## Made With
* HTML
* CSS
* JavaScript
* Node

## Packages
* Express
* Mongoose
* Bcrypt
* GraphQL
* JSON Web Token

## Application
https://akman-booksearch.herokuapp.com/

## Usage
After signing up and creating an account, users can search for books by title, authors, and other key words and save them for future reference or to access at a later time

## Local Development
<h3>Full App</h3>
1. Install npm packages with <code>npm i</code>
2. Start the app with <code>npm start</code>. The app should open a browser window at <code>https://localhost:3001</code>

<h3>Server Only</h3>
1. Navigate to the server directory with <code>cd server</cd>
2. Install npm packages with <code>npm i</code>
3. Start server with <code>npm run watch</code>
4. Navigate to <code>https://localhost:3001/graphql</code> to test queries and mutations

## Sreenshot

## Credit
Built by Angela Man

## Criteria
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  