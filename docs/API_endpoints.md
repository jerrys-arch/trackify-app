
# 🔹 API Endpoints List

This document defines all API routes used in the application.

| Endpoint           | Method | Request Body                | Response             | Notes                       |
|--------------------|--------|-----------------------------|----------------------|------------------------------|
| `/api/register`    | POST   | username, email, password   | user object + token  | Create new user              |
| `/api/login`       | POST   | email, password             | user object + token  | Authenticate user            |
| `/api/tasks/`      | GET    | user token                  | list of tasks        | Fetch all tasks for user     |
| `/api/tasks/`      | POST   | task details                | task object          | Create a new task            |
| `/api/tasks/:id`   | PUT    | updated task                | task object          | Update a task                |
| `/api/tasks/:id`   | DELETE | task id                     | success/fail         | Delete a task                |
| `/api/expenses/`   | GET    | user token                  | list of expenses     | Fetch all expenses for user  |
| `/api/expenses/`   | POST   | expense details             | expense object       | Create a new expense         |
| `/api/expenses/:id`| PUT    | updated expense             | expense object       | Update an expense            |
| `/api/expenses/:id`| DELETE | expense id                  | success/fail         | Delete an expense            |

---

