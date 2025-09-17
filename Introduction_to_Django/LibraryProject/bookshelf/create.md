from bookshelf.models import Book

book = Book(
    title="The Art of Django",
    author="Christiana Dev",
    publication_year = 2025
)
book.save()
Book.objects.all()
Book.objects.create