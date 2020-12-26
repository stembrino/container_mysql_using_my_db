# MySql with Docker/docker-compose
<div style="display: flex;">
<img width="150" src="https://cdn.iconscout.com/icon/free/png-256/docker-2-458268.png">
<img width="150" src="https://cdn.iconscout.com/icon/free/png-256/mysql-6-226028.png">
<div>
<h3>Example how to use your files to create a database</h3>
<ul>
<li>Docker</li>
<li>Mysql</li>
<li>docker-compose</li>
</ul>
<p>
It's easy way to realize how to set up an enviroment and using your files (.sql) to create a connection with your applications
<p>
<p>
Fill the env variables in mysql.env and run:<b> docker-compose up</b>
</p>
<p>
To execute database commands (mysql) into your database container. Get the name of container, run: <b>docker ps</b>
</p>
<p>
Run the command to get navigate inside of the container: <b>docker exec -it <CONTAINER ID/NAME> bash </b>
</p>
<p>
Run the command: <b>mysql -u <UDER NAME> -p</b>
</p>
