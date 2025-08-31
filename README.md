# Agricultural-Monitoring-System
Smart Farming Made Simple with IoT

Farming is never easy — keeping track of the weather, soil, and water needs takes constant effort. That’s why this project was built: a smart farming system that can watch over your plants and even water them for you, all while you relax or check things from your phone.

At the heart of it is a tiny Wi-Fi board (ESP8266) and a bunch of small sensors. These little devices can tell you how hot or humid it is, check if the soil is too dry, notice if there’s movement nearby, and even switch a water pump on or off. The best part? You don’t need to be on the farm — you can control everything from an app on your phone.

🔧 What It Can Do for You

🌡 Check the weather around your crops (temperature & humidity)
🌱 See if your soil is thirsty and needs water
🕵 Get alerts if something moves (like animals in the field)
💧 Turn the water pump on/off automatically or do it yourself with a tap on your phone
📱 Stay connected anywhere through the Blynk mobile app
🖥 See live readings on a little screen right next to the system
🔘 Press a button if you just want quick manual control
☁ Receive cloud alerts when something important happens
🧰 What You’ll Need

It only takes a few simple parts to build this system:

A Wi-Fi board (ESP8266)
A sensor to check temperature & humidity
A sensor to measure soil moisture
A sensor to detect motion
A relay (this works like a switch for the water pump)
A small LCD screen to show live readings
A push button for quick manual pump control
A few jumper wires and a breadboard to connect it all
📲 Connecting It to Your Phone

The system uses the Blynk app, which makes everything simple:

Open the app and make a new project
Choose ESP8266 as your device
Copy a little code (called an Auth Token) into your program
Add widgets to show temperature, humidity, soil moisture, and pump control
Now your farm is literally in your pocket!

📟 The On-Site Display

The small LCD screen shows everything at a glance:

T: Temperature
H: Humidity
S: Soil Moisture
M: Motion (Yes/No)
W: Water Pump (ON/OFF)
So even without your phone, you can see what’s going on.

⚙ How It All Works Together

Think of it like this:

Sensors are the “eyes and ears” of the farm — checking soil, weather, and motion.
The data goes to the LCD and also straight to your phone app.
If the soil is dry, the pump can switch on by itself, or you can do it from your app.
The motion sensor acts like a tiny security guard, sending you an alert if there’s movement.
And if you’re standing next to the system, you can just press the button to turn the pump on instantly.
It’s like having a smart assistant for your farm.

🚀 How to Get Started

Download the project files
Install the required software on your computer (Arduino IDE + a few libraries)
Upload the code to your ESP8266 board
Connect the sensors and pump as shown in the guide
Open the Blynk app — and your farm goes online!
🧠 Future Possibilities

This is just the beginning. You can:

Make the system water automatically whenever the soil dries out
Use more accurate sensors for better readings
Save all the data into Google Sheets or the cloud for analysis
Run it on solar power, perfect for outdoor farms
🌾 With this system, farming becomes smarter, easier, and more connected — giving you more time to focus on growing instead of worrying.
