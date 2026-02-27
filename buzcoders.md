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

      Using third-party software was an option, but the client preferred a custom system tailored to their needs. The system also needed to be easy for the staff to learn.

      I had to put together a system that had components of prospect outreach and onboarding clients to the client approval process.

      Part of this was putting together an SOP for certain tasks. 

      Transplating that into software that meets the company needs.

      Client outreach
      1. Cold calls
      2. Website Contact form / web email

      Laying down all the prerequisites.
      Tech to use.

      As this was company was a small sized company.
      

      A system for managing customers. Like a CRM. or what is so-called the service desk. So like in a line of business. resolution.
      A system tailored to the company's needs. Where they would assist customers adequately. 

      we defined functional requirements and data flow diagrams. The focus was on how transactions affect inventory stock while retaining data integrity - no editing transactions, proper audit trails, the works.

      Finally, we designed the interface with one principle: simple and straightforward. No frills. Everything warehouse staff needs should be instantly readable at a glance. Nothing hidden for the sake of "minimal" design. These were the initial wireframes on Whimsical.

      Initially, the entire platform was built on Laravel, serving both as the public-facing backend and the internal service desk system. Laravel handled everything — contact form submissions, booking requests, administrative workflows, and content-related logic. While this unified structure worked well in the early stages, the application began to grow in scope and complexity. To improve scalability, maintainability, and long-term flexibility, we made a strategic decision to decouple the system based on features and responsibilities.

      The first step was identifying clear domain boundaries. Laravel remains the core backend for transactional logic — handling contact form submissions, booking management, authentication, database operations, and business rules. It now functions primarily as a secure API layer responsible for structured data processing and workflow control.

      For content management, we introduced WordPress as a dedicated CMS. This separation allows marketing content, blogs, and static pages to be managed independently without affecting application logic. It empowers non-technical users to update content while keeping the operational backend stable and focused.

      For internal operations, we developed a dedicated service desk application using React. This frontend application is used by agents to raise tickets, manage requests, and follow structured workflows. It communicates with the Laravel API to retrieve and update ticket data in real time. By isolating the service desk into a React-based interface, we achieved a more responsive and interactive experience tailored specifically to operational users.


  ui_focus:
    title: 'User Interface Focus'
    description: |
      For the backend interface, the initial priority was usability and speed of implementation. We adopted a Bootstrap based admin template as the foundation for the admin system, allowing us to rapidly establish a clean, structured, and responsive layout. The template provided consistent components such as navigation menus, tables, forms, and dashboards, which were then customized to match our workflow requirements and internal branding. Adjustments were made to improve clarity in ticket statuses, booking visibility, and task management, ensuring agents could process requests efficiently without unnecessary friction.

      Since the project is ongoing, the UI layer is progressively being refactored, moving from a template-customized Bootstrap structure toward a more flexible, modern frontend architecture. This ensures that the user experience continues to improve alongside the technical decoupling of the system.
---


