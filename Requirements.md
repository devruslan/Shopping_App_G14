# Requirements/Structure

1. Welcome Screen
  - Registration
    - Role
    - Username
    - Password
  - Login
    - Username
    - Password
    - Confirmation/Greeting
2. Manager
  - Dashboard
    [1] Add Category
    [2] Delete Category
    [3] Add Item
    [4] Delete Item
    <!-- [5] Change Password // optional -->
    <!-- [6] Sign out -->
    [7] Create coupons (coup30%, coup50%)
  - Add/Delete Categories
  - Add/Delete Items
    - Name
    - Price
    - Category
    - Quantity
3. Shopper
- Dashboard
  - Display the balance
  - [1] Add funds to balance
    - Flexible amount
    - Min $50
    <!-- - Max $??? -->
    <!-- - Fixed options -->
    <!-- - Payment option PayPal, CreditCard-->
  - Shopping
  - [2] Start shopping
    - View and Select Categories
    ([1]Cloths, [2]Shoes, [3]Bags ...)
      - View Items
      - Display the cart
      - Put items to cart
      - Remove Items from cart
      - Exit Category
      - display cart info
      - Check for balance and display warning
      - Go to checkout
    - display cart info
    - Check for balance and display warning
    - Go to checkout
  <!-- [3] Sign out -->
  <!-- [4] Change password -->
  <!-- [5] Add personal info -->
4. Stock Management
  - Takes data from manager and Shopper
  - Affects "View Items" module
5. Checkout
  - Display the Items + amounts
  - Display the Subtotal
  - Prompt for coupon
  - Display Tax
  - Display Total
  - Choose Payment Method for Extra
  [1] Credit Card
  [2] PayPal
  [3] Check
  Success!
7. Confirmation and receipt
  - Choose where you want to receive your receipt
  [1] No receipt
  [2] Text
  [3] Email
