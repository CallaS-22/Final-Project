# Final-Project
  - This build will read the temperature when you press a button, then it will display the temperature onto a LCD screen and depending on the temperature light up a red or blue LED
  - Video of what it is

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
- either add comments to your Python file in the repository already, or copy your code into this Markdown file and add comments. These should explain your code.

## Reasources:
- Youtube 1: https://www.youtube.com/watch?v=-_XkGju35MI&t=270s 
- Youtube 2: https://www.youtube.com/watch?v=Hp9UjSjiH5I 
- GeeksforGeeks: https://www.geeksforgeeks.org/computer-organization-architecture/i2c-communication-protocol/ 
- Infineon: https://www.infineon.com/design-resources/development-tools/sdk/psoc-software/psoc-4-components/character-lcd-charlcd 
