# Full Stack Todo List App

Full Stack Todo List App built with Next.js 14 (Server actions) and Neon Serverless PostgreSQL.
Its a very basic todo list app to get started with **Next.js** Server actions.

## Technologies Used

- Next js 14 (Server actions)
- Typescript
- Tailwind CSS
- Shadcn-Ui
- Prisma
- Zod
- Neon (Serverless Postgresql)

## Key Features

- Create Todos
- Mark todo completed
- Delete Todo
- Different sections for pending and completed tasks.

### Visit

<https://next-server-actions-todo-app-jade.vercel.app/>

## Topics Covered

This repository gives a start to the **Next.js Server Actions**. It also Covers **Prisma Schemas** , **React-Hook-Form** and **Zod** form validation.

Frontend: I used Next.js for the user interface to create a fast and efficient SPA (Single Page Application) with a dynamic experience. The app has a responsive design to handle different screen sizes, offering an optimal viewing experience. I used ShadCN for UI components such as buttons and forms, which provide a clean, accessible design. The user can view tasks in different states (pending or completed), add new tasks, update existing ones, and delete tasks as needed. The task statuses are toggled between 'Pending' and 'Completed' by clicking the corresponding labels, moving tasks between sections.

Backend: I implemented a RESTful API using Node.js. The backend handles requests for adding, updating, and deleting tasks in the PostgreSQL database. Prisma was used as the ORM to easily define models and manage database schema. I created a "Tasks" table with columns: id, task, status, and created_at.

Database: The database is managed using PostgreSQL. I designed the "Tasks" table with the necessary fields to store task information and status. I also implemented Supabase as an optional bonus, integrating it with Prisma to streamline real-time updates and authentication.

Deployment: The app is deployed on Vercel to ensure easy access and scalability. Continuous deployment is enabled, pushing updates directly from GitHub.
