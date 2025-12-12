# Final-Project
  - This build will read the temperature when you press a button, then it will display the temperature onto a LCD screen and depending on the temperature light up a red or blue LED
  - Video of what it is:
    - https://github.com/user-attachments/assets/eeb756a8-f630-4d3c-802e-08e10125732c



## Materials
- LD 16x2 display
- Blue LED(5mm)
- Red LED(5mm)
- Tactile Buttle 
- DHT 11 temp/humidity
- MM jumper wires
- Resistors
- Bread Board
- PI

## How to Wire:
- Collect all supplies(shown above)
  - Wire blue and red LEDs using two MM jumper wires, one resistor, and the colored LED for each one:
![PicofSupplies](https://github.com/user-attachments/assets/a519eb3f-1dc3-4545-8eeb-722e9d629852)

  - Use this picture to help with wiring:
<img width="2164" height="1123" alt="LEDwiring" src="https://github.com/user-attachments/assets/04608f24-33b2-42bd-b9df-fa6884d24989" />

  - After doing that for both the red and the blue LEDs, attatch the tactile button or DHT 11 temp/humidity sensor next:
      - Three MM jumper wires and a button or temp/humidity sensor:


  - Then attatch the last piece, the display:
      - Four MM jumper wires and a LD 16x2 display
   
## How to Run:
- Press button, program should start running and the temperature sensor will take the temperature. Then the code will check if the temperature is either bigger or lower than 72 degrees fahrenheit and light up the red or blue LED accordingly. The screen should display what the temperaure is whether or not the red or blue leds light up. 

## Description of Code:
<img width="734" height="990" alt="Screenshot from 2025-12-12 14-32-44" src="https://github.com/user-attachments/assets/38193cb5-fb6b-45d0-84cd-d5e3c1ff6077" />

- imports everything needed to run program and connect to build
- connects with parts of build and name them
- "def to_fahrenheit(c):" translates the celsius temp from the sensor to fahrenheit and returns it
- "def start_program():" does not start until the button has been pressed and then it runs the bulk of the program


<img width="1560" height="990" alt="Screenshot from 2025-12-12 14-33-03" src="https://github.com/user-attachments/assets/c2ce6043-9b91-4d39-aa88-3a67d8119961" />
<img width="656" height="990" alt="Screenshot from 2025-12-12 14-33-17" src="https://github.com/user-attachments/assets/4ebc3e78-b866-4729-bec4-a68605f83944" />


- gets the format of how to print the time, celsius, and fahrenheit on the screen
- if the temperature is higher than 72 degrees fahrenheit then it turns on the red light, but if the temperature is lower than 72 degrees fahrenheit then the blue light turns on.
- No matter what the temperature, the LCD screen will always display the temperature in fahrenheit


<img width="858" height="990" alt="Screenshot from 2025-12-12 14-33-30" src="https://github.com/user-attachments/assets/2eae3b37-56e9-4467-958a-74b07b1b51e0" />


- makes sure program can run through some errors, and lets you end the program with a KeyboardInterrupt error
- this is the code for when the button is pressed, then the "def start_program()" will start running
- "pause()" stops the program until the button is pressed and the program starts up again





## Resources:
- Youtube 1: https://www.youtube.com/watch?v=-_XkGju35MI&t=270s 
- Youtube 2: https://www.youtube.com/watch?v=Hp9UjSjiH5I 
- GeeksforGeeks: https://www.geeksforgeeks.org/computer-organization-architecture/i2c-communication-protocol/ 
- Infineon: https://www.infineon.com/design-resources/development-tools/sdk/psoc-software/psoc-4-components/character-lcd-charlcd 
