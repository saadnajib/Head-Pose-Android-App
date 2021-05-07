# Head-Pose-Android-App

This App is the implimentation of PassCam.
You can find PassCam repository here : https://github.com/zekariass/PassCam

App will look for 4 different poses (front,left,right,random),

If threshold for "front-pose" is met it will change color to "Green" and headpose text to "Front" and will allow user to take a picture else if threshold is not met it will change the color to "Red" and headpose text to "Invalid" and therefor will not allow the user to take a picture (different color indicates different poses).

thresholds are:

Front : pitch(-10 to 10) and yaw(-20 to 20) Color(Green)
Left : pitch(-10 to 10) and yaw(-30 to 50) Color(Yellow)
Right : pitch(-10 to 10) and yaw(-50 to -30) Color(Blue)
Random : pitch(17 to 45) and yaw(-46to 46) Color(Purple)
