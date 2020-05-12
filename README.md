# My React Native Project 

- Backend :  https://github.com/xAirx/Backend-for-React-Native-project
- Frontend app Code:      https://github.com/xAirx/ReactNativeRestaurantApp
         

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

 ## Component Testing is backed up by Storybook.js
   
   	Small explanation: 
	
	https://blog.logrocket.com/react-storybook/
	
	
   
                    Storybook.js is a tool that helps writing components in isolation, and showcase them interactively in an isolated dev environment. 

	            The idea is to isolate show its behavior in a series of tests. This way we can make sure it works.
			
		    Storybook offers different techniques for testing UI components. Components need to undergo tests for a variety of reasons some of which are:

		    Detection of bugs
		    Tests can be documented to serve as guidelines for other developers who will work on the project
		    To prevent stuff from breaking during new commits
		    
   
   
   ## Simple Devops Setup 
                                      

	Simple Devops Setup. (Roughly)

	 Dev -> pre hook ->  Github -> CI/CD (gitlab) 
	  ->  Staging Unit-testing // Storybook Js (Component isolation and  Testing)                                                                                                                                   		->  Build stage   (Project build (minifying etc happens here))
	  ->  Deployed to ***** -> (Live in production) 

	Sentry and Logrocket monitoring 
	-> Integration with github, bugfixes with case id’s devbranch 
	-> master
	-> trigger devops setup above.          

   
&nbsp;
&nbsp;
&nbsp;


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
