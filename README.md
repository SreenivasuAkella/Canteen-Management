# Canteen Management System #

The Canteen Management System allows users to place food orders directly to the canteen manager online.

## Initial Steps to Follow:

1. Create a folder named `sslcms` in the directory `C:/xampp/htdocs/` and add all the provided files into it.

## Loading the Database:

1. Run the URL: `http://localhost/sslcms/init.php` on localhost to create a sample database on your system.
2. To delete the created database, run the URL: `http://localhost/sslcms/outit.php`.

## Running the Project:

1. Run the URL: `http://localhost/sslcms/home.php` to be directed to the home page of the CMS project.
2. The home page will prompt you to login/register as a user or login/register as an admin.

### If You Are an Admin:

1. Register yourself on the portal (`register_admin.php`).
2. After registration, you will be redirected to the admin login page (`login_admin.php`).
3. Log in with your registered credentials to access the main admin page.
4. On the admin main page (`main_admin.php`):
    - Add or change items in the menu in the "ADD ITEM TO MENU"/"CHANGE MENU ITEMS" section.
    - View the menu in the "MENU" section.
    - View orders placed by users in the "ORDERS PLACED BY USERS" section after the user has paid for the order.
    - Approve the delivery of the order and update the delivery status in the "ORDERS DELIVERED" section (`deliver.php`, `delivered.php`).
5. Log out from the admin main page by clicking the 'Go to home page' button (implemented with JavaScript).

### If You Are a User:

1. Register yourself on the portal (`register.php`).
2. After registration, you will be redirected to the user login page (`login.php`).
3. Log in with your registered credentials to access the main user page.
4. On the user main page:
    - Place orders in the "PLACE ORDERS" section by selecting items from the menu and clicking the 'order' button (`order.php`, `orderd.php`).
    - Edit the quantity of items or delete items from your order and pay using the 'pay' button. You can choose to pay via UPI or cash (`pay.php`, `payyed.php`).
    - View delivered orders in the "USER DELIVERED ITEMS" section.
5. Log out from the user page by clicking the 'Go to home page' button (implemented with JavaScript).

## Video Demonstration:

We have uploaded a video demonstration on YouTube. You can watch it [here](https://youtu.be/w6E4-1OChbA).
