Problem Statement
Book Rent is the largest online and offline book rental chain in India. They provide books of various genres such as thriller, mystery, romance, and science fiction. The company charges a fixed rental fee for a book per month. Lately, the company has been losing its user base. The main reason for this is that users are not able to choose the right books for themselves. The company wants to solve this problem and increase its revenue and profit. In this project, I performed user-based collaborative filtering and item-based collaborative filtering, andevalute the model with RMSE. The objectives of this project are to improve the user experience by personalizing the user need, and o create a recommendation engine so that users g t recommendations for books based on the behavior of similar users. This will ensure that users are renting the books based on their tastes and traits.

Objectives
• To improve the user experience by personalizing the user
needs.
• To create a recommendation engine so that users get
recommendations for books based on the behavior of
similar users. This will ensure that users are renting the
books based on their tastes and traits.

1. Read the books dataset and explore it
2. Clean up NaN values
3. Read the data where ratings are given by users
4. Take a quick look at the number of unique users and books
5. Convert ISBN to numeric numbers in the correct order
6. Do the same for user_id. Convert it into numeric order
7. Convert both user_id and ISBN to the ordered list i.e., from 0...n-1
8. Re-index columns to build matrix later on
9. Split your data into two sets (training and testing)
10. Make predictions based on user and items
11. Use RSME to evaluate the predictions

