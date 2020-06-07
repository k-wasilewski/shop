## build&run&test the app
frontend - React.js<br>
backend - Spring Boot<br>

### build
1a. cd frontend<br>
1b. npm install<br>
<br>
2a. cd backend<br>
2b. mvn package<br>
<br>

### run on Docker
1a. cd frontend<br>
1b. docker build -t frontend .<br>
<br>
2a. cd backend<br>
2b. docker build -t backend .<br>
<br>
3a. cd semantive_fullstack<br>
3b. docker-compose up<br>
<br>
4. go to http://localhost:3000<br>
<br>

### run locally
1a. cd frontend<br>
1b. npm start<br>
<br>
2a. install mysql-server<br>
2b. change root password to 'root'<br>
2c. create database shop<br>
<br>
3a. cd backend<br>
3b. java -jar target/backend-0.0.1-SNAPSHOT.jar<br>
<br>
4. go to http://localhost:3000<br>
<br>

### test
1a. cd frontend<br>
1b. npm run test<br>
<br>
2a. cd backend<br>
2b. mvn test<br>
