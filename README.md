# 📚 BookBuddy AI – Book Recommendation System

## 1. Project Title

**BookBuddy AI – Book Recommendation System**

**Project Type:** BCA College Project – Feature Set B

---

## 2. Project Description

BookBuddy AI is a simple and attractive **Book Recommendation System** designed for students and book readers.

The system allows users to search books, select a genre or author, view recommended books, check ratings, and read book details. The project contains a collection of books from different genres.

---

## 3. Features

### 🔍 Search Books
- Search books by **book title**.
- Search books by **author name**.
- Results are displayed instantly.

### 📚 Genre Selection
Users can filter books according to genres such as:
- Fiction
- Mystery
- Thriller
- Romance
- Fantasy
- Science Fiction
- Horror
- Biography
- Self-help
- Programming
- Technology
- Artificial Intelligence
- Machine Learning
- Data Science
- Science
- Philosophy
- Adventure
- And more.

### ✍️ Author Selection
- Users can select an author from the author dropdown.
- The author list is automatically generated from the available books.

### ⭐ Book Ratings
- Every book has a rating.
- Matching books are sorted according to rating.

### 📖 Book Details
Users can view:
- Book title
- Author
- Genre
- Rating
- Published year
- Description

### 💾 Save Book
Users can click the **+ Save** button to add a book to their reading list.

### 📱 Responsive Design
The website is designed to work on:
- Desktop
- Tablet
- Mobile devices

---

## 4. Tools and Technologies Used

### Frontend
- **HTML5** – Website structure
- **CSS3** – Styling and responsive design
- **JavaScript** – Search, filtering, recommendation and interactions

### Data
- JavaScript array is used to store book information.
- Each book contains ID, title, author, genre, rating, year and description.

### Development Tools
- VS Code / any HTML editor
- Modern web browser

---

## 5. Algorithm Used

### Book Recommendation Algorithm

The system uses a **filtering and rating-based sorting algorithm**.

### Steps

1. Start the program.
2. Load the available books.
3. Get the user's:
   - Search text
   - Selected genre
   - Selected author
4. Compare the search text with the book title and author.
5. Check the selected genre.
6. Check the selected author.
7. Display only the books satisfying the selected conditions.
8. Sort the matching books from highest rating to lowest rating.
9. Display the recommended books.
10. Allow the user to view complete book details.
11. Stop.

---

## 6. Simple Algorithm Flow

```text
START
   ↓
Load Book Data
   ↓
Enter Search / Select Genre / Select Author
   ↓
Filter Books
   ↓
Match Title or Author
   ↓
Check Genre
   ↓
Check Author
   ↓
Sort Matching Books by Rating
   ↓
Display Recommended Books
   ↓
View Book Details
   ↓
END
```

---

## 7. Recommendation Logic

The recommendation system is based on **user-selected filters and book ratings**.

For example:

**User selects:**
- Genre: Fantasy
- Author: J.R.R. Tolkien

The system finds matching books and sorts them according to their ratings.

The sorting logic is:

```javascript
result.sort((x, y) => y.rating - x.rating);
```

This displays books with higher ratings first.

---

## 8. Main Functions

### `render()`
Displays the available or filtered books on the webpage.

### `recommend()`
Searches and filters books according to:
- Search text
- Genre
- Author

Then sorts the results by rating.

### `details(id)`
Displays complete information about the selected book.

### `closeModal()`
Closes the book-details popup.

---

## 9. Sample Book Data

| Book | Author | Genre | Rating |
|---|---|---|---:|
| The Alchemist | Paulo Coelho | Fiction | 4.7 |
| Harry Potter and the Philosopher's Stone | J.K. Rowling | Fantasy | 4.8 |
| The Hobbit | J.R.R. Tolkien | Fantasy | 4.8 |
| Atomic Habits | James Clear | Self-help | 4.6 |
| Wings of Fire | A.P.J. Abdul Kalam | Biography | 4.7 |
| Python Crash Course | Eric Matthes | Programming | 4.7 |
| Artificial Intelligence: A Modern Approach | Stuart Russell & Peter Norvig | Artificial Intelligence | 4.7 |

---

## 10. Advantages

- Easy to use
- Simple and attractive interface
- Fast book searching
- Genre-based filtering
- Author-based filtering
- Rating-based recommendations
- Book details in popup
- Mobile responsive
- Suitable for a BCA college project

---

## 11. Future Scope

The project can be improved by adding:

- User login and registration
- Personal reading lists
- Database connectivity
- Personalized recommendations
- Machine Learning recommendation model
- User ratings and reviews
- Book API integration
- Recommendation history
- Cloud database
- Python backend

---

## 12. Conclusion

**BookBuddy AI** provides a simple way for users to discover books based on title, author, genre and rating. It demonstrates the use of **HTML, CSS and JavaScript** to create an interactive book recommendation system suitable for a BCA college project.
