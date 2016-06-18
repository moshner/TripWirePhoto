# Trip Wire Photo

Set up a trip wire using a laser (or flashlight), LittleBits, IFTTT, Tasker, Join, and Google Drive.

## A) Set up the trip wire using little bits.
1. Connect the Power Bit to the Light Sensor
2. (optional) Connect the light sensor to the voltage counter to see the voltage being used.
3. Connect to the cloud bit.
4. Shine your laser/flashlight into the light sensor

## B) Set up little bits to IFTTT
1. Connect littlebits to IFTTT
2. Create a recipe that triggers when the cloudbit no longer sees the flashlight.
3. Set up the recipe to send a message to your camera (in my case my phone)

## C) Set up AutoRemote to receive the signal from IFTTT
1. Connect AutoRemote to IFTTT (TODO, insert link to intructions)
2. Set up a Profile to trigger when that data is received.

## D) Set up Tasker Task
1. Name it 'Hi' or something.
2. Setup action to delete a file named /DCIM/Tasker/%HiFoto
3. Set a variable %HiFoto to %TIMEMS (time in milliseconds)
4. (optional) Play a music file with the sound of a camera shutter
5. Take a photo with the front camera and name it %HiFoto. Optionally you can check "Discrete" to
6. Send the photo to the location of your choice. Like using JOIN to push it to a specific device.

## E) Test it out
Try out your new laser trip wire camera. 

#Possible Uses
There a bunch of possible uses for this feature.

1. Find out which cat is using the litter box and when.
2. Log the people who walk up to your door
3. Scare intruders
4. Cookie jar surveillance
5. Show kids what animals came to a feeder
6. Watch for packages being delivered to your door
7. Track movement through a doggy door
8. Any other ideas?
