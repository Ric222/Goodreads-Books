## Data Omega Challenge- GoodReads Books Dataset  📚📖

This is the first time I participated in the Data Omega challenge and loved the month's theme: **Books!**

The dataset contains list of books listed on Goodreads. It has information about book titles, authors, ratings, ISBN, reviews, publishers and the publication date.

### Objective:
The objective of the Dashboard is to highlight the books with the highest ratings, authors with the most titles, publishers with the most reviewed books and highest rated authors.

These findings will be useful for a business owner who wants to set up a coffee-cum-library shop as he/she will get more insights of what authors people love to read these days. The analysis will answer the question: **“What books do I actually offer customers at my coffee shop?”**

### Analysis:

I started by cleaning the dataset first with Power Query.

- **How are books distributed across different languages?**

It's interesting that even though the dataset includes 27 languages, **95% of the books are in English**. 

And lengthwise, the shortest book has only 27 pages while the longest book has 6576 pages.

- **Which authors wrote the most books?**

According to dataset, **Stephen King** and **P.G.Wodehouse** are indeed one of the most prolific authors, with the most titles to their name. Their works span across various genres, including horror, supernatural fiction, suspense, and fantasy.

- **Did the ratings for Harry Potter series follow a trend?**

The ratings for six Harry Potter books in the dataset were all above 4.4 and stayed around that number. All the books were equally liked by the readers. 

Kudos to J.K.Rowling-Mary!! 😄

- **Which are the highly top rated books and authors?**

**Twilight** is the book with highest rating(4.60 M) followed by **The Hobbit**(2.53 M). 

**J.K.Rowling** is the highest rated author( ofcourse she is!!).

- **Did the books with more text reviews receive higher ratings?**

**Ratings_count** and **text_reviews_count** are highly correlated with Correlation Coefficient **O.86**.

th eplot clearly shows that the books with **more text reviews** (> 10,000) received a **better rating** (> 3.25).

- **Which publishers have the most reviewed books?**

**Penguin** publishers takes the lead here. 

**Vintage** followed by **Penguin** publishes the most number of books.

### Conclusion

I can clearly recommend a list of books and authors which he/she should have in the shop based on the above analysis. 

Do tell me **"What would be your choice of book at the coffee place"?** 😃





![Goodreads books](https://github.com/Ric222/Goodreads-Books/assets/104567667/969fc369-2a11-4092-951d-1a36d7e27464)







