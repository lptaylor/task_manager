Define CRUD.
  The ability to create, read, update and delete information within the app
from the view part of the MVC framework.

Why do we use set method_override: true?
  It is allowing us to use overrride and define any methods that are not
recognized.


Explain the difference between value and name in this line: <input type='text' name='task[title]' value="<%= @task.title %>"/>.
  The name is pulling the name that was input when the task was created, whereas
the value is using the erb template to say that the value should be equal to the instance variable @task where the method #title called on it.

What are params? Where do they come from?
  From the information given by the HTML doc.

Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?

  They are 
