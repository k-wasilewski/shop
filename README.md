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
2b. mvn test
<br>
<br>

## User flow:
#### 1 - New order step 1
![alt text](https://raw.githubusercontent.com/k-wasilewski/shop/master/screenshots/new_order.png)
This is the first step of placing new order, with validation.

#### 2 - New order step 2
![alt text](https://raw.githubusercontent.com/k-wasilewski/shop/master/screenshots/new_order2.png)
This is the second step of placing new order, with items' availibility checking and visualization.

#### 3 - Confirmation and menu
![alt text](https://raw.githubusercontent.com/k-wasilewski/shop/master/screenshots/confirmation_menu.png)
This is the confirmation of successfully placed order, and a drop-down menu.


#### 4 - Summary
![alt text](https://raw.githubusercontent.com/k-wasilewski/shop/master/screenshots/summary.png)
This is the summary of placed orders, with drop-down lists of items.
