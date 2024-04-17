# InstantBooks - Online Bookstore

InstantBooks is an online bookstore project built using Django framework. It allows users to browse through a collection of books, make purchases, and interact with an admin panel for managing products.

## Setup

1. **Get Paytm Merchant Key and MID**: Obtain MERCHANT KEY and MID from Paytm and update it in `shop/views.py` before running the project.

2. **Admin Credentials**:
   - Username: nikhilhooda
   - Password: nikhil123

3. **User Credentials**:
   - Username: user1, Password: 1234
   - Username: user2, Password: 1234

4. **Required Libraries**:
   - Install Pillow: ``` pip install pillow ```
   - Install pycryptodome: ``` pip3 install pycryptodome ```

## Payment Details

Use the following payment details for testing purposes:
- Mobile number: 77777 77777
- Password: Paytm12345
- OTP: 489871

Note: Do not attempt to make payments with official Paytm accounts or valid Debit/Credit cards in the development environment.

## How to Run

1. Open CMD, PowerShell, or Terminal/CommandShell of any IDE.

2. Navigate to the root folder where `manage.py` file is located.

3. Run command: ``` python manage.py runserver ```

4. Open any browser and go to `127.0.0.1:8000`.

5. You should see the homepage of InstantBooks.

## Access Admin Panel

1. Run the server.

2. Open a browser and visit `127.0.0.1:8000/admin`.

3. Log in with the provided admin username and password.

## Adding New Menu Items

1. Log in as an admin.

2. Go to products section.

3. Click "Add products" and provide valid details of the new product.

4. Visit the homepage to confirm the addition of the new product.

## Changing Admin Password

1. Navigate to the root folder.

2. Run the following command: ``` python manage.py changepassword <admin_username>. ```

3. Provide a new password.

## Important Notes

- The payment gateway is for development purposes only and should not be used for real-world transactions.
- Payment failures may occur frequently in the development environment. Ensure all required fields are filled and retry if necessary.
- For any queries, contact the project writer.
