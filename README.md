micro:bit Button Controlled Emoji Animations
--------------------
In this assignment you will program your micro:bit using the two built-in buttons to show your feelings. Your program will have two different animated emojis. For example, one button might trigger a happy emoji animation ane the other a sad emoji animation. Your program will be similar to the previous assignment, but you will need to use at least two if statements to check if either of the buttons has been pressed.

Here is a sample program that displays Pacman for one second when the left button (referred to as the "A button") is pressed and a ghost when the right B button is pressed:
```python
from microbit import *

while True:
    display.clear()
    if button_a.was_pressed():
        display.show(Image.PACMAN)
    if button_b.was_pressed():
        display.show(Image.GHOST)
    sleep(1000)
```


Program requirements
-----------------
* Your program must use at least two original animations
* Each button will start a different animation
* Submit both the Python code and an animated gif showing your program running to Google Classroom

Suggested steps to completing this assignment
----------
1. TBD

Samples of Student Work
----------
[Evangeline](EvangelineEmojis.png)   
