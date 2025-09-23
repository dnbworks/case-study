---
title: 'Restaurant POS'
date: '2023-03-17'
description: 'This is a point-of-sale system designed specifically for restaurants. My inspiration came from my previous experience working in a restaurant, where I was fascinated by how the POS system functioned. Some of the logic behind it was surprisingly simple, yet I was intrigued by how it was implemented.'

banners:
  - src: 'pay.png'
    alt: 'Conversation interface of iplcollege website'
  - src: 'meals.png'
    alt: 'Homepage design of iplcollege landing page'
  - src: 'slots.png'
    alt: 'User interface elements of iplcollege site'

sections:
  overview:
    title: 'Overview'
    description: |
      This is a point-of-sale system designed specifically for restaurants. My inspiration came from my previous experience working in a restaurant, where I was fascinated by how the POS system functioned. Some of the logic behind it was surprisingly simple, yet I was intrigued by how it was implemented. This curiosity led me to start a personal project to build a similar system, which helped me explore and learn technologies like React.js and Redux Toolkit
  tech:
    title: 'Tech Stack'
    items:
      - ReactJS
      - Redux Toolkit
      - MongoDB
      - ExpressJS
      - NodeJS
      - Authentication
      - TailwindCSS
      - TypeScipt
      - Adobe XD
  type:
    title: 'Project Type'
    value: 'Freelance'
  problems_and_solutions:
    title: 'Problems and Solutions'
    description: |
      Moving orders to other tabs

      In the restaurant, once an order like a Carbonara is placed, a receipt is immediately printed and sent to the kitchen. The kitchen staff and chefs begin preparing the meal right away. However, if a customer later decides to cancel the order, the system doesn't allow it to be voided, since it's already been recorded as a sale.
      To handle this, we adopted a workaround: if another customer comes in later that day and orders the same item, we would assign the original (now unwanted) order to the new customer's tab. This approach prevents the order from being wasted and avoids having to cancel it, which the system does not permit due to how sales are tracked.


 
  ui_focus:
    title: 'User Interface Focus'
    description: |
      The UI was designed with simplicity and efficiency in mind, aiming to replicate the smooth experience of modern POS terminals. I focused on creating an intuitive, clean interface that minimizes user error and supports fast-paced environments like restaurants and cafés.
---


