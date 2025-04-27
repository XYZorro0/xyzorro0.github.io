---
title: "University Form"
excerpt: "University form system for approvals with multi-level workflow management."
collection: portfolio
---

This is a web application for managing university form workflows, primarily built with Flask and SQLAlchemy. The system appears to be designed for the University of Houston (UH) and handles several types of academic forms:

Medical/Administrative Term Withdrawal requests

Student-Initiated Course Drop requests

FERPA (Family Educational Rights and Privacy Act) release forms

Name/SSN Change requests

The application features different user roles (student, department chair, president, admin) with varying levels of permissions. Students can submit forms which then require approval from administrators or department chairs in a configurable multi-step workflow. The system stores form data in a database and generates PDF documents for the forms using LaTeX templates.

Technical aspects include user authentication (including Microsoft OAuth integration), role-based access control, PDF generation, file uploads for signatures and documentation, and a structured database schema for various form types.