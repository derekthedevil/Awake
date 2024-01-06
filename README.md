# Drowsiness Detection System using Python and Opencv 
The Drowsiness Detection System is an innovative application developed using Python and OpenCV. It uses advanced facial recognition techniques to detect signs of drowsiness in the driver. When the system identifies any potential issues, it automatically sends a text message to the registered phone number of the driver.

In the system, a high-speed video camera captures the driver's face at regular intervals. OpenCV then processes the images and uses a pre-trained facial landmarks model to track the eye regions. By analyzing the position and movement of the eyes, the system can accurately determine if the driver is drowsy or distracted.

If the system detects any signs of drowsiness, it activates the Twilio API to send a text message to the driver's registered phone number. The message includes a warning about the drowsiness and the driver's current geographical location, ensuring their safety and security.

In conclusion, the Drowsiness Detection System offers a practical and efficient solution to combating drowsiness on the road. By utilizing advanced facial recognition techniques and integrating the Twilio API, the system ensures prompt notifications and alerts for the driver. This approach ultimately reduces the risk of accidents and enhances overall road safety.



## Importing necessary libraries 

<pre> pip install cv2</pre>

<pre> pip install  dlib</pre>

### If u get error while installing dlib 
<pre> pip install cmake</pre>
and add cmake to system variables path (windows)

## Make sure u have visual studios development kit for c++ installed for windows  

<pre> pip install scipy</pre>
<pre> pip install pygame</pre>
<pre> pip install subprocess</pre>


## Setting up twilio for geo-location message 

create a twilio account 

get account_sid,auth_token,twilio_number from twilio.com and add it to keys.py

## Running the main1.py 

if you are using the cmd 

navigate to folder 

<pre>python Main1.py</pre>

## using vscode 

ctrl + f5 or run without debugging

# about file structure 

- Main1.py - this is the main file that needs to be run 

- Main.py - this file sends alert signal to the user's registered phone number 

- geo.py - this file gets geo-location using ipstack API 

- keys.py - this files is used to store api keys and phone number required for twilio 





