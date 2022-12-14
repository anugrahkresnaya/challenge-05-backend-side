# Challenge-05 Backend-Side

## Entity Relationship diagram
![dbdiagram](https://user-images.githubusercontent.com/55924803/194536867-e7e94a35-1b24-479f-bc9d-9a3dda775e81.png)

## Link
http://localhost:8002/

Link to Frontend: http://localhost:8000/

Frontend Repository: https://github.com/anugrahkresnaya/challenge-05

## Endpoint for Frontend
- Get all cars: /
- Get car by id: /cars/:id
- Create car: /cars
- Delete Car: /cars/:id
- Update car: /cars/:id

## The Example of Request Body
create car

![image](https://user-images.githubusercontent.com/55924803/194550933-d46cde56-f54e-4993-ae74-ebdd7bad9578.png)

## The example of Response Body
list car

![image](https://user-images.githubusercontent.com/55924803/194551022-ded5183d-2358-4c56-8c2d-4b45ae91d421.png)

## packages
- cloudinary
- express
- multer
- nodemon
- pg
- sequelize

## Step to run
- clone the repositories
  ```
  git clone https://github.com/anugrahkresnaya/challenge-05.git
  ```
- install the dependencies
  ```
  npm install or yarn install
  ```
- set config for database
  ```
  setting config.json
  sequelize db:create
  sequelize db:migrate
  ```
- run the server
  ```
  npm start or yarn start
