# Campus Commute (Android Application)

#### Authors: Ajit Vijayakumar and Saagar Parikh 

## W18 Final Remarks 

### Running the Application 
1. Load the project on Android Studio
2. Get a new Google Maps API Key (https://console.developers.google.com/apis/api)
3. Get your google-services-JSON set up (https://developers.google.com/mobile/add)
4. Press "run" (green play button on the top right)
5. Select a virtual device, or connect your own with a USB cable 
6. Campus Commute application will now open up

### Current Progress (what we accomplished) 
1. When the application opens, it opens with the current location set to UCSB on the map (using Google Maps API)
2. Two spinners are shown on top 
3. Each of these spinners contains a drop down of 5-6 UCSB classroom locations 
4. If you select a classroom on either of these spinners, the location of that classroom will be displayed on the map 
5. A "calculate" button is present - this button should be able to calculate the walking time between two different classrooms on the two spinners. Then, the app displays the walking time

### Current User Flow (what we accomplished) 
1. The user opens up the applications
2. A map is displayed with the location set to UCSB 
3. The user can now simply display a classroom, by choosing it from the spinner list. 
4. The user can also pick two different classrooms, one on each spinner. 
5. The user can now press calculate, and the estimated walking time will be displayed. 

![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/Sceenshot1.png)
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/Screenshot2.png)
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/Screenshot3.png)

### Ideas for the future (some of these features can be seen in the sketches below)
1. Inputting a more comphrensive list of campus locations 
2. Allowing a user to input a class schedule, either mannually by creating new "courses" (as seen in #4 below) or by logging onto UCSB Gold on a portal and creating a JSON object of their schedule
3. Adding notifications feature in whcih user can allow the app to send notifications for when to leave for their scheduled item, perhaps also adding an alarm feature 
4. Adding a "start" button that when a user clicks, it will automatically detect which class the user is currently in, and sets up alarms/notifications accordingly 
5. LONG TERM GOAL: Introduce this application to UCSB affliciated apps to help students throughout the school 

### Proposed Wire Frame Diagrams 
1. Full Wireframe View 
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/Full_Wireframe.jpg)
2. First Time User 
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/FirstTimeUser.jpg)
3. Returning User
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/ReturningUser.jpg)
4. New Schedule (Enter Manually) 
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/NewScheduleManual.jpg)
5. New Class (Enter Manually) 
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/NewCourse.jpg)
6. New Schedule (through UCSB Gold portal, converting schedule to JSON Object)
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/NewScheduleGold.jpg)
7. Map View with options bar
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/Map_View.jpg)
8. Full Map View 
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/FullMapView.jpg)
9. Location Selected 
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/LocationSelected.jpg)
10. Start option selected 
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/StartSelected.jpg)
11. Set Alarm 
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/Alarm.jpg)
12. Display Notifications 
![alt text](https://github.com/ajitvijay/cs56-android-calculate-walking-time/blob/master/campusCommuteWireframe/DisplayNotifs.jpg)
