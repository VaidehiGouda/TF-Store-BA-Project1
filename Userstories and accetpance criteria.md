# TF-Store-BA-Project1

User stories 
Homepage
As a shopper, in a shopping app, I want a homepage that shows me different shopping categories, 
So that, I can decide what to browse.
Acceptance Criteria
Design a webpage that has components like profile, search bar,categories, trending dresses, menu, app name.
Each category is a clickable link, giving different options.
Given, I click the app on my phone 
when the app opens
then, I should view a homepage

Given, I open the app
when the homepage appears
then, I should see options for shopping, profile, display dress categories, My cart, search bar, Menu, app name
Given, I am on homepage
when I see different options
then, all the options should be clickable to next page

Given, I open the app
when the homepage does not load
then an option to reload or exit must appear

Given, I open the app
when some parts of the homepage loads
then a message asking to reload app appears

Given, I click the app in my phone
when the request is being processed by system
then, homepage must appear within 6seconds

Search bar optimisation
I want a search bar that understands my needs
So that, I can get/ choose what I want
Acceptance Criteria
Make a search bar which takes keywords
Click the search bar to enter text
match it with the existing items in the app
filter those results
Given, I open the app
when on the browsing page
then, there should be a search bar

Given,I click the search bar
when I type the keywords and enter
then, it should display the relevant search results

Given, I enter the words in the search bar that yields no results
when the search is complete
then, it should display message saying "no results"

Given, I enter special characters in between words in the search 
when it processes search
then,I should get valid search results
Given, I enter valid keywords in the search bar
when the system processes request
then, the page must load within 5 seconds

Given, the search bar is present
when I type less than 3 letters
then, it should dislay message saying "enter more letters"

As a shopper,
I want the profile at one corner of the page at all times,
So that,I can view and click to go to my profile to verify or make any changes.
Design the page such that the frame remains all the time
this frame contains the options with links enabled
menu, profile, app name, home are these options

Given, I open the app
when the pages are loaded
then, I should see the profile at all times

Given, I am on any page  in the app
when The profile appears in the page 
then, it should be clickable taking to the profile page.

As a shopper,
I want to be able to add an item to the cart and view it later
So that, I can not miss out on my favourite items.
Acceptance Criteria
Create a list called cart specific to user
Put an option "Add to cart" under each item
When cliked add the item to respectice cart
View cart in user profile
On clicking cart show all items in the cart

As a shopper,
I want to see all available colors of one dress, with price, material made of, sizes
So that, I can pick the desired dress and mark it for shopping
AC-	for each item display the name, image, price, size,  materials etc
Also put other options- Add to cart, In stock



I want to enter minimum personal details, and all entered data should be secure
So that, I need not share much personal data just for a shopping app, data safety
While creating the user profile take username, pwd, address, phone email, name, and store it in the company database.
No unauthorise from the company or no third party can access that.

I want to make payment through the app
So that, I dn't need to switch to different payment method.
Use third party payment API for transactions
Give limited access to them

I want to track my order after shopping
So that, I am sure my item reaches me.
After order confirmation, generate a shipping link.
Mail it to the user

 