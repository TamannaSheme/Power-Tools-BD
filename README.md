# Power-Tools-BD

# Manufacturer Website

#### Manufacturer Website Client Side Link: https://github.com/programming-hero-web-course1/manufacturer-website-client-side-TamannaSheme

#### Manufacturer Website Server Side Link: https://github.com/programming-hero-web-course1/manufacturer-website-server-side-TamannaSheme

### Manufacturer Website Live Link: https://toolsbd-5e046.web.app/?fbclid=IwAR1Jg5gljsa-HgxxPMe1R6lb4DjKWka8d78TrSZ9t7ly6Jg_kq3SKnieCHo

### For testing purposes, I provide admin credentials (an email address and a password): 
             Email:  tamannasheme7@gmail.com
             Password: 1204220

# Features:



### Website Purpose

   The website is a `tools manufacturer` website. The tool manufacturers could manufacture carpentry tools, masonry tools, electric tools, metalwork tools, or any tool. My website is typical e-commerce or any of your previous assignments. My design and website idea is unique. My website code or design doesn't match any of the projects implemented in our course. 

# Features:


### Features -01:

1. Home page has a Header (simple navbar), Banner, Tools/Parts, Business Summary, Reviews, and Footer. The tools/parts have either 3 tools/parts.  Each tool/part have a relevant name, image, short description, minimum order quantity, available quantity, price (per unit price), a place order/purchase/book now/ buy now button. If a user clicks on the purchase or buy now button it takes the user to the purchase page.

2. There are two different sections on the home page and the 6 sections mentioned above. 

3. The business summary show some summary of my business. There are 4 summary on this summary section. F

4. The `purchase' page is a private route. The private route redirects to the login page if the user is not logged in. After login, the user will be redirected to the page he/she wanted to go to. Also, after reloading the page of a private/protected route, the user is not redirected to the login page. 


5. On the Purchase page, users will be able to change the order quantity (increase/decrease) in an input field. The initial value of the quantity will be the minimum order quantity. However, the user won't be able to reduce the quantity below the minimum order quantity mentioned on the tool/part. Also, the order quantity can not be higher than the available quantity. You will display an error and disable the purchase button in both cases.

6. There is an email/ password (login/Register) based login system. The registration form should have the name, and once a user is logged in, the user name and the logout button should appear on the header, which will log out the user once clicked. 

7. If a user is logged in, they will see another option on the header is called `Dashboard`. Inside the dashboard, a user (not an admin) will see options like `My Orders`, `Add A Review`, `My Profile` options on the side nav. This is the time to implement a nested route. Based on your website idea, you can change the name of these menu items. The My Profile link will be open for everyone. This means every user will be able to see my profile link and update their profile.

8.  On `My Orders` page, the logged-in user will see only their orders. If the user wants, they should be able to cancel (canceling is just deleting the order) any order that is not paid yet. Ask for a confirmation message before canceling an order. Do not use browser default confirm. Instead, use a good-looking modal. 

9. On the `My Orders` page, there is a payment button for each order. The user has not paid yet. The pay button will take the user to the payment page. The user should be able to pay by using a credit card here. The payment page will display order details. Once the payment is completed for an order, the user will see the transaction id for that order on the my orders page.

10. On the `Add A Review` page, users should be able to add a review. A review will contain ratings ( a number 1 to 5 and a description). 

11. Also, in my website there is a `My Portfolio` route. 

12. There is a  404 page (not found page). 



### Features-02:

1. Meaningful `readme.md` file on both the client and server sides.

2. The website responsive. Make sure the site looks different on desktop and mobile responsive. 

3. My website has a relevant name. Images and all the content of the website is appropriate. 

4. Clean and organized Code. 

5. On the `Manage All Orders` page for the admin, the logged-in admin will see the orders placed by every user. If multiple users use this website to place orders, everyone's order will be displayed here. The orders that are not paid will show `unpaid`. And the orders that are paid, an Admin can update the status of a paid order. After placing an order and completing the payment, every order will have a default status: `pending`. On the Manage All Orders page, an admin will be able to update the status of the pending to `shipped` status. This could be a simple button to update the pending status. Also, the admin will be able to cancel that is not paid yet. Make sure to add a confirmation before deleting.

6. Implement the basic version of the `jwt` token. 
7. Similarly, I protect the admin route and on the server side verify the admin level api requests.

8. on the `Manage Products` page, an admin can delete any products.  After deleting that product will not appear on the `home` page.

9.  Use `react query` for at least one API call.

10. Use `react hook form` at least one form. For the rest of the forms, user can either use react hook form or basic html form or any other form you want.



### Features-03: 

1. I add animation in the home page and other places.
2. I use `axios` and implement interceptors to inject authorization headers in one place other than adding an authorization header for every call separately.
3. Send a confirmation email after placing an order. Even if the email doesn't get sent or goes to the spam folder. Also, it will be nice to send an email once an order is shipped to the user.
4. On the `Manage All Orders` implement a button to show all pending orders. Another button to show all shipped orders, all unpaid orders. Add search to find an order by email address of a user. The list of orders could be sorted by the newest one at first. I Consider implementing pagination on this page.
   
5. Display order status on the `My Orders` page. So that a user can see the status of the order whether it is pending, or shipped.
6. Use google font.
7. Our footer is  realistic.
8. Optimize my images
9.  Replace the default react favicon and give an icon for your website.
10. Display the latest (newest) 6 reviews on the home page.


### Additional information

1. I use local image or host image anywhere or both.
2. I use tailwind css. Also, I use component libraries.
3. Host my site on Firebase.
4. Host my site on Netlify.
5. Deploy my server-side code to Heroku. 

