💡 Dual LED Blinking System (Arduino UNO Simulation)

This project simulates two LEDs blinking alternately using an Arduino UNO, built and tested on the Wokwi online simulator. It demonstrates how digital pins on a microcontroller can control output devices like LEDs using simple logic and timing functions.


---

🧠 Project Overview

Uses two digital pins to control two LEDs.

LEDs blink alternately every 200 milliseconds.

Basic embedded systems logic using digitalWrite() and delay().

Built using Arduino IDE and simulated on Wokwi.



---

⚙️ Tools & Technologies Used

Arduino UNO

Wokwi Simulator (virtual hardware)

2 LEDs

C++ / Arduino Programming



---

💡 Features

✅ Blinks two LEDs alternately

✅ Demonstrates digital output control

✅ Useful for beginners learning microcontroller basics

✅ 100% online simulation



---

▶️ Simulation Link

👉https://wokwi.com/projects/436017112453510145

📁 Files Included

File	Description

main.ino	Arduino code for LED blinking
diagram.json	Wokwi circuit layout
README.md	Project documentation



---

🔧 How It Works

void setup() {  
  pinMode(8, OUTPUT);  
  pinMode(9, OUTPUT);  
}  
  
void loop() {  
  digitalWrite(8, HIGH);  
  digitalWrite(9, LOW);  
  delay(200);  
  
  digitalWritel8, LOW);  
  digitalWrite(9, HIGH);  
  delay(200);  
}



