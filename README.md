# V5-PreAutonMenu-VCS 

This is the repository for the MenuTester program, which runs on the VEX V5 Brain and uses Vex Coding Studio.

It is encouraged that people use this code to learn from, whether it be making graphics on the screen
or learning how menus flow with each other. Feel free to use code from this program in your own as well.

Due to some limitations within Vex Coding Studio, a [more advanced program](https://github.com/Wup123102/V5-MenuTester-PROS) 
is in the works, which uses [PROS](https://pros.cs.purdue.edu/).

Here is the simple work flow of the program:

![Simple Workflow of Menu](https://github.com/WarrenRobotics/V5-PreAutonMenu-VCS/blob/master/src/common/images/V5PreAutonMenu.jpg)

---

Here is a list of some features:

 * Utilizes most of the space on the screen to display information or buttons.

 * Autonomous mode selection(list), driver selection(list), and driver augment selection(yes/no).(*)

 * Runs in a separate thread.

 * Comes default with 8 autonomous modes by default(including one to do nothing, or skills if desired).

 * Comes with 3 drivers by default.

 * Has a review menu at the end to let user confirm settings, and change them if needed.

 * Flexability to change the name of the autonomous programs and drivers. The names only have to be changed
in one array location.

 * Flexability to add or remove extra options(tutorial in progress, requires adding another array value and creating another submenu).

---

Here is a list of some features we wish to add in the future:

 * An object for a button that contains its position, dimensions, current state, and methods to draw. This will 
allow creating buttons to be much easier, as well as checking if they are pressed. If the idea of a Button object 
won't work, [Jpearman's Buttons program](https://www.vexforum.com/uploads/default/original/2X/1/192a98c87b6c835adfdbee31b339f7c989e79ec7.vex)
(see [this post](https://www.vexforum.com/t/how-do-you-make-buttons-on-the-brain-screen/49294/8)) may be another way to tackle the problem of buttons.

 * Double-Buffered rendering.

 * Allow controller to change options in addition to the buttons on the screen.
 
 * Implement redundancy so that the menu seletor can safely exit(and have default values) if a match were to start without confirming all options
 
 ## Images
 
 ### Autonomous Selector
 ![Autonomous Selector](https://github.com/WarrenRobotics/V5-PreAutonMenu-VCS/blob/master/src/common/images/1.jpg)
 
 ### Driver Selector
 ![Driver Selector](https://github.com/WarrenRobotics/V5-PreAutonMenu-VCS/blob/master/src/common/images/2.jpg)
 
 ### Driver Control Augment Selector
 ![Driver Control Augment Selector](https://github.com/WarrenRobotics/V5-PreAutonMenu-VCS/blob/master/src/common/images/3.jpg)
 
 ### Review Menu
 ![Review Menu](https://github.com/WarrenRobotics/V5-PreAutonMenu-VCS/blob/master/src/common/images/4.jpg)
 
 ### Post-Review Menu(Settings Confirmed)
 ![Post-Review Menu](https://github.com/WarrenRobotics/V5-PreAutonMenu-VCS/blob/master/src/common/images/5.jpg)
