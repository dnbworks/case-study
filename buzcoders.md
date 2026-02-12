---
title: 'Buzcoders'
date: '2023-03-17'
description: 'A web agency website for a marketing company that specializes in websites, SEO, paid ads etc. They contacted me for a landing page.'
source_code: ''
live: ''
banners:
  - src: 'buzcoders-convo.jpg'
    alt: 'Conversation interface of Buzcoders website'
  - src: 'buzcoders-home.jpg'
    alt: 'Homepage design of Buzcoders landing page'
  - src: 'buzcoders-interface.jpg'
    alt: 'User interface elements of Buzcoders site'

sections:
  overview:
    title: 'Overview'
    description: |
      This is a custom-built Point of Sale system designed for restaurants, developed as a portfolio project to demonstrate my full-stack web development skills. The application allows staff to take orders, manage tables, track inventory, and process payments through a clean and responsive interface.
  tech:
    title: 'Tech Stack'
    items:
      - Wordpress API
      - Wordpress CMS
      - Laravel
      - Mysql
      - Javascript
      - Jquery 
      - Bootstrap css
      - AJAX
  type:
    title: 'Project Type'
    value: 'Freelance'
  problems_and_solutions:
    title: 'Problems and Solutions'
    description: |
      Managing complex order flows (e.g., multiple items, special instructions, real-time updates) without confusing the UI
      To support complex order flows without overwhelming users, I designed and implemented a modular component system using React. I leveraged Context API and custom hooks for clear and maintainable state management across components. maintaining a responsive and intuitive interface. Special attention was given to conditional rendering and adaptive UI patterns to handle edge cases such as split bills, order modifications, or simultaneous updates ensuring a seamless experience even under high volume usage.

      Role-based access was difficult to structure cleanly. I needed different permissions for waitstaff, kitchen staff, and admins
      To address this challenge, I implemented robust Role-Based Access Control (RBAC) using JSON Web Tokens (JWT) and backend middleware. Each user receives a role-encoded token at login, which is validated on every request. Middleware logic determines access rights per endpoint and UI visibility rules based on the role. For example, kitchen staff only see pending preparation items, while admins have full access to analytics and system settings. This approach keeps the UI clean and task-focused for each user group, enhancing both security and usability.

      Handling offline scenarios and syncing orders when the connection is restored
      Given the critical nature of uninterrupted order-taking, I implemented a resilient offline-first approach. Using local storage and a custom sync queue, orders are temporarily stored client-side when connectivity drops. A background process monitors network status and automatically pushes pending orders to the server once the connection is restored, resolving any conflicts gracefully. This ensures that users can continue operations without disruption, preserving data integrity and improving reliability in environments with unstable networks.
      
  ui_focus:
    title: 'User Interface Focus'
    description: |
      The UI was designed with simplicity and efficiency in mind, aiming to replicate the smooth experience of modern POS terminals. I focused on creating an intuitive, clean interface that minimizes user error and supports fast-paced environments like restaurants and cafés.
---


