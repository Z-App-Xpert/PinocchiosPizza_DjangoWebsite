Skip to content
Search or jump to…
Pull requests
Issues
Marketplace
Explore
 
@Z-App-Xpert 
EdZielinski
/
Project3
Public
0
00
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
update readme
 master
@EdZielinski
EdZielinski committed on Aug 2, 2018 
1 parent 364eaf9 commit a68a6a053242573813e8ed14ad2333612f2c54c2
Showing  with 1 addition and 1 deletion.
  2  README.md 
@@ -69,7 +69,7 @@
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- For the Register_user function, If they are submitting the form then the user will be registered.  User and password will be taken and try to create a new user, if a user already exists then it will be invalid, then it will give an error.  Then if it passes, the Cart is created for the User.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Next is the logout_user. The system will be notified that this user is logged out and the login page will open.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Profile_user contains the user details, when a user is logged uses the request  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Next is order, this is the page where you order things. The menu is created and stored as a dictionary. The menu is created using the three tables, then you get the cart and you clear the cart, but if something already exists then you are adding it to the order and the user may then add more items. The sub options are stored differently and displayed differently then than the Regular Pizza and the Sicilian Pizza. The temp_vars are sent to the order_food.html page. The order page relies heavily on the order.js file in the static folder.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Next is order, this is the page where you order things. The menu is created and stored as a dictionary. The menu is created using the three tables, then you get the cart and you clear the cart, but if something already exists then you are adding it to the order and the user may then add more items. The sub options are stored differently and displayed differently than the Regular Pizza and the Sicilian Pizza. The temp_vars are sent to the order_food.html page. The order page relies heavily on the order.js file in the static folder.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- In cart, we just get the Cart if there are items in it, then we return it.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- In orders, If there are no orders the return no items found, otherwise get the orders.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- In show_order, first check to see if user is a superuser and display order if true, otherwise display the users order. If the order is not found then redirect them to orders.  
0 comments on commit a68a6a0
@Z-App-Xpert
 
 
Leave a comment
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
 You’re not receiving notifications from this thread.
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete
