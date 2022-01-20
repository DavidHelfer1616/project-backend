<h1>Revature Social Network Platform</h1>

<h2>Project Description</h2>
<p>In this social network, everyone is friends with everyone. As a user, you will be able to register and login to your account. 
When you successfully login, you are automatically friends with everyone which means you will see a feed of everyone's posts.
Users will be able to create a post and like other people's posts. Users will also have the ability to view other profiles which will display posts of that specific user.
</p>

<h2>Technologies Used</h2>
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>Angular</li>
  <li>Java</li>
  <li>PostgreSQL</li>
  <li>AWS RDS</li>
  <li>AWS S3</li>
</ul>

<h2>Features</h2>
<p>List of features ready and TODOs for future development</p>
<ul>
  <li>Ability to make posts and view others posts on a central feed</li>
  <li>Image uploading</li>
  <li>Password Encryption</li>
</ul>

<p>To-Dos:</p>
<ul>
  <li>Like comments feature</li>
  <li>Comment on comments</li>
  <li>Add Exploding button animation</li>
</ul>

## Getting Started
clone into using: ```https://github.com/DavidHelfer1616/project2-backend.git```

To set up environment variables for windows:

1. Search "Edit the System Environment Variables"
2. Click "Environment Variables"
3. Under "System Variables", select "New"

Once you've done this you'll set them up to look like this:

Variable name = Variable value
```
AWS_SMTP_USERNAME = [username generated from AWS]

AWS_SMTP_PASSWORD = [password generated from AWS]

SPRING_DATABASE_URL = [your database location]

SPRING_DATABASE_USERNAME = [your database usernname]

SPRING_DATABASE_PASSWORD = [your database password]

SPRING_DATABASE_DRIVER = [your database driver]

SPRING_DATABASE_PLATFORM = [your database platform]

SPRING_DATABASE_DDL_METHOD = create
```

## Usage
A user can register with the website and after they will use thier credentials to login. After logging in the user will be directed to their main feed where
they will see other users posts. They can on make a post on the main or navigate to either their profile or another users profile by clicking on that users
handle, located just above their posts. When the user navigates their profile they have the option of making a post or editing their profile information, such as
their usernam, password, full name, email, and even their profile picture.

## Contributors
Brady Westveer
Jason Chan

## Links to front-end and testing application
Front-End: ```https://github.com/DavidHelfer1616/project2-frontend```

Testing-Application: ```https://github.com/DavidHelfer1616/project2-e2e```
