<h1>Server for whatsapp Clone</h1>

<h3>Description</h3>

The web server includes the rating page of client side and the API that connect with the client.
The API includes the following commands (and more):

<ul>
  <li>Get all user contacts</li>
  <li>Add new contact to another user</li>
  <li>Delete contact</li>
  <li>Get messages of a chat</li>
  <li>Get the details of user in the system</li>
  <li>Update details about a user</li>
  <li>Invite to a new conversation</li>
  <li>Delete conversation</li>
  <li>Create new message</li>
  <li>Login and SignIn</li>
</ul>


<h3>Installtions</h3>

The installtions required for the project:
1. MARIA-DB for database.
2. set the connection string to your sql server in file ServerDbContext.cs in Repository project.
3. To link the DB to the Whats_App_ServerSide project, open the Package manager console and execute the add-migration init command and then update-database. 
4. Section 2 must also be performed for Whatsapp_Rating project.

 
Note - in order to run the program, the server located at localhost:7288 must be run simultaneously along with the react project that located at localhost:3000. 
Also, to run the rating page that found at localhost:7215 you must set the project as startup project and only then run it. 
Which means we have three separate windows for the three parts of the program.


<h3>Technologies</h3>
<ul>
  <li>C#</li>
  <li>MVC</li>
  <li>.NET</li>
  <li>MariaDB</li>
  <li>Swagger</li>
  <li>Entity Framework</li>
  <li>SignalR</li>
</ul>


Contributors names:
Tomer Hadar
<br/>
Noa Amit
