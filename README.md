# sql_final

The world was taken by surprise by the coronavirus, changing the usual order of things. People no longer go out, visit cafes, or shopping centers in their free time. However, there is now more time for books.

Objective: Analyze the database of a large book reading subscription service. It contains information about books, publishers, authors, and user reviews of books. This data will help formulate a value proposition for a new product.

**Data Description**

**Table: `books`**

Contains data about books:

- `book_id` - book identifier;
- `author_id` - author identifier;
- `title` - book title;
- `num_pages` - number of pages;
- `publication_date` - book publication date;
- `publisher_id` - publisher identifier.

**Table: `authors`**

Contains data about authors:

- `author_id` - author identifier;
- `author` - author's name.

**Table: `publishers`**

Contains data about publishers:

- `publisher_id` - publisher identifier;
- `publisher` - publisher's name;

**Table: `ratings`**

Contains data about user ratings of books:

- `rating_id` - rating identifier;
- `book_id` - book identifier;
- `username` - username of the user who left the rating;
- `rating` - book rating.

**Table: `reviews`**

Contains data about user reviews of books:

- `review_id` - review identifier;
- `book_id` - book identifier;
- `username` - username of the user who wrote the review;
- `text` - review text.

**Tasks**

- Calculate the number of books released after January 1, 2000;
- For each book, calculate the number of reviews and the average rating;
- Determine the publisher that has released the most books with more than 50 pages;
- Identify the author with the highest average rating for books, considering only books with 50 or more ratings;
- Calculate the average number of reviews from users who have given more than 48 ratings.

**Conclusion**
Based on the analysis, we have determined the following:

819 books were released after January 1, 2000.
Penguin Books has released the highest number of books - 42.
The book by J.K. Rowling and Mary GrandPré has the highest average rating of 4.3.
The average number of reviews from users who have given more than 48 ratings is 24.
We have also supplemented the table with the number of reviews and average rating for each book.
