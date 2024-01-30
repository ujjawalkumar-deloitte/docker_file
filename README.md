Adjust the values for POSTGRES_DB, POSTGRES_USER, POSTGRES_PASSWORD, PGADMIN_DEFAULT_EMAIL, and PGADMIN_DEFAULT_PASSWORD according to your preferences.

Run Docker Compose:
Open a terminal in your project directory and run the following command to start the containers:

**docker-compose up -d**

**Access pgAdmin:**
Open your web browser and go to http://localhost:8080. Log in using the email and password specified in the docker-compose.yml file. Once logged in, you can add a new server and connect it to the PostgreSQL container.

Server: postgres
Username: myuser (or the one you specified)
Password: mypassword (or the one you specified)
Host: postgres
Port: 5432
Save the connection, and you should be able to manage your PostgreSQL server using pgAdmin.
