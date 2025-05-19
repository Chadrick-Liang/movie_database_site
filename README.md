# Enviro DVD Rental Management System  
Full-stack web app for browsing, renting, and administrating DVD collections.

Enviro provides a clean, secure interface for both customers and admins:
- 🔒 **JWT-based authentication** (login/logout, role-based access)  
- ⚙️ **Node.js & Express** RESTful API  
- 🐬 **MySQL** relational database backend  
- 🎨 **HTML5/CSS3 + Vanilla JavaScript** front-end  
- 🔄 Customer/Actor/DVD CRUD operations via AJAX

Ready to deploy locally or host on any Node-capable server.

# Login page
![Screenshot of web app login front page](/images/login.png)

# Movie search page
![Screenshot movie search interface](/images/movie_search.png)

#Instructions
1. Open MySQL Workbench, log in to the local instance and from the top left corner, File > Run sql script > navigate to 'bed_dvd_db.sql' within the recently unzipped folder > open.
2. Open visual studio code and open the folder 'frontend'.
3. From the top left, File > New window > open the folder 'backend'.
4. In both, navigate to Terminal > New Terminal.
5. In the backend folder window, navigate to 'Model' > 'databaseConfig.js' and change the createConnection parameters to the user and password of your running, local mysql instance as well as the database to bed_dvd_db.
6. In both terminals, run the command 'node server.js'.
7. Visit the link 'http://localhost:3001/login.html' in a web browser to login to the website.
8. To login as an ordinary user, the username is 'test' and the password is 'test'.
9. To login as an admin, the username is 'testAdmin' and the password is 'test'.
