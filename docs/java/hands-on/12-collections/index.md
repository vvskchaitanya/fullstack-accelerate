# [Java](../../) - Collections - Basic

# Java Collections - Hands-on Exercises

## Learning Objectives

- Understand how to use `List`, `Set`, and `Map` in Java.
- Implement real-world scenarios using Java Collections.
- Practice retrieving, updating, and manipulating collections.

---

## Exercise 1: Managing a Library (Using `List`)

### Problem Statement
A library needs a system to store a list of available books. Implement a `List` to store book titles and perform the following operations:

1. Add books to the library.
2. Display all books.
3. Remove a specific book.
4. Search for a book by title.

![Library](./image1.png)

### Input & Output
#### Input:
- A list of book titles.
- A title to remove.
- A title to search.

#### Expected Output:
- The list of books after addition.
- The list of books after removal.
- A message indicating whether a book is found or not.

---

## Exercise 2: Unique Student Roll Numbers (Using `Set`)

### Problem Statement
A university stores student roll numbers and wants to ensure that duplicate entries are not added. Implement a `Set` to store roll numbers and perform the following:

1. Add new roll numbers.
2. Display all roll numbers.
3. Attempt to add a duplicate roll number and observe the output.

![StudentRecords](./image2.png)

### Input & Output
#### Input:
- A set of student roll numbers.
- A roll number to add.

#### Expected Output:
- The set of roll numbers after adding elements.
- No duplicate roll numbers should be present.

---

## Exercise 3: Phonebook Directory (Using `Map`)

### Problem Statement
A phonebook application stores contacts with names and phone numbers. Implement a `Map` to store contact details and perform the following:

1. Add contacts to the phonebook.
2. Retrieve a contact’s phone number using the name.
3. Display all contacts.

![PhoneBook](./image3.png)

### Input & Output
#### Input:
- A set of name-phone number pairs.
- A name to search.

#### Expected Output:
- The list of contacts after addition.
- The phone number associated with a given name.

---

## Challenge Task
Implement a **shopping cart system** where:

- A `List` holds items added to the cart.
- A `Set` ensures that only unique product IDs are added.
- A `Map` maintains the product name and price.

### Input & Output
#### Input:
- A list of items to add to the cart.
- A product ID to add.
- A name-price pair to store in the map.

#### Expected Output:
- The list of items in the cart.
- The set of unique product IDs.
- The map of product names with prices.

---

[← Excercise 11](../hands-on/11-abstraction) | [Next Topic TBD →](../next-topic)

---

🔗 **Related Topics:**
- [Collections](../collections/)
- [ArrayList](../arraylist)
- [Sorting Collections](../sorting)
- [Streams API](../streams)
---

