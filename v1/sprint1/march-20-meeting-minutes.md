# March 20 Meeting Minutes

**Roles**
- Frontend: -TheG-
- Backend: mkgrtx
- Other: risby

**Sprint deliverables**
- Ticket form page
  - Create tickets
  - Success/ fail notification
- Tickets page
  - View all tickets
  - View single ticket detail

**Sprint Deadline**
- Monday March 27

**Standups**
- We agreed to share our updates/progress every other day

**Other**
- Frontend can use [json-server](https://www.npmjs.com/package/json-server) to mock API
  - Create `db.json` with mock data
  ```json
  {
    "tickets": [
        {
            "subject": "ticket title",
            "description": "ticket details",
            "emailAddress": "ticket-creator@email.com",
            "creationDate": "2012-04-23T18:25:43.511Z",
            "editDate": "2012-04-23T18:25:43.511Z",
            "ticketNumber": 1,
            "name": "Ticket creator name"
        },
        {
            "subject": "ticket title 2",
            "description": "ticket details 2",
            "emailAddress": "ticket-creator2@email.com",
            "creationDate": "2012-05-23T18:25:43.511Z",
            "editDate": "2012-05-23T18:25:43.511Z",
            "ticketNumber": 2,
            "name": "Ticket creator name 2"
        },
        {
            "subject": "ticket title 3",
            "description": "ticket details 3",
            "emailAddress": "ticket-creator3@email.com",
            "creationDate": "2012-06-23T18:25:43.511Z",
            "editDate": "2012-06-23T18:25:43.511Z",
            "ticketNumber": 3,
            "name": "Ticket creator name 3"
        },
    ]
  }
  ```
  - Create npm script command to launch json server: `"server": "json-server -p3001 --watch db.json"`
  - Use `http://localhost:3001/tickets` for API calls
- PM can  use [swagger](https://editor.swagger.io/) to design API specifications for backend and frontend to implement and consume
- We can use [figma](https://www.figma.com/) to create basic mockups/wireframes for frontend to implement

