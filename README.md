# My React Native "FullStack" Project 

- Backend :  https://github.com/xAirx/Backend-for-React-Native-project
         

&nbsp;
&nbsp;
&nbsp;
&nbsp;




## Imagery

### App - A work in progress

![](https://media.giphy.com/media/XbyRPGlLGjzwd48wly/giphy.gif)
![](https://media.giphy.com/media/WpHzcqwVw77m2NYoPq/giphy.gif)
![](https://media.giphy.com/media/XfbhnNHt2MzIlUTHWr/giphy.gif)
![](https://media.giphy.com/media/f3qB4hqzum66Q6kQWi/giphy.gif)
![](https://media.giphy.com/media/Pkj7flg6CVX5ce8DFe/giphy.gif)
![](https://media.giphy.com/media/lmqAV0ZTpJ1ORgwxMU/giphy.gif)
![](https://media.giphy.com/media/SvFVHDHMnRG1tz2oba/giphy.gif)
![](https://media.giphy.com/media/JrwyIDPuRZY7f3lSXu/giphy.gif)
![](https://media.giphy.com/media/Rihl7EsnvgbntDO0Oh/giphy.gif)

&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;


# Project overview


   ## App made in React Native 

    __________________________________
    
     A React Native app, supporting the same features working with the same backend and API.
     
     The Native app is a mini version of the above React Frontend.
     
     The Native app will also be using the API and Backend created.
     
     The app also includes table reservation, with integration with the users calendar.

&nbsp;
&nbsp;
&nbsp;
&nbsp;

   ### Goals: 

     Summarize the salient features of hybrid mobile application development frameworks
     Create a React Native application
     Develop a React Native application using various React Native components and Layouts
     Build navigation within your application using React Native Navigation support
     
     Design the UI for the app using various React Native UI elements
     Express the Redux approach to implementing a variant of the Flow architecture in React Native
     Design forms within the application for data entry
     Employ alerts and Modals to present information to the user
     
     Build storage support within the application for persisting Redux state
     Employ animations to provide enhanced user experience
     Employ gesture-based interaction within the app
     Develop a way of alerting users
     
     Develop applications to use the native capabilities of the devices
     Employ the Expo SDK to access native device capabilities
     Develop applications that use sharing features of mobile devices
     Develop applications that can do user notifications


&nbsp;
&nbsp;
&nbsp;
&nbsp;   

   #### Features: (subject to change): 
  

         React native Navigation & Components.  -done
     
         Integrated font awesome "fonts and buttons" -done
        
         Form handling &  Redux integration for form handling  -done
         
         Redux integration to create a "Loading Component" using the activity indicator component -done
         
         Trigger showing of message when data is fetched from server. -done
     
         Redux integration to "Star products" and rate them -done
    
         Redux integration to handle the customers favorite products -done
         
         Secure storage - handling user login etc. -done
         
         Local notifications - Notification handling for reserving tables and based on calendar dates and integration with phone calendar -done
         
        Social Sharing - Sharing of information to social media sites using the React Native Share API -done
        
        Email Integration for contact page. -done
        
        Interaction with users camera to obtain images for the user profile  -done
        
        NetInfo() and Network info, to check if device is offline or not. -done
          connectiontype, effectiveconnectiontype -done
          connectchange even fires when netwwork status changes etc. -done
          
        Swipe Option Buttons and Alerts -done
          
        Animations -done
          
        Gestures -done
          
        Persist Redux Store -done


&nbsp;
&nbsp;
&nbsp;
&nbsp;       

&nbsp;
&nbsp;



# Features Development Log (subject to change): 

Expected List of Features & Architecture

&nbsp;
&nbsp;
&nbsp;
&nbsp;

	 ---------Login functionality, with registration, JWT, communicating with the backend express API ----------
       
        Oauth, facebook login etc. 
	-  Not started on backend
	-> Frontend started ****  Work in progress
    
        Users can register and login 
	- integrated on backend 
	-> Frontend started ****  Work in progress
     
   
        --------User panel Setup ----------
        
        Via Userpanel able to update profilepicture, description etc.  
        - integrated on backend. 
	-> Frontend started ****  Work in progress
        
        Via Userpanel able to update a submitted comment and delete a submitted comment.
        - integrated on backend. 
	-> Frontend started ****  Work in progress
        
        
	
	 ------------ Admin Panel setup -----------

       Admin Panel Frontend structure - done

       
        Admin can  GET all the registered users' information from the database and see it in the adminpanel
        - integrated on backend. 
	-> Frontend started ****  Work in progress
    
        Admin allowed / able to upload files, such as images when creating new dishes. and see it in the adminpanel
        - integrated on backend. 
	-> Frontend started ****  Work in progress
    
        Admin allowed see and flag dishes as featured or not. and see it in the adminpanel
        - integrated on backend. 
	-> Frontend started ****  Work in progress
    
        Admin can see and flag leaders as featured for the frontpage and see it in the adminpanel
        - integrated on backend. 
	-> Frontend started ****  Work in progress
	      
             
	    

&nbsp;
&nbsp;   
&nbsp;
&nbsp;
&nbsp;
&nbsp;

# Devlog

## React Native 

&nbsp;
&nbsp;
&nbsp;
&nbsp;


#### Part 1 : Navigators and Components. - done

      The Contact Us page is showing the address of the restaurant in the card format as shown above. - done

       The history information about the restaurant is displayed in a card format as shown above using a functional component named History(). - done

       The corporate leadership information is shown in the About Us page in the format as shown above. The leader information is renedered inside a Card. - done

       The AboutComponent is a included using the Stack Navigator and in the Drawer Navigator. - done

       The ContactComponent is a included using the Stack Navigator and in the Drawer Navigator. - done

 


#### Part 2 : UI elements and Redux - done

       Add an Action named ADD_COMMENT to the ActionTypes.js. - done

       Add two action creators named postComment() and addComment(). The postComment() creator will receive the dishId, rating, author and comment as the four parameters. - done

      Update the comments reducer function to handle the new ADD_COMMENT action and add the comment to the list of comments. The handling of the action should also ensure that appropriate ID will be added to the comment.- done


     The modal containing the form is correctly added to the Dishdetail component- done

     The form is correctly configured with the rating, author and comment fields.- done

     An Icon is added to the RenderDish Card that will trigger the showing of the modal.- done

      The ADD_COMMENT action is correctly added- done

      The postComment() action creator is correctly added- done

      The addComment() action creator is correctly added and will be dispatched by postComment() after a 2 sec delay- done

      The comment reducer is updated to handle the ADD_COMMENT action- done

      EXTRA: __________________________________________________________________

      The favorites redux integration now includes a toggle functionality.- done

       The POST_COMMENT now also allows us to correctly call the LOADING_COMMENTS and show the data dynamically on add.- done




#### Part 3: Animations, gestures and redux persist. - done


     The reservation form zooms in when the user navigates to the reservation view - done 


      An alert containing the information from the reservation form is shown when the user submits the filled reservation form. - done 
          If the user clicks on Cancel, then the form is cleared. - done 
          If the user clicks on OK, then the form is cleared. - done 


     When the user does a left to right gesture on the Dish details card in the Dishdetail component, toggle the comment form modal. - done
     

#### Part 4:  Calendar event API, Image Picker API Reservation Functionality with users calendar.- done

        In this task will make use of the Expo SDK ImagePicker API to enable application to fetch an image from the photo library.

          Update LoginComponent.js to set up a function named getImageFromGallery() that fetches the image from the photo library on the device using the ImagePicker API support.


         Details of setting up the source to be the Photo Library can be found in the API documentation.- done

         Add a new button named Gallery that when clicked will initiate the process to enable the user to select a picture from the photo library using the ImagePicker API.- done

          Once the image is picked, it must be processed through the ImageManipulator to obtain a resized PNG version of the image as we did in the exercise.- done

        In this task I will insert a new Calendar event into the default calendar on the mobile device for the table reservation.  will use the Calendar API from Expo SDK for this.  will implement this in the ReservationComponent.js file.

        When the user submits the reservation form,  will obtain the details of the reservation in the handleReservation() function.- done

          Implement a new function named obtainCalendarPermission() that will ask for permission to access the calendar on the device. The corresponding permission is Permission.CALENDAR.

         Implement another function named addReservationToCalendar() that receives the date information as a parameter. This function is invoked from the handleReservation() function.- done

         should use the createEventAsync() function from the Calendar API to insert the event into the default calendar (Calendar.DEFAULT). This function takes a title, the start and end time, timezone and location as the parameters.

        Use 'Con Fusion Table Reservation' as the title of the inserted event- done

        To specify the start Date and end Date,  can convert the Date ISO string into a Date object by using new Date(Date.parse(date)). Furthermore, the Date.parse() gives  the date value in milliseconds.  can set up the end time by adding 2 hours (2*60*60*1000) to the milliseconds and use it to generate the Date object corresponding to the end time of the event.- done

         For time zone use 'Asia/Hong_Kong', and the location as '121, Clear Water Bay Road, Clear Water Bay, Kowloon, Hong Kong' - done

         The LoginComponent.js is updated to implement the getImageFromGallery() function that uses the ImagePicker API to enable the fetching of the image from the photo library. - done

        The LoginComponent.js file is updated to include a button named Gallery that will initiate the procedure to enable the user to select a picture from the photo gallery. - done

         The image selected by the user is processed using the ImageManipulator to generate a PNG image - done

        The ReservationComponent.js file is modified to implement the obtainCalendarPermission() function that obtains permission to access the calendar - done

         The ReservationComponent.js file is modified to implement the addReservationToCalendar() function that inserts the event into the default calendar using the Calendar API.- done

        The details of the event are correctly inserted setting the title, start and end time and the location correctly. - done





&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;   

&nbsp;
&nbsp;
&nbsp;
&nbsp;   

&nbsp;
&nbsp;
&nbsp;
&nbsp;   

&nbsp;
&nbsp;
&nbsp;
&nbsp;   

&nbsp;
&nbsp;
&nbsp;
&nbsp;   
&nbsp;
&nbsp;
&nbsp;
&nbsp;   

&nbsp;
&nbsp;
&nbsp;
&nbsp;   
  ### Website made in React.js

&nbsp;
&nbsp;
&nbsp;
&nbsp;

  #### Goals: 

      Express the general characteristics of JavaScript frameworks and libraries
      Create a new project using React
      Create React components within a React application
      Express what is meant by full-stack web development
    
      Develop a React router based navigation to various views in a React application
      Develop a single page application using the React router support
      Give examples of various types of React components
    
      Create uncontrolled React forms
      Create controlled forms and perform form validation
      Discuss the features of the Flux architecture
      Explain the Redux approach to implementing a variant of the Flow architecture
    
      Create Redux Actions
      Develop Redux actions using Redux Thunk
      Develop client-server communication using Fetch
      Develop Fetch-based communication with a REST API server


&nbsp;
&nbsp;
&nbsp;
&nbsp;

   #### Features:


         Form handling &  Redux integration for form handling 
         
         *********** Redux integration to create a "Loading Component" using the activity indicator component
         Trigger showing of message when data is fetched from server.
    
         ***********Redux integration to "Star products" and rate them
    
         ***********Redux integration to handle the customers favorite products
         
         Redux Thunk middleware 
         
         React Animations for animations
         
         Redux For Client server communication with fetch.
         
         Feedback through the feedback form by creating a new feedback service that accepts the form data.

&nbsp;
&nbsp;
&nbsp;
&nbsp;


 ## React website (Frontend)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

&nbsp;
&nbsp;
&nbsp;
&nbsp;

### Website  - A work in progress

The task was to build a site entirely with react-strap.
With react,redux,routing and more.

![](https://media.giphy.com/media/d5xPDBmDGvhuWiO6nY/giphy.gif)

![](https://media.giphy.com/media/iehQ45MNpKN56Z4At1/giphy.gif)

![](https://media.giphy.com/media/Jq87f8wLGyDp4GREvn/giphy.gif)

![](https://media.giphy.com/media/jUnnEOWLHlkjdjI2EP/giphy.gif)

![](https://media.giphy.com/media/cLY3Lw11yJH16zMscd/giphy.gif)

![](https://media.giphy.com/media/j3JZrptEGxdvaD7dTv/giphy.gif)


&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

#### Notes: 



onenote: https://d.docs.live.net/0897203c158e872f/Documents/marcos%20notesbog/MERN%20stack/
                

     Frontend built in React.js, supporting react router based on Redux.
     Introduced new action types and action creators to support the fetching of the information from the server and update the Redux store.

  


  #### Part 1 & 2 :

       Setting up the project &. Creating components needed - done

       Created a new DishdetailComponent and added it to React application. - done

       Updated the view of the DishdetailComponent to display the details of the selected dish using an reactstrap card component. - done

       Updated the view of the DishdetailComponent to display the list of comments about the dish using the Bootstrap unstyled list component. - done

       Integrated the AboutComponent given above into the single page application. - done

       Added a new functional component named <RenderLeader> through the RenderLeader() function to AboutComponent.js that    renders the details of a given leader using the reactstrap <Media> component. - done

      Construct and render the list of leaders in the About Us page using the <RenderLeader

      component implemented above. - done 
      
      

#### Part 3:

       Configure The React application to make use of Redux   - done

       Provide a form to enable users to submit their comments   - done

       Validate the information entered by the users in the form   - done

       Set up the form as a local form using the react-redux-form    - done



 #### Part 4 : 

       Introduced new action types and action creators to support the fetching of the leaders information from the server and update the Redux store. - done

       Updated the Home and the About component to render the information about the leaders using the downloaded data from the server - done

       Add simple animations to the About component where the leaders information is displayed. - done

       Enabled the users to submit feedback through the feedback form by creating a new feedback service that accepts the form data and uses Restangular to record their feedback on the server. - done

     Appropriate action types and action creators have been added. - done

      The Home component is correctly using the leader data, and handling any errors that might arise. - done

      The About component is correctly using the leader data, and handling any errors that might arise. - done

      A new postFeedback() action creator is correctly implemented to post the feedback data to the server. - done

      The Contact component has been correctly updated to use postFeedback() to post the form data to the server. - done

      Appropriate animation has been added to stagger the rendering of the leaders in the AboutComponent. - done




