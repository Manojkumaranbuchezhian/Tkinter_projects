# Digital clock
In the following application, we are going to use Label widget and also going to use time module which we will use to retrieve system’s time.

# Code Explanation
1. The code starts by importing the necessary modules.
2. The first module is the tkinter library, which provides basic functionality for creating graphical user interfaces (GUIs).
3. Next, the strftime function is imported to retrieve system time.
4. Next, a window is created and given a title of “Clock.”
5. A function called time() is then created to display the current time on the label widget.
6. This function uses the strftime() function to format the time string according to system conventions.
7. The last part of this code sets up styling for the label widget so that it will look nicer.
8. Finally, an instance of Label is created and placed at the center of the window.
9. The time() function is executed, and your output should look like this: Clock: Tue Dec 12 08:00:00 2016
10. The code creates a window and assigns it the title “Clock”.
11. The time() function is then called to display the current time on the label widget.
12. The lbl.config() function is used to set the text of the label widget.
13. The after() function is used to delay displaying the time for 1000 milliseconds.
14. Finally, the style of the label widget is modified with lbl.pack().
