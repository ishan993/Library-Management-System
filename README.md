# Library-Management-System

 The Library Management System provides a simple yet elegant user interface to patrons and librarians, achieved using Google’s Material Design guidelines and principles. 

For the librarian, our application provides the following functionality:
1. Ability to add books, recording their location, call number, number of copies, along with book details. 
2. Update book information after adding the book.
3. Use ISBN to look up a book’s information to facilitate recording book details, achieved by Google Books API, 
   retrieve a list of books added by a particular librarian.
4. The ability to search for a book based on the following criteria: book title, keywords, publish year, published, and author. 
5. Automatically sign-up as a librarian by using SJSU email.
6. Set date and time to check the following functionality: renew books, calculate fine, send reminders.

For the patron, we implemented the following functionality:
1. The ability to add multiple books to cart, check them out, and return them.
2. The ability to enroll in multiple books’ waitlist.
3. The ability to reserve a book for 3 days after the book’s waitlist clears. 
4. The ability to renew book twice if there is not waitlist
5. Email notification for registration, book checkouts, book returns and book reservation.
6. Daily Email reminders to return a book which is due within from 5 days.

Component Design: 
