# Hook A Book

![MIT License](https://img.shields.io/badge/license-MIT-green)

## Note

We worked on this project as a group during class, and the code for the finished application was provided by our instructor.

## Description

- Purpose of this project: A fully functioning Google Books API search engine
- Problem(s) the app solves: A user not having a place to search for books.
- Languages used: HTML, CSS, JavaScript
- Brief description: An application where the user can search for books using a fully functional Google Books API search engine.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)
- [Links](#links)

## Installation

This app requires the installation of Appolo server, graphql, React, and Node.js/Express.js to function. All are included in the package.json files and can be installed with the following input:

```bash
npm install
```

## Usage

When the user loads the search engine application, they are presented with a menu with the options "Search for Books" and "Login/Signup", an input field to search for books, and a submit button. When they click on the Search for Books menu option, they are presented with an input field to search for books and a submit button. When they are not logged in and enter a search term in the input field and click the submit button, they are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site. When they click on the Login/Signup menu option, a modal appears on the screen with a toggle between the option to log in or sign up. When the toggle is set to Signup, they are presented with three inputs for a username, an email address, and a password, and a signup button. When the toggle is set to Login, the user is presented with two inputs for an email address and a password and login button. When they enter a valid email address and create a password and click on the signup button, the user account is created and they are logged in to the site. When they enter their account’s email address and password and click on the login button, the modal closes and they are logged in to the site. When they are logged in to the site, the menu options change to Search for Books, an option to see my saved books, and Logout. When the user is logged in and enter a search term in the input field and click the submit button, they are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account. When the user clicks on the Save button on a book, then that book’s information is saved to the user's account. When they click on the option to see their saved books, they are presented with all of the books they have saved to their account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from the account. When the user clicks on the Remove button on a book, then that book is deleted from the user's saved books list. When they click on the Logout button, they are logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button.

## Screenshots

### Screnshot of main page before user has logged in but has searched for books

!["Screen shot of app of main page on desktop. The header is black and the font is white. On the top left text reads "Hook A Book!" and to the top right is a nav bar with options to "Search For Books" and "Login/Sign Up". Below that in the middle has larger white text that reads "SEARCH FOR BOOKS!" beneath which is an input bar that says "Search for a book" and next to the bar in a green button with white text that reads "Submit Search". Below that is a white background with black text reading "Viewing 10 Results" with several Lord of the Rings books underneath.](./img/hook_a_book_desktop_ss.png)

### Screnshot of See Your Books page

!["Screen shot of app of See Your Books page on desktop. The header is black and the font is white. On the top left text reads "Hook A Book!" and to the top right is a nav bar with options to "Search For Books" and "Login/Sign Up". Below that in the middle has larger white text that reads "VIEWING ANEWUSERS'S BOOKS". Below the header is a white background with black text reading "Viewing 2 Saved Books" images and text for two books underneath.](./img/hook_a_book_saved_ss.png)

## License

This application is licensed under the MIT license.

## Contributing

If you would like to contribute to this application, please follow the Contributor Covenant guidelines.

## Tests

Input unexpected characters into the search input.

## Questions

If you have any questions:

- Email me: [meegan.r.anderson@gmail.com](mailto:meegan.r.anderson@gmail.com)
- Go to my github: [NotANewt](https://github.com/NotANewt)

## Links

- Here is the repo: [NotANewt/Hook A Book](https://github.com/NotANewt/hook_a_book)
- Here is the pages: [NotANewt/pages](https://hook-a-book-meegan.herokuapp.com/)
