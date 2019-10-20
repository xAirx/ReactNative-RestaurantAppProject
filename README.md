# My Portfolio FullStack Project 
 
# Project created as part of the honors programme at the hong kong universty of science and technology.

 
 
### The project will combine all three courses:

          Front-End Web Development with React 
          Server-side Development with NodeJS, Express and MongoDB
          Multiplatform Mobile App Development with React Native                                                                                                                   

### Repo links: 
    
    
    
    
## Project report (subject to change):
    
    https://1drv.ms/w/s!Ai-HjhU8IJcIhZwN7QqKalO1yxmCpw?e=5cN1ao
 

 
   
## Stacklist: 
    
    React.js
    React router
    Redux
    ReactStrap
    
    React Native 
    Redux
    Native navigation
    ReactStrap
    
    
    Backend and API + Authentication.
    __________________________________
    Mongoose
    MongoDB
    Express ( REST API )
    
    
    
## Architecture (subject to change): 

    Expected List of Features & Architecture
    
 ### Introduction
                
     A website + native app “Boilerplate” 
     with a backend and Native app that serves as a platform for showing any content you would like could be petstore, a f   football club, anything you would like.

     User login and authentication
     Authentication based on being an admin or not.
     Admin based management, being able to see a user list, and the entire API.
     Comment and form support for the users to interact with the content.
     Support for a user to manage their own comments, delete functionality.
     API supporting various objects of which contains members of the “company” 
     A React Native app, supporting the same features working with the same backend and API.
     Immidiate Architechture (Subject to change)



 # Frontend 
                
  #### Notes: 
  
  https://onedrive.live.com/view.aspx?resid=897203C158E872F%2184124&id=documents&wd=target%28MERN%20stack%2FReact%29
onenote:https://d.docs.live.net/0897203c158e872f/Documents/marcos%20notesbog/MERN%20stack/React/

  
     Frontend built in React.js, supporting react router based on Redux.
     Introduced new action types and action creators to support the fetching of the information from the server and update the Redux store.
   
   
   
  #### Part 1 & 2 :
      
      Setting up the project &. Creating components needed
      
      Created a new DishdetailComponent and added it to your React application.

      Updated the view of the DishdetailComponent to display the details of the selected dish using an reactstrap card component.

      Updated the view of the DishdetailComponent to display the list of comments about the dish using the Bootstrap unstyled      list component.

      Integrated the AboutComponent given above into the single page application.

      Added a new functional component named <RenderLeader> through the RenderLeader() function to AboutComponent.js that    renders the details of a given leader using the reactstrap <Media> component.
      
      Construct and render the list of leaders in the About Us page using the <RenderLeader> component implemented above.
      
 #### Part 3:
      
      Configure The React application to make use of Redux
      
      Provide a form to enable users to submit their comments
      
      Validate the information entered by the users in the form

      Set up the form as a local form using the react-redux-form 
      
           import { DISHES } from '../shared/dishes';
           import { COMMENTS } from '../shared/comments';
           import { PROMOTIONS } from '../shared/promotions';
           import { LEADERS } from '../shared/leaders';

           export const initialState = {
               dishes: DISHES,
               comments: COMMENTS,
               promotions: PROMOTIONS,
               leaders: LEADERS
           };

           export const Reducer = (state = initialState, action) => {
               return state;
           };

      
 #### Part 4 : 
 
       Introduced new action types and action creators to support the fetching of the leaders information from the server and update the Redux store.

        Updated the Home and the About component to render the information about the leaders using the downloaded data from the server

        Add simple animations to the About component where the leaders information is displayed.

        Enabled the users to submit feedback through the feedback form by creating a new feedback service that accepts the form data and uses Restangular to record their feedback on the server.

 
     Appropriate action types and action creators have been added.
    The Home component is correctly using the leader data, and handling any errors that might arise.
    The About component is correctly using the leader data, and handling any errors that might arise.


    A new postFeedback() action creator is correctly implemented to post the feedback data to the server.
    The Contact component has been correctly updated to use postFeedback() to post the form data to the server.


    Appropriate animation has been added to stagger the rendering of the leaders in the AboutComponent.



# Backend: 

#### Notes: 

