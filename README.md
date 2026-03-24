# Memory-Game-with-ESP32C3Mini
Simple memory game with ESP32C3Mini, 5 pushbuttons, 5 LEDs, 1 Oled LCD, 1 Buzzer and powered by a 18650 Battery

I've made this game for the fun of coding, schematic drawing and PCB Design.
Code is available for you to improve, change, hack or just use as it is.
Gerber Files available too (still waiting for the PCBs to arrive from JLCPCB to test)

The game consist in a simple colour memory game where you see a LED light up and press the corresponding button. 
Each time you make it it adds new colour to the sequence until you fail. It sings a sort of Sad Trombone tune when you loose.
If you solder the ESP without programming (or want ot change the code later) you need to enable the SW2 for programming, this will disconnect the OLED from the ESP. This is because the ESP uses the same I2c pins for the LCD and programming.
Once I have the first board built I'll upload a few photos of it ;-)
All parts are easily available on the internet, Aliexpress, Ebay and other electronics parts retailers like BitsBox, Pihut etc.
Hope you like it and have fun building this.

Disclaimer - I'm not liable for anything that may happen when you handle the battery, electronics parts and solder. Please don't build this if you ain't confident enough. Ask for help ;-)

![prototype_mem_game](https://github.com/user-attachments/assets/9a345ab1-32d8-4850-8b4d-e17f02a5d0a6)


TO DO:
- Change screen szie and check code for bigger screen
- design a enclosure, either laser cut or 3d printed
- create kit and make available
