Actions Specifiction
===============

Listing of the reasoning and behavior of each action.

View Book
=========

View a certain book by the id or isbn

Search Books
==============

Search book by author, title (fuzzy), isbn, fiction, etc.

Add Book
==============

Post the fields to create a book

Update Book
==============

Post updated fields with the id or isbn of the book

Delete Book
==============

Delete a record based on id or isbn, deleting a copy should be updated.

Checkout Books
==============

Dedicated action to reduce current_copies

Checkin Books
==============

Dedicated action to increase current_copies

Report on Checked Out Books
===============================

View all books where current_copies < total copies

Report on Rarely Checked Out Books
========================================

View all books where total_copies == current_copies and updated_at is > 6 months

