# My React Native Project 





- Backend :  https://github.com/xAirx/Backend-for-React-Native-project
  #### Hosted API: https://expressproject.herokuapp.com/
  ###### you can register a user or use: username: marcouser password: password for testing purposes - Remember you are not admin
 					 try /dishes /favorites /leaders
					 
					 example:  https://expressproject.herokuapp.com/dishes/5ebaa5d3f22b400c864b949c
  
  

&nbsp;
&nbsp;
&nbsp;
&nbsp;  
&nbsp;
&nbsp;
&nbsp;
&nbsp; 
  
  
  
- Frontend app Code:      https://github.com/xAirx/ReactNativeRestaurantApp
         



&nbsp;
&nbsp;
&nbsp;
&nbsp;
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



# Current Development Log (subject to change) : 

Expected List of Features & Architecture

&nbsp;
&nbsp;
&nbsp;
&nbsp;

# React Native FullStack App


________________________________________



# Todo 
	
	- Connect to heroku API. BaseURL - done 
	- Redux pulls data correctly - done
	 
         - Learn how to seed a leader
	 - Learn how to add a promos
	 
	 - Image handling (Multer /// Filestorage)
	 
	 Connecting JWT register + login functionality to frontend
	 
	 - Create Refresh Token Functionality - and API endpoint for this purpose.
	 - Implementing httpcookie to hold the JWT serverside so we can compare for a refresh token.
	 - Connecting backend to frontend - recieve token in browser as cookie 
	 -
	 -
	 -
	 -
	


________________________________________

&nbsp;
&nbsp;
&nbsp;
&nbsp;

# Backend

________________________________________

## #0--------------Fileuploading with multer---------------------------- Under development
          
	  Correctly setting up the uploadRouter
	  
	  Understanding the concept of heroku file system and using bash to connect
	  
	  Understand why we need proper storage - adding cloudinary.
	  
	  Understand how to upload a file correctly.
	 
	  
	  
	  
	  
	 
## #1 Connecting JWT register + login functionality to frontend  - not started
	 
	 - Create Refresh Token Functionality - and API endpoint for this purpose.
	 - Implementing httpcookie to hold the JWT serverside so we can compare for a refresh token.
	 - Connecting backend to frontend - recieve token in browser as cookie 
	 
	 
### #2 Oauth implementation

&nbsp;
&nbsp;



&nbsp;
## Users Panel:

________________________________________

	  
### #1 TODO ------> Favorite functionality for users**
&nbsp;
&nbsp;   
&nbsp;

  
 -implemented - NOT TESTED

	  

### #2 TODO ------> Comment CRUD support for the users to interact with the content.**
&nbsp;
&nbsp;   
&nbsp;


#### NOT IMPLEMENTED MIRROR LEADERS ROUTE CODE

 	LeaderRouter.route('/:leaderId/feedback')
 
 	TODO ------  Support for a user to manage their own comments, delete functionality. -implemented - NOT TESTED

#### Backend **** Work in progress

#### Frontend started **** Work in progress

&nbsp;
&nbsp;   
&nbsp;

  

### #3 Via Userpanel able to update profilepicture, description etc.**  
	Mirror functionality from registraiton page 
	  getImageFromCamera = async () => {
	    console.log('GETIMAGEFORMCAMERATRIGGRED');
&nbsp;
&nbsp;   
&nbsp;

#### Backend **** Work in progress

#### Frontend started **** Work in progress



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
# Frontend

________________________________________

&nbsp;
&nbsp;
&nbsp;

## Login functionality, registration

________________________________________
  

### 1# Passport - Users can register and login 



#### Backend - done



#### (DESIGN) Frontend work in progress 

&nbsp;
&nbsp;   
&nbsp;


### #2 Registration image upload 

	Moving functionality from state based to work with multer and store images serverside under user ID.

	### Adding auth0 button etc.


#### Backend - Work in progress

#### Frontend work in progress.



&nbsp;
&nbsp;
&nbsp;
&nbsp;

## User panel Setup

________________________________________   

&nbsp;
&nbsp;   
&nbsp;

### 1# Via Userpanel be able to see your favorites and delete and see new ones added

	The idea : Remove current favorites menu point and only show inside user panel.
	
	Migrate favorites functionality from using localstorage to using the express api and storing information under the 	   user login


#### Backend *** needs testing 

#### Frontend *** Work in progress. 

&nbsp;
&nbsp;   
&nbsp;



### 2# Via Userpanel able to update a submitted comment and delete a submitted comment


#### Backend **** Work in progress

#### Frontend started **** Work in progress



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

## Admin Panel setup

________________________________________



### 1# Admin Panel Frontend structure

  

#### Admin GET all the registered users' information from the database and see it in the adminpanel


##### Backend done **** Work in progress
##### Frontend started **** Work in progress

&nbsp;
&nbsp;   
&nbsp;


### 2# Admin allowed / able to upload files, (MULTER and FS) such as images when creating new dishes. and see it in the adminpanel


#### Backend **** Work in progress


#### Frontend started **** Work in progress

&nbsp;
&nbsp;   
&nbsp;

### 3#  Admin allowed see and flag dishes as featured or not. and see it in the adminpanel**



#### Backend - done

#### Frontend started **** Work in progress

&nbsp;
&nbsp;   
&nbsp;

### 4#  Admin can see and flag leaders as featured for the frontpage and see it in the adminpanel**



#### Backend - done

#### Frontend started **** Work in progressReact Native FullStack App

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


 ## Component Testing is backed up by Storybook.js
   
   	Small explanation: 
	
	https://blog.logrocket.com/react-storybook/
	
	
   
                    Storybook.js is a tool that helps writing components in isolation, and showcase them interactively in an isolated dev environment. 

	            The idea is to isolate show its behavior in a series of tests. This way we can make sure it works.
			
		    Storybook offers different techniques for testing UI components. Components need to undergo tests for a variety of reasons some of which are:

		    Detection of bugs
		    Tests can be documented to serve as guidelines for other developers who will work on the project
		    To prevent stuff from breaking during new commits
		    
  


# Project overview


   ## App made in React Native 

    __________________________________
    
     A React Native app, supporting the same features working with the same backend and API.
     
     The App depicts an app for a restaurant, with several features such as user login, table booking, and other native features created and utilized with the EXPO CLI, for example: integration with the users calendar.
     an API was written in express (mongoose, mongodb). 

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
