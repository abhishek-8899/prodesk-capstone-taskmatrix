# TaskMatrix API

## Authentication

| Method | Endpoint | Purpose |
|---|---|---|
| POST | /api/auth/register | Register user |
| POST | /api/auth/login | Login user |
| GET | /api/auth/me | Get current user |
| POST | /api/auth/logout | Logout user |

## Projects

| Method | Endpoint | Purpose |
|---|---|---|
| GET | /api/projects | Get projects |
| POST | /api/projects | Create project |
| GET | /api/projects/:id | Get project |
| PATCH | /api/projects/:id | Update project |
| DELETE | /api/projects/:id | Delete/archive project |

## Project Members

| Method | Endpoint | Purpose |
|---|---|---|
| POST | /api/projects/:id/members | Add member |
| DELETE | /api/projects/:id/members/:userId | Remove member |
| PATCH | /api/projects/:id/members/:userId | Update member role |

## Tasks

| Method | Endpoint | Purpose |
|---|---|---|
| GET | /api/tasks | Get tasks |
| POST | /api/tasks | Create task |
| GET | /api/tasks/:id | Get task |
| PATCH | /api/tasks/:id | Update task |
| DELETE | /api/tasks/:id | Delete task |

## Comments

| Method | Endpoint | Purpose |
|---|---|---|
| GET | /api/tasks/:taskId/comments | Get comments |
| POST | /api/tasks/:taskId/comments | Add comment |
| PATCH | /api/comments/:id | Update comment |
| DELETE | /api/comments/:id | Delete comment |

## Activity

| Method | Endpoint | Purpose |
|---|---|---|
| GET | /api/projects/:projectId/activity | Get project activity |

## Dashboard

| Method | Endpoint | Purpose |
|---|---|---|
| GET | /api/dashboard | Get dashboard statistics |