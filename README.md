
## Heirs ANV-1030
Key features of this power supply are as follows:
- Cheap yet feature-rich variable DC-DC power supply
- Aimed towards beginners as a DIY electronics project
- Comprehensive documentation 
- Adequate accuracy and performance for general electronics use
- Use of cost oriented and widely available components
- A linear topology without digital control for simplicity and low cost
- Complete set of protections (OVP, OCP, OTP, SCP)




This variable analog bench power supply is designed whilst taking into consideration the following requirements:
- A relatively low power step-down DC-DC converter
- No digital control component
- Fast charge USB output with voltage and current monitoring outputs
- An Entirely non-switching linear topology
- Current, voltage, I_SET and OVP_SET should be displayable via two 3rd party voltmeter modules
- For visual output we are gonna use 3rd-party off-the-shelf voltmeter modules which can be priced as low as 0.90$ each
- Minimal over-shoot at power on/off
- Various protection mechanisms such as adjustable over-voltage(OVP), over-current(OCP), over-temperature(OTP), short-circuit(SCP), reverse voltage protection
- Remote voltage sensing (Kelvin wiring)
- Fan-less design relying on passive cooling
- Use of cost-oriented and widely available components
- Only a single variable output channel
- Modular design as the user can use any battery/ac-dc converter as the power source
- 

Wattmeter display
- OVP, CC, CV.  front panel LED
- front panel output on/off button

Add OCP

Use eeprom and adc for seven segment monitors

Goddammit adding stm8s003f3 cheapest microcontroller with an adc for front panel control

Now i have to reconsider a lot of things

Use pwm to drive output voltage through the opamp

Using pwm and adc at the same time might cause inaccuracies it should be tested for the specified microcontroller
 
 transformer tap for 220/110 compatibility
 
  beep on/off button
  
   standard distance between output terminals
   
   ovp ocp enable/disable button
   
   crow bar output protection
   
   soft and hard on/off switches
   
   ac input goes directly to the front panel
   
   different voltage taps of the transformer with relay or triac control for performance
   
   surviving fast shorts on the output
   
   gate being shorted to drain 
   
   thermally isolating the voltage reference on the pcb
   
   seethrough plexiglass front panel with laser print and cut
   
   پلکسی گلس خیابان پامنار
   
   mirror plexiglass reverse engraving
   
   main bjt transistors for durability
   
   electrophoresis compatible
   
   seperate digital and analog parts on the pcb

   seven segment display on the pcb

   optional switching pre regulator board for performance improvement
   
   analog programming of the power supply

   biocompatible with low leakage

   fast surge current protection for the load

   timer!

   kV surges from the output protection

  banana to usb converter 
