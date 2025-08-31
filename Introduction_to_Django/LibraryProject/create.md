# Define the Book class
class Book:
    def __init__(self, title, author, year):
        self.title = title
        self.author = author
        self.year = year

# Create a Book instance
book = Book("1984", "George Orwell", 1949)

# Expected output:
# Book created successfully with title: 1984, author: George Orwell, year: 1949
print(f"Book created successfully with title: {book.title}, author: {book.author}, year: {book.year}")
