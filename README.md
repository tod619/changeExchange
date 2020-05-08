# changeExchange

![Responsive Image](assets/design/responsiveImg.PNG)

## INTRO

ChangeExchange is a website created for a fictional financial company that has a focus on selling currency. The webstie provides a way for users to find out about the company along with the ability to compare the exchange rates of different currency from around the world. The site uses HTML, CSS, Bootstrap, JavaScript, +JQuery to acheive the owners goals.

## DEMO

A working demo version of the ChangeExchange site can be found at:
https://tod619.github.io/changeExchange/

## PROJECT DESCRIPTION + FEATURES

This project is a one page static site that contains six sections. The sites primary goal is to allow a user to interact with the information the site presents in a meanigful way to get information. This interaction is acheived with DOM manipulation which reveals or hides information from the user. Five out of the six sections contains some form of manipulation from JavaScript or JQuery.

1. Navigation Bar: A responsive navbar that sticks to the top of the screen. A smooth scroll function is added using JQuery which smoothly scrolls to links on the page. As the bar stays at the top of the screen additional classes are added or removed depending on the scroll position of the bar. This allows the navigation bar to remain visible even on the lighter sections of the site.

2. Showcase: The showcase section features a dynamic heading which updates the heading with different text through a dynamic typing effect. This effect is acheived using JavaScript.

3. About: This section contains some general information about the company along with a responsive icon that doesn't appear on smaller screens but will appear on larger ones.

4. FAQ: This section contains additional questions that a user might have about the company. Initially the answers are hidden from the users view and only the questions are visable. By clicking on the question the answer reveals itself through an animation. This hiding and revealing data is acheived using JavaScript.

5. Convertor: This section is where the user can check the exchange rates of different currencies. This is acheived by using the fetch api along with a third party api from https://api.exchangerate-api.com. The fetch api makes a call to this the exchangerate api which then returns a promise. We use JavaScript to convert this promise into a JSON object which we can use. With the information that we get form this site we can update the information in the DOM and these changes are presented to the user dynamically.

6. Footer: This is the footer section which contains links to ChangeExchnges social media accounts along with a copright and date. The information in the date section is dynamic and will change as the years roll on. This is acheived through JQuery which simply updates the text of a span with the current year.

## PROJECT STRATEGY

The main strategy that I had in mind when creating this site was to build a visually appealling site that would catch the users eye and that would be intuative to navigate around. I also wanted to create something that would be able to dynamically change sections on the site based on user actions. This was acheived using JavaScript + JQuery.

## PROJECT SCOPE

The scope of this project was to create a site for the ficitional start up comapny ChangeExchange that would allow a user to interact with their exchange rate algorithm which in turn would allow a user to see the different rates that different currencies were trading around the world.

## UI/UX

The layout of the site has been created to catch the eye of any potental customers. The site has a clean style with a serious colour scheme that has been created to present the information to the user in an easy to follow manner. The dark and light color scheme is broken up by the use of a bright lime green colour which adds a hint of freshness to the site. In keeping with the serious tone of the site sans-serif fonts were used for both the headings and the paragraphs as I felt that this was in keeping with the more business like tone for the site.

## USER STORIES

To help develop the site even more I created a few user stories from the company's + user perspectives.

As an owner of the site:
I would like an attractive and eye catching site.
I would like the site to contain information about the company and what we do.
I would like a site that works well on different devices so that users can have the same experience on a mobile or desktop.

As a user of the site:
I would like a site that is easy to navigate.
I would like to be able to interact with the product in a meaningful way.
I would like to be able to find up to date information on the exchange rate.
I would like the exchange rate convertor to be easy to use.
I would like to be able to learn the site once and for this experince to be usable on different devices.

## WIREFRAMES

To help visualize the site I created desktop + mobile wireframes which can be seen below.
