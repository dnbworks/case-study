---
title: 'Buzcoders'
date: '2023-03-17'
period: "June 2022 - Nov 2024"
description: 'A web agency website for a marketing company that specializes in web design, SEO, paid ads etc. I was with Buzcoders from September 2024 - May 2025. When I joined, I initiated the stack to be used for the project'
source_code: 'https://github.com/'
live: 'https://buzcoders.com'
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
      I was with Buzcoders from September 2024 - May 2025 and it was interesting, to say the least. When I joined, I initiated the stack to be used for the project. When I first joined. Buzcoders was a soft opening. Had no website, backend system, and SOP. This led to discussions about the agenda and how to make both client and server side. 

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
      - React
  type:
    title: 'Project Type'
    value: 'Freelance'
  problems_and_solutions:
    title: 'Problems and Solutions'
    description: |

      Problem 1. onboarding client. 

      Using third-party software was an option, but the client preferred a custom system tailored to their needs. The system also needed to be easy for the staff to learn. I had to put together a system that had components of prospect outreach and onboarding clients to the client approval process. Part of this was putting together an SOP for certain tasks. Transplating that into software that meets the company needs.
    

      I built a customer management system, essentially a CRM and service desk tailored to the company’s day-to-day operations. The goal was simple: help staff resolve customer requests smoothly and efficiently.

      Early on, I mapped out the functional requirements and data flows, paying close attention to how transactions affect inventory. Data integrity was critical, no editing past transactions, clear audit trails, and full traceability.

      When designing the interface, I kept one rule in mind: clarity over flash. Warehouse staff should see everything they need at a glance — no hidden actions, no unnecessary minimalism. Just straightforward, practical design.

      At first, the entire platform ran on Laravel, handling everything from contact forms and bookings to admin workflows and content. As the system grew, I split responsibilities to keep it scalable and easier to maintain.

      Laravel now serves as the core API, managing business logic, authentication, bookings, and database operations. I introduced WordPress for content management, allowing marketing and content updates without touching the application logic.

      For internal operations, I built a dedicated service desk app in React. Agents use it to manage tickets and workflows in real time, with a faster and more responsive experience connected directly to the Laravel API.


  ui_focus:
    title: 'User Interface Focus'
    description: |
      For the backend interface, I prioritized usability and fast implementation by adopting a Bootstrap-based admin template. This allowed us to quickly build a clean, responsive layout with consistent components like navigation menus, tables, forms, and dashboards, customized to fit our workflow and branding. I also refined ticket statuses, booking visibility, and task management to help agents work more efficiently.

      As the project evolves, the UI is being gradually refactored from the template-based Bootstrap structure to a more flexible, modern frontend architecture, improving user experience alongside the system’s technical decoupling.
---


