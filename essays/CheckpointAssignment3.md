---
layout: essay
type: essay
title: "E3: Preparing for WODs Technical Essay"
# All dates must be YYYY-MM-DD format!
date: 2022-09-27
published: false
labels:
  - Essay
---

<body>
  
Show what each page will look like. The pages do not have to be “functional” but the design should clear. Here is an example PPT prototype
  
<img width="950" alt="Screen Shot 2022-11-30 at 12 48 52 PM" src="https://user-images.githubusercontent.com/112213087/204924867-4748b16c-edcc-4c44-be2b-af1e336acaa8.png">


Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.
  
I will have a cart on a separate page that doubles as an invoice and using sessions I will store cart session in a product key from products_display and then use a get on the server to request the key into quantities that then gets added to the cart. For example, selecting 10 hibuscus from the flower page will add 10 flowers to the cart which will display in the top corner with "you have 10 items in your cart". As you continue shopping for items this number should continue going up. Hitting the make purchase button in the cart should then finalize your order and send you an email with documentation of your purchase.

Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.
  
I would like to store product quantities, images, and favorited products in the session. The session will contain a key  from our products json file and then 
  
How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?
Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)
If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?
How are you approaching Assignment 3 differently than Assignment 2?
</body>
