## yooda-hostel

[Live Website](https://yooda-hostel-7586a.web.app/)

[Heroku Repo for Server](https://evening-stream-09071.herokuapp.com/)

[Git Server Link](https://github.com/Rabbi01521/yooda-hostel-server-site)

[Git Client Link](https://github.com/Rabbi01521/yooda-hostel-client)

### Features:

- Admin can add food with price.Form will have - food name, cost price,
  after adding show it in a table (backend pagination mandatory) , He can edit and delete each item.
- Admin can add new student , Form will contain -
  full name, roll,age, class, hall name , status (“active”, “inActive”, )
- Student table will have a checkbox in every row, and the admin can
  change status ( “inActive”, “active”) by selecting multiple items from the table.(Bulk action by single button click).
- student table (backend pagination mandatory), edit and delete items.
- While serving food, create a distribution form where admin can
  search students by roll, select “shift” from drop down, “Date”. Add food item they want to take, Then change the status to “served”
- If a student has been already serve in that shift on date, show a
  message - “Already served”
- .env file to hide db user and password and also use .gitignore file

### Technology :

- node
- mongodb
- express
- nodemon
- dotenv
- React
- react-router-dom
- material ui
