# Demo Application 2025
Read everything in __IMPORTANT__ before proceeding.

# IMPORTANT
- This application will start the user off on a participant page. If the app crashes when opening an Activity, it's likely because of a previously used Participant Name or Participant Number. Open the app again, input a random sequence of characters as your participant number, and then try again!
- When navigating this README for each chart type, read the text before the bulleted list for more important information about the chart.
- To move back to the graph selection page, swipe down and up with four fingers to exit the chart.

## Scatter Charts
There are two scatter charts in this application. Property vs Distance are points formatted in a line with a negative slope. Income vs Work Hours are points formatted into 3 distinct clusters. 
- __Sound:__ With both charts, the pitch of the sound effects will increase with higher values and decrease with lower values as the user moves their finger along the data points. This applies to the individual clusters in Income vs Work Hours as well.
- __Vibrations:__ The scatter charts will have a constant vibration when 1 finger is on a colored section of any point on the graph. If the user puts their finger on the grey outline around the colored point, the frequency of the vibration is going to change. Only in the Income vs Work Hours chart, vibration will also be different if their finger is on the center of a cluster.
- __Text-To-Speech (TTS):__ The user can move their finger to any of the text, which will enable TTS to read out the titled text, except for the numerical values next to the x and y axis. The app will state if they are in the chart through TTS, and by holding their finger down on any section INSIDE of the graph, it will read out the x and y values to the user. 
- __Mode:__ By swiping from the right to left using 4 fingers, the chart "mode" will change. The user will know if the chart mode changes as the TTS will say "mode change". With the mode change, there will be a more subtle noise that uses spatial audio throughout the entire chart while the user is navigating the space. There will no longer be the clearer sounds as they navigate through the points until swiping right to left with 4 fingers once more to change the mode back, in which the TTS will say "mode change" again.

## Bar Charts
There are two bar charts in this application. Allergies is shown to be a stacked bar chart. Art Scores shows 3 bars side-by-side per category rather than being stacked.
- __Sound:__ In both bar graphs that are used in this application, a bell noise will play if the user moves their finger through the bolded bar between or top the categories of the bar. The top of the graph is marked by a bolded line, and specifically in the stacked bar chart, TTS will read out which bar they are on by reading out "Allergy A" or "Allergy B" depending on where their finger moves to on the bar.
- __Vibrations:__ The bar charts' vibration will change depending on what color bar the user is on, even if on a stacked bar chart, the vibration will still change with color.
- __Text-To-Speech (TTS):__ TTS works very similarly to the scatter charts, where it will read out the text for the axis and the chart if their finger moves to the text. There are also bar titles that can be read out as well. The chart title does go on for a while, so the user can pinch the screen, out and in, to stop TTS The difference in the bar charts is that TTS will read out the y-axis values to the user as they drag their finger vertically through the graph.

## Line Chart
There is one line chart in this application. The goal of this chart is to start at one of the 3 lines on the left side of the chart, and to move one finger through the line and the intersections until it reaches its end.
- __Vibrations:__  Each line has its own frequency at which it will vibrate; this is how the user will keep track of whether they are on the correct line or not.
- __Text-To-Speech (TTS):__ TTS will work as it has with the other charts, the TTS will read out graph and axis titles. TTS will now also read out if the user is at an intersection and tell them which two lines have crossed if the user's finger is held down. No TTS is used when the user's finger is on the blank space of the chart or if their finger moves to any of the numerical values next to the x and y axes.
- __Mode:__ The number on the bottom left of the activity will change by swiping 2 fingers to the left. This is for keeping track of data in the csv file based on the line that the user would be moving through. The number on the bottom left will NOT change anything with the vibrations or TTS.
