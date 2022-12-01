---
layout: essay
type: essay
title: "E3: Preparing for WODs Technical Essay"
# All dates must be YYYY-MM-DD format!
date: 2022-11-30
published: true
labels:
  - Essay
---

<body>
  
Show what each page will look like. The pages do not have to be “functional” but the design should clear. Here is an example PPT prototype
  
<img width="950" alt="Screen Shot 2022-11-30 at 12 48 52 PM" src="https://user-images.githubusercontent.com/112213087/204924867-4748b16c-edcc-4c44-be2b-af1e336acaa8.png">


Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.
  
I will have a cart on a separate page that doubles as an invoice and using sessions I will store cart session in a product key from products_display and then use a get on the server to request the key into quantities that then gets added to the cart. For example, selecting 10 hibuscus from the flower page will add 10 flowers to the cart which will display in the top corner with "you have 10 items in your cart". As you continue shopping for items this number should continue going up. Hitting the make purchase button in the cart should then finalize your order and send you an email with documentation of your purchase.

Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.
  
I would like to store product quantities, images, and favorited products in the session. The session will contain a key that matches a product from our json file and then adds it to our cart. This code from Assignment 3 is what I will use to generate the form and then send it to the server which should add it to the cart in a session. 

![Capture](https://user-images.githubusercontent.com/112213087/204969728-698a2c3a-5eeb-4d59-bc95-5fe8902c244e.PNG)

  
How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?
I have not reached this point yet, but I think that we will search if a cookie exists with the user_name when a user logs in. If there is no cookie with user_name then we do not allow them to access that page. For this assignment we have to destroy the cookies on logout to prevent someone from accessing the information.
  
Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)
I want to add a button that changes the theme from light/dark and use a function to save it in a cookie, I have also seen many people using local storage, but this is a problem for the future.
  
If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?
  Work by myself
How are you approaching Assignment 3 differently than Assignment 2?
Assignment 3 seems much harder than 2 because there are so many new concepts that we have not learned so I will be using more online resources and trying to incorporate the code examples because there was a fact that said we could get a fully functioning assignment 3 using just the examples and labs.
</body>
