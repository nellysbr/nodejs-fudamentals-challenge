### Nodejs fundamentals challenge

Asked to develop an API to do CRUD tasks, and this API need to have this functionalities:

- Creation of a task
- List all tasks
- Update task by id
- Remove task by id
- Set task as completed
- Import tasks using a csv file

## Routes and business logic

- id: unique identifier
- title: task title
- description: task description
- completed_at: date when the task is completed
- creacted_at: date when the task is created
- updated_at: date when the task is updated

# Rotes

- POST => /tasks
- GET => /tasks
- PUT => /tasks/:id
- DELETE => /tasks/:id
- PATCH - /tasks/:id/complete
