---
layout: project
type: project
image: images/alpha2.jpg
title: Alpha Blog
permalink: projects/alphablog
# All dates must be YYYY-MM-DD format!
date: 2019-06-03
labels:
  - Rails 5
  - Bootstrap
  - Ruby
summary: An article management app that allows users to sign up,create articles and publish.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

Alpha Blog is a web based application that allows users to create and manage articles. Once a new user signs up, he/she can create, edit and delete articles, view articles by other users, search for an article using several categories, edit their profile and view profiles of other users. 

For this project, I started by analyzing, reviewing and understanding the requirements in order to determine the functionalities and features that are appropriate and needed in the software system. I then delved into the development process, using mostly the adaptive model of the RAD (Rapid Application Development) approach. I did a detailed design on a plain sheet paper to illustrate the assets and elements of the U.I.

Here is a picture of the design paper:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```
In the development, I created the app using Rails 5, build a custom authentication system from the scratch, added styling using bootstrap classes, build one-to-many and many-to-many associations, add profile images using gravators and used pagination for listing views.

You can learn more at the [Alpha Blog Website](https://alpha-blog-mantoss.herokuapp.com).



