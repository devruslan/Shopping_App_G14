# User Stories

1. Welcome Screen

  - U.S.1. As a user I should be able to register
    - 1.A.C.1. Verify that the user can choose a role
    - 1.A.C.2. Verify that the user can create a username
    - 1.A.C.2.1. Verify that the username is unique
    - 1.A.C.3. Verify that the user can create password
    - 1.A.C.3.1. Verify that the password is at least 8 characters, at least 1 lowercase, 1 uppercase, 1 numeric and 1 special character

  - U.S.2. As a user I should be able to Login
    - 2.A.C.1. Verify that the user can see the username Prompt and be able to enter username
    - 2.A.C.2. Verify that the user can see the password Prompt and be able to enter password
    - 2.A.C.3. Verify that the username and password are valid. If valid let the user in. If not valid, give error message and prompt to login or register.
    - 2.A.C.4. Number of attempts should be limited to 3. After 3rd invalid attempt user should be blocked.

  - U.S.3. As a user I should be able to reset my Password
    - 3.A.C.1. Verify that the user can choose to reset the Password
    <!-- - 3.A.C.2. Verify that the user is sent an email with a link to reset the password // We are not sure how we can make this work without difficulties -->
    - 3.A.C.3. Verify that the user i prompted to enter the username
    - 3.A.C.4. Verify that the user can enter the new Password

2. Manager

  - U.S.4. As a manager I should be able to add categories
    - 4.A.C.1. Verify that the manager can give name to the Category
    - 4.A.C.2. Verify that the new category name is unique (no duplicates)
    - 4.A.C.3. Display a success message with options to add more or leave

  - U.S.5. As a manager I should be able to delete categories
    - 5.A.C.1. Verify that the manager can choose which category to delete
    - 5.A.C.2. Display a success message
    <!-- - 5.A.C.3. Option to bulk delete -->

  - U.S.6. As a manager I should be able to add items
    - 6.A.C.1. Verify that the manager can input item name, price and quantity and select the category.
    - 6.A.C.2. Verify that the item is not a duplicate
    - 6.A.C.3. Display a success message with options to add more or leave

  - U.S.7. As a manager I should be able to delete items
    - 7.A.C.1. Verify that the manager can choose which item to delete
    - 7.A.C.2. Display a success message
    <!-- - 7.A.C.3. Option to bulk delete -->

  - U.S.8. As a manager I should be able to create coupons
    - 8.A.C.1. Verify that the manager specifies coupon name and percentage
    <!-- - 8.A.C.2. Option to choose either percentage or off amount -->
    - 8.A.C.2. Verify that the percentage is max 30%
    - 8.A.C.2. Display success message

3. Shopper

  - U.S.9. As a shopper I should be able to view the dashboard
    - 9.A.C.1.
    - 9.A.C.2.

  - U.S.9.

  - U.S.10.

  - U.S.11.

  - U.S.12.
