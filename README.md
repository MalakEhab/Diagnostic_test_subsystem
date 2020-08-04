# Diagnostic_test_subsystem
The program is written on arduino mega 2560 and using LCD 16 × 2 , Joystick, 2-Pushbutton, RGB LED.
The testing should be initialized by pressing of a push button,
where in that case in the first line of the LCD the message “Test Mode ON” should be displayed for 1 second.
After the 1 second has elapsed the LCD display will show the list of options.
A visual menu should be used on the LCD display that the user will use to scroll through the current options,
where in the first line of the LCD the current active item of that menu (option) should be displayed and in the second line the next option should be displayed. 
The menu should contain the following values: o [1] First test o [2] Second test o [3] Third test o [4] Fourth test o [5] Exit test.
The current option should change with the use of the joystick.
The pushbutton of the joystick should allow the user to access that option. 
Pushing the push-button will activate the respective option. 
When options [1] – [4] are selected then the test of that specific component should start. 
During the test phase the blue LED of the RGB LED should blink for 5 seconds with a time blinking period of 250msec. 
A second push-button is used to simulate the existence of an error. 
If during the testing time the push-button is pushed, then the red light should turn on after the 5 second interval has elapsed. 
If the push-button was not pressed, the green light should turn on. 
By pressing the push-button of the joystick again, the program should get the user back to the selection mode, 
and the RGB LED should turn off. 
If the option [5] is selected, then the screen should be turned off.
