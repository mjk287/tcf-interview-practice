Book App: Be able to signup, login, check current user, register a book, render all books, claim a book, remove a book, render book show page, render user show page with books, allow user to edit registered books etc.

1. Signup, Login, Current User
- download and install JWT in the backend
- on Signup and Login endpoints, encode JWT token of user id
- on Signup, register user in the database
- on Login, authenticate user based off of username and password
- on refresh or reload, check for JWT token in local storage, decode token, and find user based off of this
