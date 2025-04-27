---
title: "Zoo Database website"
excerpt: "Full-featured zoo management system for both visitors and staff operations.<br/><img src='/images/ZooDB.png'>"
collection: portfolio
---

This project is a comprehensive zoo management system called "Wild Wood Zoo," built using a full-stack architecture. 
The system handles both visitor-facing features and internal staff management tools:

For visitors: 
Ticket purchasing and management,
Gift shop browsing and online purchases,
Animal and attraction information,
Interactive zoo map,
Membership options,
and user profile management.

For staff: 
Dashboard with role-specific views (zookeepers, veterinarians, gift shop clerks, and managers),
Animal health monitoring and management,
Enclosure maintenance and reporting,
Staff assignment and scheduling,
Notification system for important alerts (animal health issues, low inventory),
Gift shop inventory management and sales reporting,
and Revenue tracking and financial reporting for tickets.

The system implements a robust authentication system with JWT tokens that provides different access levels based on staff roles and types.

The architecture follows a clear separation between the backend (Node.js/Express with MySQL) and frontend (React with Tailwind CSS), communicating through RESTful APIs. 

The database design includes relationships between various entities like animals, enclosures, staff, inventory, and sales transactions.

The UI is responsive and user-friendly, with role-based access controls ensuring users only see and interact with features relevant to their roles.