# Electronic-DJ-Soundboard
The Electronic DJ Soundboard I designed in Eagle while serving as hardware lead on a 4-person team. I picked out the chips, designed the circuit, performed layout, soldered all components and tested and verified the board with a power supply and digital multimeter. 

I also coordinated with the embedded software lead on GPIO pin assignments, I/O functionality, communication protocol usage, and peripheral connections to support embedded firmware development.


<p align="center">
  <img src="https://github.com/user-attachments/assets/1155b4fa-6265-40bb-9c61-7e30dbf6d3ba" width="700">
  <br>
  <em> The DJ circuit board outside its enclosure. I laser cut the enclosure and sanded it so it would fit together. </em>
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/ec44a738-2afb-4133-98fc-19c236798699" width="700">
  <br>
  <em> The DJ circuit board from another angle. </em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/77563db1-35d9-429f-b6cb-36e5cb82a0f5" width="700">
  <br>
  <em> The main DJ circuit board.</em>
</p>


## Hardware: 

1. **TM4C123GH6PMI microcontroller launchpad** (as the main MCU for the project)
2. **Ceramic and Tantalum capacitors** (various purposes)
3. **ESP8266 Wifi module** (for saving user-made sound clips)
4. **TLV5618ACP DAC** (for outputting to the two speakers)
5. **MC34119 audio amplifier** (for amplifying the DAC output to the speakers)
6. **ULN2803a transistor array** (for powering the LED arrays)
7. **LM4041CILPR shunt voltage reference** (required for the TLV DAC)
8. **Resistors** (various purposes)
9. **Wire nuts** (for connecting the LEDs to the transistor array)
10. **LM2937 3.3 V regulator** (for powering different parts of the board)
11. **Testpoints** (for verifying that different parts of the board work)
12. **Blue, Red and Yellow LEDs** (to light the translucent buttons when pushed)
13. **MC7805ABTG 5V regulator** (for powering the LED array)
14. **8-ohm speakers** (for outputting user-made sounds)
15. **Audio jack** (so you can choose to use the built-in speakers or attach your own personal speaker for better sound quality)
16. **Pin headers**(to connect the launchpad to the board, and to have maximum flexibility in testing prototype)
17. **DC power connector** (to power the board)
18. **ST7735R LCD** (for displaying info to the user)
19. **Wood enclosure** (to store all electronics)
20. **Turn potentiometer** (for volume change)
21. **Slide potentiometer** (for tone change)
