# Django Model Relationships Project

This project demonstrates **advanced Django ORM relationships** by modeling a real-world system of authors, books, libraries, and librarians.

## Features

- **ForeignKey**: One Author can write multiple Books.
- **ManyToManyField**: A Library can contain many Books, and a Book can belong to multiple Libraries.
- **OneToOneField**: Each Library has one Librarian, and each Librarian manages only one Library.
- Example ORM queries for retrieving relational data.

## Project Structure
