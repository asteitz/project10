# Project_10 - Sensor and Gesture App

*Ashley Steitz and Jacob Fritz collaborated on this project.*

---

**Description**

In Project 10, we developed an Android app using Jetpack Compose that showcases the functionality of gesture and sensors.
The app consists of two activities: Sensor Activity and Gesture Activity.

In Sensor Activity:
- Displays the user's name, location (state and city), current temperature, and the value of another chosen sensor (excluding Accelerometer and Light sensor).
- Includes a button "Gesture Playground" that supports fling operation, navigating the user to Gesture Activity upon performing a fling operation.
- Utilizes the Geocoder class to retrieve location information.

In Gesture Activity:
- Divides the activity into two fragments.
- The top fragment contains a red ball that moves with user gestures.
- The bottom fragment logs the activities performed in the top fragment.
- The red ball responds to user swipes, moving accordingly.
- Records and updates a log of gestures performed by the user.

Bonus 10%:
- Created a third activity replicating Gesture Activity, using a sensor (e.g., accelerometer) to move the ball within the fragment.

**Functionality**
[Opened the app]
[Swipped Down]
[Swipped Left]
[Swipped Right]
[Swipped Up]
[All gestures populated the screen]

---

## Video Walkthrough

Watch a demonstration of the app's functionality in the GIF available ![Recording in GIF of Walk Through](https://github.com/asteitz/project10/blob/master/app/src/main/java/sensory/activity/project10/Project10FullRecording.gif).
*GIF created with [CloudConvert](https://cloudconvert.com/).*

The link to the Google eplay will be avalible shortly - however due to the post I made I am having an unforeseen issue with the Google Play Store not accepting my account despite all items being filled out. This means I am unable to push to production. Right now I am linking the post I made on inscribe, later it will be replaced with the _Google Play Store_ link but for now the link is [here](https://inscribe.education/main/indianau/6754110229504431/conversations/6749461750113015?backToListTab=all).
**UI Challenges:**
- uploading to the google play store
- Handling the live data
- Adjusting to Jetpack Compose

**Backend Challenges:**
- identity verification
- creating the key and matching it to the app bundle and linking it to the app release on google play 
- Learned how to work with the position and location functions.
- A lot of new content (gestures, lat, long, etc...) that was difficult to integrate using the source links at first but made sense after whiteboarding and lecture.

---

## License

    Copyright [2023] [Ashley Steitz, Jacob Fritz]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


