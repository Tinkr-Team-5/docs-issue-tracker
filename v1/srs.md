# Project Specification

## Problem Statement
Need an easy way for managers to give their clients a way to open issue tickets for support and to manage these tickets as well as manage the employees who will work on them

## Product Vision
A web application that simplifies the creation and managing of tickets and users

- Share a link to ticket board for customers to open tickets
- Transfer support ticket data (ex: from a contact form) to ticket board via API call
- View and manage all tickets on ticket board
- View and manage all ticket boards
- View and manage all employees
- View data analysis of employee and ticket activity

**Glossary**

- Ticket Board
    - Instance of the ticket management application for a single organization or service
    - Main interface and collection for tickets belonging to a single organization or service
- Tickets
    - Requests for support or help
    - Description of some issue that needs to be addressed
- Clients/ Customers
    - Users of some organization/ service that can only open tickets
- Employees
    - Members of some organization/ service that can assign themselves to a ticket, respond to client, and mark a ticket as closed
- Manager
    - Member who has all the privileges as an Employee + ability to delete tickets, assign other employees to tickets, view data analytic reports on tickets & employee activity, manage employee members access, create/ manage ticket board, etc
    - Product owner
- Admin
    - Developer account that has all the privileges and manage/see all ticket boards

**Users**

- Small businesses
- Freelance
- Contractors

**Features**
| ID | Epic | Priority |
| --- | --- | --- |
| 1 | User Authentication | Must Have |
| 2 | Ticket Management | Must Have |
| 3 | User Management | Must Have |
| 4 | Activity Dashboard | Must Have |
| 5 | Access Management | Must Have |

