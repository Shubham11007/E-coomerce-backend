 E-commerce website: Created the backend of an e-commerce website, where I
 implemented a login and registration system with JWT (JSON Web Token) authentication
 to ensure secure access. Used Bcrypt to hash passwords before storing them in the
 database, preventing security risks like plaintext storage.
 Built APIs to: Search books by title, author, or category. Apply filters (price range, ratings,
 genre) for a better user experience. Add/remove books from the cart and calculate the
 total price.
 Designed: MySQL database with proper relationships between books, users, carts, and
 orders. Used transaction management to ensure data consistency (e.g., deducting stock
 after purchase). Implemented error handling to provide clear messages (e.g., "Book not
 available").
    Key Features & My Contributions
      1. Secure User Authentication
 Created a login and registration system with JWT (JSON Web Token) authentication to ensure
 secure access.
 Used Bcrypt to hash passwords before storing them in the database, preventing security risks like
 plaintext storage.
   2. RESTful APIs for Bookstore Operations
 Built APIs to:
 Search books by title, author, or category.
 Apply filters (price range, ratings, genre) for better user experience.
 Add/remove books from the cart and calculate the total price.
 Proceed to checkout, leading to a dummy payment page 
     Database & Security
 Designed a MySQL database with proper relationships between books, users, carts, and orders.
 Used transaction management to ensure data consistency (e.g., deducting stock after purchase).
 Implemented error handling to provide clear messages (e.g., "Book not available").
 Key Challenges & Solutions
 Challenge: Slow search queries with multiple filters.
 Solution: Added database indexing on price, rating, and category columns.
 Challenge: Cart data persistence across sessions.
 Solution: Used JWT tokens to track users instead of server-side sessions
