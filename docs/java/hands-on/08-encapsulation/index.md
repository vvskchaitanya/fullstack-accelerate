# [Java](../../) - OOP - Encapsulation

### Learning Objectives:

- Implement Encapsulation, Define getter and setter
- Create object instances using Java constructors

---
#### Example 1: Book and BookStore

```mermaid

classDiagram
    class Book {
        -String title
        -String author
        -double price
        +getTitle()
        +getAuthor()
        +getPrice()
    }

    class BookStore {
        -String name
        -Book[] books
        +addBook(Book book)
        +removeBook(Book book)
        +listBooks()
    }

    BookStore "1" --> "many" Book : contains

```