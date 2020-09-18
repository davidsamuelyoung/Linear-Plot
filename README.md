# Linear Plot

Latest version: v0.01 

## Updating your version

You have two choices in updating your version of Linear Plot:

#### Updating Option 1 (large bandwidth usage)
Click "Code" > "Download ZIP" (You can then delete the rest of the 
files in the folder except the application)

OR

#### Updating Option 2 (very little bandwidth usage)
Open this [link](https://raw.githubusercontent.com/davidsamuelyoung/Linear-Plot/master/Linear%20Plot.app/Contents/Resources/LinearPlot.py).
Once the raw file has loaded, copy the entire document (from 
"#  Copyright ..." to "start_up()").

Then navigate to Linear Plot on your Mac. Right-click Linear Plot and then "Show Package Contents".
Open "Contents" > "Resources". Right-click on "LinearPlot.py" and choose "Open with TextEdit".
Remove all of the code inside "LinearPlot.py" and paste in the code you copied from the [link](https://raw.githubusercontent.com/davidsamuelyoung/Linear-Plot/master/Linear%20Plot.app/Contents/Resources/LinearPlot.py).

Hit "Save" (or "cmd + s") to save the file and then close TextEdit. 
Your version of Linear Plot will now be updated.

## About Linear Plot
Linear Plot uses the Python programming language along with "matplotlib" and "numpy" 
to create high quality lines of best fit from x- and y- data points.

Linear Plot allows a decent amount of personal customization of the application. 
This is in order to allow users to seamlessly integrate their plots with the document 
they are writing (or for whatever other use they need lines of best fit for).

## FAQ
**Q.** Why does Linear Plot lag while resizing the window?

**A.** Matplotlib is creating a very high quality graph behind the scenes. 
Currently the only way to fix this issue is by using a more powerful computer.

**Q.** Why are many common fonts missing from the "Change Fonts" option?

**A.** At the moment Python and Matplotlib do not share all the possible fonts available. 
If this changes I will promptly update Linear Fit to show such fonts