https://onedrive.live.com/view.aspx?resid=897203C158E872F%2184124&id=documents&wd=target%28MERN%20stack%2FSQL%2FExpress%20Router%29
onenote:https://d.docs.live.net/0897203c158e872f/Documents/marcos%20notesbog/MERN%20stack/SQL/Express%20Router/



   #### Express and Routing

   #####  Part 1 :

    * Created a Node module using Express router to support the routes for the dishes REST API.
    * Created a Node module using Express router to support the routes for the promotions REST API.
    * Created a Node module using Express router to support the routes for the leaders REST API.


    Objective 1

    * The REST API supports GET, PUT, POST and DELETE operations on /dishes/:dishId end point.

    Objective 2

    * The new Node module, promoRouter is implemented and used within your server to support the /promotions end point.
    * The REST API supports GET, PUT, POST and DELETE operations on /promotions and GET, PUT, POST and DELETE operations on /promotions/:promoId end points.


    Objective 3

    * The new Node module, leaderRouter is implemented and used within your server to support the /leaders end point.
    * The REST API supports GET, PUT, POST and DELETE operations on /leadership and GET, PUT, POST and DELETE operations on /leaders/:leaderId end points.



   ###### Part 2 : 

    Architecture and REST API and endpoints.

    Objectives:

    * Designing the overall architecture of your application, from the front-end to the back-end. You should have apportioned the responsibilities to the front-end and back-end.

    * Design an appropriate REST API that should be supported by your server-side. A good design would enable ease of implementation of both the front-end and the back-end and facilitate seamless communication.

    * Decide on the database schemas (if you are using Mongoose) and the structure of the data, depending upon the database technology that you choose to implement the persistence of server-side data

    * Design the business logic to be implemented on the server-side to support the needs of the front-end.


    * Implemented the Promotions schema and model

    * Implement a REST API to support the /promotions endpoint, and the /promotions/:promoId endpoint enabling the interaction with the MongoDB database

    * Implemented the Leaders schema and model

    * Implement a REST API to support the /leaders endpoint, and the /leaders/:leaderId endpoint enabling the interaction with the MongoDB database


    Task 1
    * The Promotions schema and model correctly supports all the fields as per the example document given above
    * The label field is set to an empty string by default
    * The price schema is be supported with a new SchemaType called Currency.
    * The REST API endpoints /promotions and /promotions/:promoId are implemented to interact with the MongoDB database

    Task 2
    * The Leaders schema and model correctly supports all the fields as per the example document given above.
    * The REST API endpoints /leaders and /leaders/:leaderId are implemented to interact with the MongoDB database




   ###### Part 3 :

    User Authentication

    * Check if a verified ordinary user also has Admin privileges.
    * Allow any one to perform GET operations
    * Allow only an Admin to perform POST, PUT and DELETE operations
    * Allow an Admin to be able to GET all the registered users' information from the database
    * Allow a registered user to submit comments (already completed), update a submitted comment and delete a submitted comment. The user should be restricted to perform such operations only on his/her own comments. No user or even the Admin can edit or delete the comments submitted by other users.


     update all the routes in the REST API to ensure that only the Admins can perform POST, PUT and DELETE operations. Update the code for all the    routers to support this. These operations should be supported for the following end points:


    * POST, PUT and DELETE operations on /dishes and /dishes/:dishId
    * DELETE operation on /dishes/:dishId/comments
    * POST, PUT and DELETE operations on /promotions and /promotions/:promoId
    * POST, PUT and DELETE operations on /leaders and /leaders/:leaderId




   ##### Part 4 : 

    Backend as a service


    * Allowed users to select a dish as their favorite, and add it to the list of favorites that are saved on the server.
    * Allowed users to retrieve the list of their favorite dishes from the server
    * Delete one or all of their favorite dishes from their favorites list on the server.


    * When the user does a GET operation on '/favorites', you will populate the user information and the dishes information before returning the favorites to the user.
    * When the user does a POST operation on '/favorites' by including [{"_id":"dish ObjectId"}, . . ., {"_id":"dish ObjectId"}] in the body of the message, you will (a) create a favorite document if such a document corresponding to this user does not already exist in the system, (b) add the dishes specified in the body of the message to the list of favorite dishes for the user, if the dishes do not already exists in the list of favorites.
    * When the user performs a DELETE operation on '/favorites', you will delete the list of favorites corresponding to the user, by deleting the favorite document corresponding to this user from the collection.
    * When the user performs a POST operation on '/favorites/:dishId', then you will add the specified dish to the list of the user's list of favorite dishes, if the dish is not already in the list of favorite dishes.
    * When the user performs a DELETE operation on '/favorites/:dishId', then you will remove the specified dish from the list of the user's list of favorite dishes.


    * A new favoriteSchema and Favorites model has been correctly implemented to take advantage of Mongoose Population support to track the users and the list of favorite dishes using their ObjectIds in the favoriteSchema and Favorites model.
    * The GET, POST and DELETE operations are well supported as per the specifications above
    * The app.js has been updated to support the new route.





