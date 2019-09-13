# Project 1

Web Programming with Python and JavaScript

## Spineless Reviews

I tried to go above and beyond with this assignment.  It meets all the requirements, but is also visually appealing and easy to use.  I put a lot of thought into the UX.

User registration and authentication are all handled using Flask sessions.  The home screen includes a "quote of the day" about reading or books in general.

Once logged in, users can search for books by ISBN, author, or book title.  Partial matches work and the search is forgiving regarding spacing and capitalization.

Once a user finds a book to click on, more info is displayed, including the cover jacket of the book, the Goodreads review count, as well as stars are dynamically
generated.  If there are existing Spineless Reviews, these are also shown.  Users are enforced to be only able to add on review.

Finally, there is an API URL endpoint that other programs can use.
