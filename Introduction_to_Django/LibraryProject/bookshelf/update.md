# Update Operation

Command:

book = Book.objects.get(title="1984")
book.title = "Nineteen Eighty-Four"
book.save()

Expected Output:

<QuerySet [<Book: Nineteen Eighty-Four>]>