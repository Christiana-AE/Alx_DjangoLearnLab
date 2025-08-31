# Delete the book instance
del book

# Try to retrieve all books (in this simple example, we check if 'book' still exists)
try:
    print(f"Title: {book.title}")
except NameError:
    print("Book has been deleted successfully.")

# Expected output:
# Book has been deleted successfully.
