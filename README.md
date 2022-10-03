# Bellrringer
Play outro music before the bell rings in class.
## Features

- Precise time accuracy (100ms)
- Adjustable delay
- Beautiful interface

## Adding your Bell Schedule

> ⚠	You must have basic knowlege of Javascript to set the bell schedule

Add blocks like the one below in the section titled "Add time blocks here". The below code would create a schedule that goes off at 9:56 AM.

     if (cHour == 9) {  
        	    if (cMinute == 56) {  
                   if (cSecond == slider_value) {  
                        play();  
        	     }  
        } 
