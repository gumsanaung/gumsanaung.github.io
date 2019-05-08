---
layout: project
type: project
image: images/manoacart-landing.png
title: ManoaCart
permalink: projects/manoacart
date: 2019-05-07
labels:
  - Web Development
  - IntelliJ
  - Meteor
  - Cloudinary Widget
  - Semantic UI React
summary: Created a website that would serve as a platform for students to sell their items with a team
---
<img class="ui medium centered image" src="/images/manoacart-landing.png">

For the last project of the software development class in UH Manoa, I and four other students in the class worked together for a website that would allow UH students to sell their used school supplies etc. I contributed to both the front and the back end of the site. The first major thing I did was to create a schema that would store the user's information correctly and define what king of input is acceptable for the data. With this data collection up and running, I made a sign up page and also made some default imports for when the server restarts with proper publications of the data.

<img class="ui medium centered image" src="/images/manoacart-signup.png">

We used Cloudinary for our user profile pictures since we did not want to store the data ourselves. This meant that we had to utilized the tools and API provided by Cloudinary to properly integrate their services. It was the hardest feature that I implement and I learned a lot about how to use scripts and how to handle data returned from an external source. I could not implement the signed upload because of my lack of knowledge in generating signature for each upload. I had all the data needed to generate the signature and attempted to but when I used it, the upload never completed. I hope to learn more about this area in the future but for now, I am very satisfied with the progress I made with this project.

<img class="ui medium centered image" src="/images/cloudinary-widget.PNG">

GitHub: [Here](https://github.com/aloha-supply-co/ManoaCart)
