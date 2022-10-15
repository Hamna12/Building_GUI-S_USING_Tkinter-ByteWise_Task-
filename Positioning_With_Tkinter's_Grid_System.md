# Positioning with Tkinter's Grid System:

The grid layout has 4 main options that you can use while positioning widgets.
* row – The row at which the widget is to be placed
* column – The column at which the widget is to be placed
* columnspan – The number of columns the widget will occupy
* rowspan – The number of rows the widget will occupy

There is no limit to the number of columns and rows you can have in the grid. The highest column and row numbers you enter into your grid,
will become the determine the number of rows and columns.

# What is grig in python Tkinter's?

The grid() method allows you to indicate the row and column positioning in its parameter list. Both row and column start from index 0.
# Example:
For example grid(row=1, column=2) specifies a position on the third column and second row of your frame or window.

# Code:
```python
from tkinter import *

root = Tk()

#creating a label widget
myLabel1 = Label(root, text="Hello World!")
myLabel2 = Label(root, text="My Name is Hamna Qaseem")


# Showing it onto the screen
myLabel1.grid(row=0, column=0)
myLabel2.grid(row=1, column=5)


root.mainloop()
```
