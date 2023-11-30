# CS 234 Website
### Preview 
&emsp; This is a website I created for my Database and Web Development class's final project. It is a database-driven website where all interior web pages update when changes occur in the database. PHP and HTML are the only two languages used for this website. All of the styling is done using w3 School CSS classes. 
The zip file containing this website is linked to this project. It includes all of the PHP files used along with an SQL file for the database. You can import my SQL database to your own if you would like to test out the website. All of the HTML and CSS code is wrapped in with the PHP code.

### Key Features
* User passwords are stored as hashes for security
* Database can be updated for the website
* Website adjusts automatically with database changes
* Only users can access the interior of the website

### Website Content
&emsp; Upon first entering the website, you will have the chance to log in if you are an existing user or register if you do not have an account. The login page is the first page you will encounter and it checks to see if your login information is inside of the database when you attempt to login.

![Login Page](https://github.com/bendery13/CS234_Website/assets/152329584/505610e8-aca0-4e53-b54a-2d13ea381c91)

&emsp; If you want to create a new account, you can access the register page from the login page. When you submit this page, it will first check to see if the username entered already exists. If it does, then it informs the user, and they must enter a new username. If the username is available, then the site checks the password to make sure it meets the minimum requirements.

![Register](https://github.com/bendery13/CS234_Website/assets/152329584/280fc9e9-c89f-44fe-9193-d38156111d6c)

&emsp; After successfully logging into the website, the user will have access to three pages. The first is the home page which will give them an overview of the contents of the website. The home page welcomes the user personally with their username.

![Home](https://github.com/bendery13/CS234_Website/assets/152329584/a2408583-4a93-41cb-9a63-4f388161a479)

&emsp; On the Musical Artist page, the user will be able to see the list of musical artists in the database. They will be able to use this page as a reference page for the search function on the next page.

![Musical Artists](https://github.com/bendery13/CS234_Website/assets/152329584/448435fe-da77-4e3c-a25a-397e4be35250)

&emsp; The Artist Search page allows the user to search for albums of different artists using their singer ID. When the user first enters the page, the table will show only the headers of each column. Once a singer ID is searched, the results will stay on the screen until it is exited, or a new entry is submitted.

![Artist Search](https://github.com/bendery13/CS234_Website/assets/152329584/74a23ec4-111b-4681-a877-ed61b8a458e9)

&emsp; The last main page on the website is the administrator page. This page is only accessible to administrators and any attempt by a regular user to access the page will be denied. The user, if logged in, is told that they do not have access to the page. No GUI interface exists for them to access it, so they can only attempt to access it by typing in the URL. The following screen will show if they attempt to access the page.   
![User Admin Page](https://github.com/bendery13/CS234_Website/assets/152329584/056059ec-618f-4d36-baca-170df74666a1)

&emsp; On the administrator page, the admin will have access to most of the nonsensitive information in the database. They can view the registration table and the artist table from the database. The passwords for the users are hashed out both in the database and from the administrator for security. From this screen, the admin will be able to perform all of the CRUD functions for the two tables using the GUI interface provided. For each button on the screen, they will provided with a form where they can perform all the necessary functions for the database through a web form. Once they complete a change in the data, their admin page and the whole website will update with it.

![Admin Screen.](https://github.com/bendery13/CS234_Website/assets/152329584/64e26e35-8445-47fa-ab75-8ef51616d92e)

&emsp; When the user is done using the website, they should log out. Upon logging out they are presented with a personalized goodbye message with their username. The PHP Session ends, and they will not be able to access the interior pages of the website until they log back in.

![Log Out](https://github.com/bendery13/CS234_Website/assets/152329584/93a408f6-67bf-481a-912e-0380abc508f0)

Here are the three tables that run the database.
#### Registration
![Registration](https://github.com/bendery13/CS234_Website/assets/152329584/b767a46c-70de-43e2-8ad5-67093f884abd)

#### Artists
![Artists](https://github.com/bendery13/CS234_Website/assets/152329584/51a00aef-3a99-43c0-9950-35f3a6f10669)

#### Albums
![Albums](https://github.com/bendery13/CS234_Website/assets/152329584/8591d57d-ba6d-4ba7-8d48-54f7e98a0dbd)



