# Web Dev Starter Code

## Project Spec

What is the general theme? For example, a photo gallery, recipe repository, Twitter clone, e-commerce inventory, API-driven data mining,
generic wedding, a message board for the class, dentistry, etc.

What is it going to do? For example: draw customers to a photography business by showing a portfolio, pricing, contact information, and booking.
Mine data from IMDB to answer questions about movies and movie stars. Forum to facilitate communication between users. Etc.

Who is the target audience? For example: The general public, family members, research scientists, students, etc.

What sort of data will it manage? This doesn’t include static data, such as logos, headers, and footers. Think of any data that will be dynamically generated
based on user form input. For example, user comments, uploaded images, credit cards, etc.

Stretch Goals? Once your project is fully functional and demonstrates adequate scope, what extra features do you want to implement? What additional gold
plating would make your website utterly awesome? Stretch goals aren’t part of your grade; they are just for your own satisfaction.

The general theme will be a general store that sells bushcraft and modern survival equipment for customers. What the website is going to do is draw
customers in who are in need of supplies to get them through the day, the website will be a game based item shop so it's not going to be selling real
items but items related to an massive multiplayer online game. The MMO game won't actually exist, but the website would be designed in a way where if
it did exist that this is how the website would function.

The target audience will be people who are playing the mmo game mentioned before and it will cater to their expectation on how an online market should
look like. So the target audience would be anyone who is mature, 18+, as the mmo itself would be a mature game. I am aware of the University policies,
so it will only be g-rated items for the market available at this time.

The audience will be interested in buying variety of gear sold by many merchants across the mmo game. The areas will be displayed on the website itself in
one of the pages, and it will be in a png map either made by myself or from external software. It will also try to compare item prices from all these different
merchants.

I will try to implement arificial inflation just to make things interesting. If this doesn't pan out please don't penalize me, because I know it will be
difficult. However, I do know it is do able, even if it isn't for myself.

The data it will manage goes like this, image, item name, item price, seller name, location of seller (in the game), quantity of items, taxes, item size
(for clothing), item color, and item description. All of these qill be unique to each item, so no item will have the same qualities. If something
is left out we will address it later on.

Most of the data will be backend but some of the mentioned data will be calculated in the frontend. Such as taxes and qunatity will be frontend based.
The majority of the data will be handled server side. The rest of the website would just be handling both the front end and backend data, and
manipulating the data as needed.

So the home page will be an introduction to the mmo and some features that are in the mmo. The second page will be where you upload items and the merchant names
into the database as well as their locations and delete items based on ID. The third page is data retrieval which will be handled two ways, all data from the server
or just a selected item(s) based on your keywords, pick the item(s) you want then the quantities of each and reveal the total price of the item(s). The fourth page is
the list of locations using the png and location descriptions.

Well, once this market is up and running, I would try to see what else I can implement on my website such as a user database and ofcourse some
security features to the user database. Such as hashing user passwords, user privledges on the website (regular user, moderator, and admin alike).
Then I would see how I would implement this market into the actual game itself (if it were real), so it can be dynamic.

## Project Wireframe

TODO: Replace the wireframe below with you own design.

![wireframe](wireframe-example.png)

## For me

Below is a detailed breakdown of the requirements.

    To get a C- on this project you need to do the following:
        Have a landing page (index.html) 
        Have a form on the index that allows you to submit data to AWS
        Have a button that retrieves ALL your database entries and displays them on the page
        Have a a way to delete entries
        Have between 2-5 CSS styles 
    To get a B- on this project you need to do the following:
        You must complete 100% of the requirements of  the C- project
            You must have at least 3 distinct pages, you can not have everything implemented in index.
        You must have a separate page (not on your index.html) with a form that submits data to AWS
        You must have a way to conditionally retrieve data and display it on a separate page. You can do this any way you wish,
		but you can not just return the entire database.
        You can include as many extra pages as you wish there is no limit.
        Have between 6-10 CSS styles 
    To get an B on this project you need to do the following:
        You must complete 100% of the requirements of  the B- project
        You must have each page styled with custom CSS
        You must have authored some tests
        Have between 11-15 CSS styles 
    To get an A- on this project you need to do the following:
        You must complete 100% of the requirements of  the B project
        All your forms must properly sanitize user input
        You must have 80% code coverage of ALL your front end JavaScript
        You must have at a minimum of 4 different HTML pages that perform distinct functionality.
        Have between 16-20 CSS styles 
    To get an A on this project you need to do the following:
        You must complete 100% of the requirements of  the A- project
        100% of your pages MUST get a perfect lighthouse score for accessibility in chrome (NO EXCEPTIONS AT ALL)
        Have between 21+ CSS styles