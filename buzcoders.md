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
      A web agency website for a marketing company that specializes in websites, SEO, paid ads etc.

      It was exciting and interesting work on this project, to say the least. 

      I handled from start to finish. Let go through it.

      The designed layout immediately capture attention with a bold hero section, strong messaging, and a clear call to action. The structure guides visitors naturally through the page, from understanding what the company does, to seeing real project examples, to learning about the core values behind the brand. Every section was intentionally placed to support clarity, credibility, and conversion.


      On the development side, It was built using a responsive, component based approach to ensure performance, scalability, and maintainability. The entire interface adapts smoothly across devices while maintaining a polished and professional look.

      Wordpress CMS API was the ideal tootl. to use since 

      Overall, this project reflects my ability to take an idea from concept to completion, combining strategic design thinking with solid technical execution to create a website that not only looks good, but works effectively.

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
      Beyond the frontend design, I also developed the backend using Laravel to power a structured service desk system. The goal was to create a reliable internal platform where client inquiries, project requests, and support tickets could be efficiently managed. The system allows administrators to track requests, update statuses, assign tasks, and maintain organized communication logs. Built with Laravel’s MVC architecture, the backend ensures clean code structure, secure authentication, and scalable database management. This setup provides both stability and flexibility, allowing the platform to grow as the business expands. By combining a polished frontend with a robust Laravel backend, the project delivers not just a website, but a complete operational solution that supports real client workflows.

      Initially, the entire platform was built on Laravel, serving both as the public-facing backend and the internal service desk system. Laravel handled everything — contact form submissions, booking requests, administrative workflows, and content-related logic. While this unified structure worked well in the early stages, the application began to grow in scope and complexity. To improve scalability, maintainability, and long-term flexibility, we made a strategic decision to decouple the system based on features and responsibilities.

      The first step was identifying clear domain boundaries. Laravel remains the core backend for transactional logic — handling contact form submissions, booking management, authentication, database operations, and business rules. It now functions primarily as a secure API layer responsible for structured data processing and workflow control.

      For content management, we introduced WordPress as a dedicated CMS. This separation allows marketing content, blogs, and static pages to be managed independently without affecting application logic. It empowers non-technical users to update content while keeping the operational backend stable and focused.

      For internal operations, we developed a dedicated service desk application using React. This frontend application is used by agents to raise tickets, manage requests, and follow structured workflows. It communicates with the Laravel API to retrieve and update ticket data in real time. By isolating the service desk into a React-based interface, we achieved a more responsive and interactive experience tailored specifically to operational users.

      This decoupled architecture creates clear separation of concerns:

      Laravel → Business logic, bookings, contact handling, API layer

      WordPress → Content management and marketing pages

      React → Internal service desk interface for agents

      The development workflow followed a structured approach. We began by modularizing the Laravel backend into clearly defined services and API endpoints. Next, we integrated WordPress as a content layer while preserving routing boundaries. Finally, we built the React service desk as a client application consuming Laravel APIs, implementing authentication, role-based access control, and ticket lifecycle management.

      This architectural shift improved scalability, performance optimization, deployment flexibility, and long-term maintainability. It also enables independent iteration: content updates, backend enhancements, and service desk improvements can now be developed and deployed separately without disrupting the entire system.
      
  ui_focus:
    title: 'User Interface Focus'
    description: |
      For the backend interface, the initial priority was usability and speed of implementation. We adopted a Bootstrap-based admin template as the foundation for the service desk system, allowing us to rapidly establish a clean, structured, and responsive layout. The template provided consistent components such as navigation menus, tables, forms, and dashboards, which were then customized to match our workflow requirements and internal branding. Adjustments were made to improve clarity in ticket statuses, booking visibility, and task management, ensuring agents could process requests efficiently without unnecessary friction.

      Because the backend is used by operational staff daily, the focus was not purely aesthetic but functional — prioritizing clarity, readability, and workflow efficiency. Forms were simplified, ticket states were visually differentiated, and dashboard elements were structured to reduce cognitive load during high-volume activity.

      As the project evolves and we continue decoupling the system, the UI strategy is also transitioning. The long-term goal is to replace the template-based backend interface with a fully component-driven React application. This shift will allow for more dynamic interactions, improved state management, and a more tailored user experience specifically optimized for service desk agents. The React-based interface will provide better real-time updates, modular UI components, and improved scalability as new workflow features are introduced.

      Since the project is ongoing, the UI layer is progressively being refactored — moving from a template-customized Bootstrap structure toward a more flexible, modern frontend architecture. This ensures that the user experience continues to improve alongside the technical decoupling of the system.
---


