# e-commerce

This application utilizes Express.js and mysql connecting to the database using sequelize. The user must first use dotenv to login to their mysql user. Then a npm run seed will seed all the models using the db with the attributes that each model consists of . Each model has a seperate route file that each contain routes for actions to get one by the model id, get all the objects in the model distinction, add an object to the models database given the proper route, delete an object based on id, or update an objects id based on its current id. Insomnia is used to test all of the routes by entering in the required input for the desired output, either with just id on the local server port or with JSON input as well. 

An accidental reinitilize of the repository lost all of my commits, and force pushing erased any history of it. 

I have attached a video link with a demostration of how each of the route actions GET, PUT, POST, and DELETE the given model objects from seeding from the db.

https://watch.screencastify.com/v/Qq000I7NAeNacqfGxd87


![2022-08-22](https://user-images.githubusercontent.com/100645317/186031717-504e6d27-ba6b-44f4-8c96-18f5a2719f82.png)
