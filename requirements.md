In order to prepare better timesheets for your company, you've been asked to develop a terminal application for logging what work someone did on a certain day. The script should ask for a task name, how much time was spent on the task, and any general notes about the task. Record each of these items into a row of a CSV file along with a date.

Provide a way for a user to find all of the tasks that were done on a certain date or that match a search string (either as a regular expression or a plain text search). Print a report of this information to the screen, including the date, title of task, time spent, and general notes.

Make sure your script runs without errors. Catch exceptions and report errors to the user in a meaningful way.

As a user of the script, I should be prompted with a menu to choose whether to add a new entry or lookup previous entries.

As a user of the script, if I choose to enter a new work log, I should be able to provide a task name, a number of minutes spent working on it, and any additional notes I want to record.

As a user of the script, if I choose to find a previous entry, I should be presented with four options:

* find by date
* find by time spent
* find by exact search
* find by pattern

* When finding by date, I should be presented with a list of dates with entries and be able to choose one to see entries from.
* When finding by time spent, I should be allowed to enter the number of minutes a task took and be able to choose one to see entries from.
* When finding by an exact string, I should be allowed to enter a string and then be presented with entries containing that string in the task name or notes.
* When finding by a pattern, I should be allowed to enter a regular expression and then be presented with entries matching that pattern in their task name or notes.

When displaying the entries, the entries should be displayed in a readable format with the date, task name, time spent, and notes information.

