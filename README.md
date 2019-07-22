# arduino_interrupt
Write a program for the Arduino that utilizes interrupts. Interrupts allow a section of Arduino code to be called without writing code in the loop( ) function to explicitly check that code

Each button is to trigger an interrupt. The interrupts are to toggle between two states/messages displayed on the 16x2 LCD.
* When no button has been pressed your 16x2 display should say something like "We have
  been waiting for X seconds", where X starts at the value 0 and is updated as time goes on.
  This is State 0.
* When the first button is pressed, the display should display “Interrupt received! Press
  button 2 to continue”. This is State 1.
* When the user presses the second button, the display goes back to displaying "We have
 been waiting for X seconds", and restarts the time at 0 seconds. (I.E. go back to State 0.)
