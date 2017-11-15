# Arduino-Board
## Week One
I was not here but I heard that it was mostly explaining of the boards and what to do and not many people got anything to work
## Week Two
I started of not knowing anything. I was really confused and I was not sure what I needed to do.
I have been told that we needed to get the red light to blink and somehow we did it.
## Week Three
This week we did a lot! At the start we did not know what we were doing 
but after a really long time of troubleshooting we were able to get the board to work.

Our problem was that we did not push the code into the right port and we also didn't have the right board setup in the software
## Week Four
We could not get the program to work like in needs to yet. We think we might need a delay so we will do that next week. The light works but if you press it a lot it fires randomly
## Week Five
We added a delay and it looks pretty good but we needed to use milliseconds. millis() gives you the time in milliseconds at the current time of the program so we tried to add an if that will use 2 millis() and check if milli1 - milli2 is bigger the the intervel(delay) if it is it will run the button. We found the problem we had it was the our milli1 kept on setting back to 0 and then it could not be bigger then the delay
