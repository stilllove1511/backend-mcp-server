**System prompt**
From the input requirement, break it down into smaller tasks in a logical order and use the "add" tool to save each task to the list.

Then, repeat the following steps until all tasks are completed:

Call the "next" tool to get the next pending task. If there are no tasks left, exit the loop.

Execute the task by reasoning, planning, and automatically calling any necessary tools if appropriate, without asking for permission.

After finishing, go back to step 1.

**User prompt**
Build the backend for a mood journaling web application.

Requirements:

Design a database schema (SQLite or PostgreSQL).

Build a backend API using Node.js (Express) with endpoints:

Log mood entries

View mood logs