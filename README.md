# BookApi
A short coding assessment, which implements a REST API that calls an external API service to get information about books



The following endpoints works for the API document
1. POST: localhost:8000/api/books?name=A Clash of Kings&isbn=978-0553108033&number_of_pages=768&publisher=Bantam Books&country=United States&released_date=1999-02-02&authors=George R. R. Martin
2. GET: localhost:8000/api/books
3. PUT: localhost:8000/api/books/1?name=Game of Thrones&isbn=978-0553103541&authors=George R.R Mart&author_id=1&number_of_pages=200&publisher=George Books&country=United States&released_date=1999-02-02
4. DELETE: localhost:8000/api/books/1 
