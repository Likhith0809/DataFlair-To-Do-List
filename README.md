# DataFlair-To-Do-List

The To-Do List Application is a Java project that allows users to manage tasks, assign due dates, and organize them into projects. Here are the key features of this application:

1.Task Management:
  * Users can create new tasks, each with a title and a due date.
  * Tasks can be assigned to specific projects.
  * Existing tasks can be edited, marked as done, or removed.
    
2.Text-Based User Interface:
  * The application provides a command-line interface (CLI) for user interaction.
  * Users can perform various actions using text commands.
    
3.Persistence:
  * The application allows users to save their task list to a file.
  * Upon restarting the application, the previous state is restored from the saved file.

    
**How It Works**

  1.Creating Tasks:
    Users can add tasks by specifying a title, due date, and project.
    For example, you might create a task like “Finish project proposal by Friday” and assign it to the “Work” project.

  2.Editing Tasks:
    * The application supports task editing. If you need to modify a task’s details, you can do so using its unique ID.
    * For instance, if you mistyped the due date, you can correct it without recreating the entire task.
  
  3.Marking Tasks as Done:
    * When a task is completed, you can mark it as done.
    * This feature helps you keep track of your progress.
 
  4.Removing Tasks:
    * If a task is no longer relevant, you can remove it from the list.
    * For example, if you finished a task ahead of schedule, you can delete it.
 
  5.Sorting Tasks:
    * The application allows sorting tasks by both date and project.
    * You can quickly find tasks that need attention.
  
  6.Saving and Loading:
    * Users can save their task list to a file (presumably in a structured format).
    * When reopening the application, the saved tasks are loaded back into the list.
