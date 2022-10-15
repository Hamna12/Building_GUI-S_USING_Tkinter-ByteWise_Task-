# What is Tkinter?

Tkinter is the standard GUI library for Python. Python when combined with Tkinter provides a fast and easy way to create GUI applications.
Tkinter provides a powerful object-oriented interface to the Tk GUI toolkit.

# Creating GUI Application using Tkinter:

Creating a GUI application using Tkinter is an easy task. All you need to do is perform the following steps −

Import the Tkinter module.

Create the GUI application main window.

Add one or more of the above-mentioned widgets to the GUI application.

Enter the main event loop to take action against each event triggered by the user.

# Following steps for importing Tkinter:

```python
from tkinter import *

root = Tk()

#creating a label widget
myLabel = Label(root, text="Hello World!")

# Showing it onto the screen
myLabel.pack()

root.mainloop()
```

After running this a pop up of new window will appear.
