# ANDROID_Looper

Looper
-----------
Class used to run a message loop for a thread. 
Threads by default do not have a message loop associated with them; to create one, call prepare() in the thread that is to run the loop, and then loop() to have it process messages until the loop is stopped.
Most interaction with a message loop is through the Handler class.
This is a typical example of the implementation of a Looper thread, using the separation of prepare() and loop() to create an initial Handler to communicate with the Looper.

ScreenShots
-----------
<div>
<img width="200" src="https://user-images.githubusercontent.com/32612534/40411584-2d379632-5e71-11e8-9118-2d0009f71c06.png">
<img width="200" src="https://user-images.githubusercontent.com/32612534/40411587-2e056f9e-5e71-11e8-9a8c-3b19dd1099f5.png">
</div>

