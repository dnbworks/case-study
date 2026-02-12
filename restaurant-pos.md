---
title: 'Restaurant POS'
date: '2023-03-17'
description: 'This is a Point of Sale (POS) system designed for restaurants. My inspiration came directly from the system we use at Cielo Alto Place, where I currently work, I was amazed by how the POS system functioned. Some of the logic behind it was surprisingly simple, yet I was intrigued by how it worked.'

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
      While I was learning myself React, I brainstormed various projects to build. Most of the ideas I found online were a bit too basic, and I wanted to challenge myself with something more complex. I began admiring the logic behind our workplace POS, amused enough. I started sketching the UI screen by screen. whenever the cashier placed orders. This project is a functional replica of that system.

      Key Logic & Features
      The system follows a specific operational flow:
      Order Finality: Once an order is placed, it cannot be canceled.
      Order Management: To handle mistakes or changes, users have the option to either complete the sale or transfer those items to a different order.
      
      Exploring the "why" behind these features was fascinating. While some of the logic seemed simple on the surface, implementing it correctly required a deep dive into state management. This curiosity drove me to use React.js and Redux Toolkit, which allowed me to manage complex order states effectively.
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
      Order Reassignment

      In a fast paced restaurant environment, efficiency is key. Once an order such as a Carbonara is placed, a receipt is instantly generated and sent to the kitchen for preparation. Because the system records this as an active sale immediately, the order cannot be voided or canceled.

      To manage this, the system allows for order reassignment. If a customer needs to change their mind after the kitchen has started cooking, the unwanted item is held in the system. When a subsequent customer orders that same dish, the staff can simply transfer the original entry to the new customer's tab. This method ensures that sales records remain accurate and prevents food waste while adhering to the system's strict "no-void" policy.


 
  ui_focus:
    title: 'User Interface Focus'
    description: |
      The UI was designed with simplicity and efficiency in mind, aiming to replicate the smooth experience of modern POS terminals. I focused on creating an intuitive, clean interface that minimizes user error and supports fast-paced environments like restaurants and cafés.
---


