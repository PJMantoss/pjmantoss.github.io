---
layout: project
type: project
image: images/pixstore.jpg
title: Pix Store
permalink: projects/pixstore
# All dates must be YYYY-MM-DD format!
date: 2020-12-01
labels:
  - React JS
  - CSS Grid
  - Github
summary: A mock e-commerce site built with React.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/pixstore.jpg">
  <img class="ui image" src="../images/pixstore2.jpg">
</div>

Pix Store is a mock e-commerce site built with React. The idea is for users to visit the site, look at the available pictures, choose some of them to be printed so that they can order them to be printed and shipped to them. Images on the list can be favorited or added to the cart and then on the cart page, a user can see the images he added and then proceed to place his/her order or remove some of the items he/she does not want anymore. On the cart page a user can also the individual and total cost of the pictures he/she selected.

The reason for this project is to test my understanding of React Router, React Hooks, Custom Hooks, Context and PropTypes. The project was styled with CSS grid.

After creating the basic structure (components and pages) of the site, I set up React Router which connects the links in the header to all the relevant pages and components (Cart and Photos). Then I set up Context for the app in a separate file. 

In the context file I created a custom component that renders the provider of the context created. Then I exported the provider component so it can be eventually passed to a useContext hook.

Still in the context file, inside a useEffect hook, I imported JSON data of the photos information from an API using fetch and saved the data in a state. Then using the data in the context state I map over it in the photos page and display the images.

CHALLENGES: The major challenge I experienced was how to display a favorite-icon and a add-to-cart icon when a user hovers over an image. 

SOLUTION: To solve this I created a Hovered state(a boolean) and tracked it in the Image component.

You can learn more at the [Pix Store Website](https://pjmantoss.github.io/pix-store/#/).

<a href="https://github.com/PJMantoss/pix-store"><i class="large github icon"></i>Github Repo</a>
