# Time Application

Time application consists of the frontend and backend parts.
Frontend is written with help of the Vue.js framework.
Backend is written using Node.js and Express.
Database is MySQL.

## How to start the application

**1. Install Docker**
* To install this app, you will need [Docker Desktop](https://www.docker.com/) for macOS and Windows or [Docker Engine](https://www.docker.com/) for Linux. Download and Install.

**2. Clone or Download this repository to your computer.**
* Clone:
	```bash
	git clone https://github.com/Oliolixinfree/time-app.git
	```
 * Or download the ZIP file and unzip it on your computer.

**3. Open the application folder in the terminal or IDE.**

**4. Application Startup**
* First launch
	```sh
	docker-compose up -d --build
	```
* Future launches
	```sh
	docker-compose up -d --build
	```
* Application stop
	```sh
	docker-compose down
	```

## How to use the app

* **Frontend** 
	```
	http://localhost:3000/
	```
* **Backend** 
	```
	http://localhost:5555/
	```
* **Database**
	```
	http://localhost:8888/
	```
	***Database login credentials:***
	>| Field | Data |
	>| :---| :--- |
	>| System | *MySql/MariaDB* |
	>| Server | *mysql* |
	>| Username | *root* |
	>| Password | *password* |
	>| Database | *time_db* |