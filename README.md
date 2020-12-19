# Bootcamp 03-Homework Assignment: Bootstrap Portfolio Website
## Description
This week's homework assignment was to build a mobile responsive portfolio site using Bootstrap. I was tasked with creating pages for Home/About, Portfolio, and Contact. Other requirements were a navbar, responsive layout, and responsive images. Another goal was to minimize the use of media queries by taking advantage of bootstraps grid layout system, and to code accessibily with alt tags and semantic html.

## My Approach
I started by linking to the external CDNs for Bootstrap CSS and JavaScript and jQuery. I ran into some problems with getting the navbar "hamburger" icon functional on responsive layout, which it turned out was related to the order I was loading external javascript files.

For layout, I started by using the dark navbar theme from the Bootstrap components page. Then, I built out a content grid of a hero image with a class pulled from W3 schools, a main content section with a bio, a little section for my two cats below that, and a sidebar up top with links to my bands. I filled those sections with placeholders and styled in CSS, including some font, color, and spacing tweaks. Then, I created a sticky footer with copyright info and my social media buttons. I found something on Bootsnipps that I modified to make the social media icons scale up when hovered over, which I like.

Once my homepage content sections were finished, I filled it in with my actual content - biographical information, live links in the sidebar, cat pics, and cat stats.

Then, I went on to the Portfolio section, which I built in a similar manner -- gridding it out, filling with placeholders, then populating with actual content. In this case, I featured some recent professional projects from work, a few spotify recordings I play keyboard on, and some videos of my bands. The biggest challenge there was the responsive video iframe section, but I found a solution that I'm satisfied with from Bootstrap's documentation.

Finally, I built the contact form with a two column section for email and phone contact info.

## Final Thoughts
My inspiration for this page was a basic full-width site that is very popular in modern design, featuring large, uncluttered elements, like many squarespace sites. I'm happy with the progress I made learning how to build out sites using the grid content system. I'd like to learn a bit more of the backend material to make things like contact forms actually send an email, and perhaps to find a cleaner responsive video solution.
