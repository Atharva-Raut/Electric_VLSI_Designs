# CMOS Analog Design Self-learning Project
A collection of sample CMOS analog layouts in 0.6um technology, using Electric VLSI Design System<br>
This repository is a part of a self-learning project done to explore the field of CMOS Analog IC Design 
based on the concepts taught in the course EE618 (view on [CDEEP](https://www.cdeep.iitb.ac.in/vod/vodCloud/course_intra.php?ccode=296&referSrc=57dc9eb7be985a0e14aaa07846b0b9b4))

## Contents

[electricBinary-9.07.jar](electricBinary-9.07.jar) is an executable Java program for Electric VLSI Design System software

[Amplifiers.jelib](Amplifiers.jelib) can be loaded in Electric to view the layouts

[C5_models.txt](C5_models.txt) contians the models for NMOS and PMOS transistors obtained from [here](http://cmosedu.com/jbaker/courses/ee421L/f13/students/mummm2/Lab4/lab4.htm)

[Amplifiers_design.docx](Amplifiers_design.docx) has calculations and approximations taken while designing the schematics


## Usage
### Viewing and editing layout
- Make sure [Java](https://www.java.com/download/ie_manual.jsp) is installed on your system
- Open the executable binary of Electric, can be found [here](electricBinary-9.07.jar) or download from the [official site](https://www.staticfreesoft.com/)
- Open the file [Amplifiers.jelib](Amplifiers.jelib)
- Explorer tab lists all the designs contained in the library
- For a quickstart tutorial on designing in Electric, refer this [youtube video](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwit7v2OkvLxAhWEWHwKHYZTAAUQwqsBegQICRAB&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DJqj8VmS38fw&usg=AOvVaw2-waRGAWHKLHIP9NAhbdTq)

### Simulations
- Download LTspice XVII from the [here](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html)
- Set preferences under SPICE/CDL section in Electric according to this [guide](http://cmosedu.com/cmos1/ltspice/ltspice_electric.htm)
- For simulating, click Tools->Simulation(Spice)->Write Spice Deck...
- This will launch LTspice
- In LTspice, right click on the plot pane->Add Traces and select the plots you want to view
___

Project Author:<br>
Atharva Raut<br>
Undergraduate Student, IIT Bombay

The author of this work hereby waives all claim of copyright (economic and moral) in this work and immediately places it in the public domain;
it may be used, distorted or destroyed in any manner whatsoever without further attribution or notice to the creator.
