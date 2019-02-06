# Trip-Planner-and-Tracker
You will have to install google play services on GenyMotion if you want to use GenyMotion as your emulator. In this assignment you will be implementing a simple location tracking application. The application tracks the user’s current location using the device’s GPS and draws the tracked user’s path on a Google map using PolyLines. 
MainActivity:
This app is composed of a single activity. This activity should display a Google Map Fragment.
The implementation requirements include:
1. A location manager should be used to retrieve your current location, through activating the
location provider (GPS). Make sure to configure the location listener’s minimum distance
and time appropriately.
2. Location tracking includes the logic required to enable the location provider and listener, it
also includes the logic required to draw the tracked locations on the Google Map. The
location tracking is initially turned off when the app starts. Upon a long touch the location
tracking should be started, a toast message should be shown to indicate that the tracking
has started, see Figure 1(b). Finally if user long touches the map while tracking this should
end the location tracking. A toast message should be started to indicate that the tracking has
stopped.
3. A marker should be used to display the start and end locations on the google map.
4. Using PolyLine, display the paths on the map taken so far by the user. The path should be
updated periodically when the user’s location changes. For more information about PolyLine, please visit: https://developers.google.com/maps/documentation/android-api/
shapes
5. The map bounds should be automatically setup to include all the polylines created based on
the user location updates. The map should auto zoom and automatically setup the bounds
to include and show the polylines drawn so far. You should explore the use of
LatLngBounds.Builder (https://developers.google.com/android/reference/com/google/
android/gms/maps/model/LatLngBounds.Builder)
6. Generate an APK file for your app, and the APK file should be included in your submission. 

