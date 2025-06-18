# Requirements

##  Must Have

-  Real-time messaging between users (Socket.IO)
-  Collaborative task boards (Kanban-style)
-  Real-time notifications for mentions, task updates, etc.
-  Multi-tenant architecture (isolation of orgs)
-  FastAPI backend with JWT-based auth
-  Redis for pub/sub and caching
-  Role-based access control within teams
-  User and organization management (CRUD)
-  Persistent storage of tasks, messages, and notifications

## Should Have

-  Customizable workflows per organization (e.g., task states)
-  Search across messages and tasks
-  API access for integration with other tools
-  Minimalist responsive frontend (React/Tailwind)

## Could Have

-  Message reactions and file attachments
-  Slack/Trello migration tools
-  Desktop PWA support

##  Won’t Have (initially)

-  Video/audio calling
-  Third-party plugin marketplace
