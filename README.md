# QuickDesk – Simple Help Desk Ticketing System

QuickDesk is a clean, user-friendly help desk solution that enables users to raise support tickets, and allows support staff and administrators to manage and resolve them efficiently. The primary goal is to simplify communication between users and support teams without unnecessary complexity.

---

##  Purpose

To streamline technical and customer support through an intuitive ticket-based platform that supports:

- Ticket creation, assignment, tracking, and resolution.
- Role-based access for **Users**, **Support Agents**, and **Admins**.
- Real-time status tracking and communication.
- Efficient filtering and sorting for large ticket volumes.

---

## Users & Roles

###  End Users (Employees / Customers)
- Register and log in
- Create and track support tickets
- View ticket status and conversation
- Receive email notifications on updates
- Upvote/downvote questions (for public queries)
- Search, filter, and sort their tickets
- Edit profile and notification settings

### Support Agents
- View all tickets (filtered queues: All, My Tickets)
- Assign, update, and resolve tickets
- Change ticket status: Open → In Progress → Resolved → Closed
- Add internal comments and replies
- Create tickets on behalf of users

### Admins
- Manage users, roles, and permissions
- Create, edit, and delete ticket categories
- Full system-level control

---

##  Functional Requirements

- User authentication (Register/Login)
- Ticket creation with:
  - Subject, description
  - Category selection
  - Optional file attachments
- Threaded ticket view (timeline conversations)
- Upvote/downvote functionality for FAQs or public tickets
- Email notifications for:
  - New ticket creation
  - Status changes
- Status transitions:
  - `Open` → `In Progress` → `Resolved` → `Closed`
- Search and filter tickets:
  - By status (Open/Closed)
  - By category
  - Sort by most replied / recently modified

---

##  Basic User Flow

```text
1. User registers/logs in.
2. User creates a ticket.
3. Ticket is placed in "Open" state.
4. Support agent picks and updates status.
5. User and agent exchange replies (timeline view).
6. Agent marks ticket as resolved or closed.
