---
layout: project
type: project
image: images/admin.jpg
title: University Admin
permalink: projects/universityadmin
# All dates must be YYYY-MM-DD format!
date: 2020-12-27
labels:
  - React Router
  - Styled Components(CSS in JS)
  - Firebase
  - Docker
summary: A university admin dashboard for managing courses (under construction).
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/admin2.jpg">
  <img class="ui image" src="../images/admin.jpg">
</div>

A simple application for a university admin to manually chose courses for students.

This is a private project to demonstrate the use of React Router and Compound Components with Firebase Authentication and Docker. It's still in development.

TECHNOLOGIES OVERVIEW

React
React Router
Styled Components(CSS in JS)
Firebase (Authentication)
Docker
DESIGN PATTERN: Compound Components - a design pattern in React in which a component is composed of a subset of child components that all work in tandem to produce some functionality.

HOW TO RUN & TEST PROJECT?

CLONE THE PROJECT

git clone https://github.com/PJMantoss/university-admin.git

INSTALL DOCKER

sudo apt install docker-ce (NOTE: Make sure you install Pre-requisite Packages and add Docker Repositories before installation)

INSTALL DEPENDENCIES

yarn add react-router-dom

yarn add styled-components

yarn add normalize.css

RUN DOCKER IMAGE

sudo docker run reactimage

OPEN A NEW TERMINAL WINDOW

run sudo docker ps (inside the new terminal)

run sudo docker exec -it [CONTAINER ID] sh (replace CONTAINER ID with the actual values displayed in previous step. Type it in without the angle brackets []).

type ls after /app # and press enter to see contents of container

run npm start

when asked whether you'd like to run app on another port, type y

Open another terminal tab/window to start project

START THE PROJECT

yarn start

TEST PROJECT

yarn test

To learn more see codes at <a href="https://github.com/PJMantoss/university-admin"><i class="large github icon "></i>Github</a>

[University Admin Website](#).