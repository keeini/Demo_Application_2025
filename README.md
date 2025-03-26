# Demo_Application_2025
This demo application will utilize scatter, bar, and line charts from multiple activities all in one!

- __SOAR_NFB_2024__: Property vs Distance and Income vs Work hours
- __CSUN_2024_DEMO__: Allergies and Art Scores
- __LDV_User_Study_2024__: S9 Line

This will be a guide to help anyone navigate the app easily.

# IMPORTANT
This application will start the user off on a participant page. The user __MUST__ input a random string as the participant number. If not, the app will crash upon opening any of the activities on the app.

## SOAR Scatter Charts
There will be two scatter charts from the SOAR_NFB_2024 app. Property vs Distance are points formatted in a line with a negative slope. Income vs Work Hours are points formatted into 3 distinct clusters.
- __Vibrations:__ The scatter charts will have a constant vibration when 1 finger is on a colored section of any point on the graph. If the user puts their finger on the grey outline around the colored point, the frequency of the vibration is going to change. The vibration will also be different if their finger is on the center of a cluster.
- __TTS:__ The user can move their finger to any of the text which will enable TTS to read out the titled text. The app will state if they are in the chart through TTS, and by holding their finger down on any section INSIDE of the graph, it will read out the x and y values to the user.
- __Mode:__ By swiping to the left using 4 fingers, the chart "mode" will change. The user will know if the chart mode changes as the tts will say "mode change". With the mode change, there will be a more subtle noise that uses spatial audio throughout the entire chart while the user is navigating the space. There will no longer be the more clear sounds as they navigate through the points until swiping left with 4 fingers once more to change the mode back.

## CSUN Bar Charts
There will be two bar charts from the CSUN_2024_DEMO app. Allergies is shown to be a stacked bar chart. Art Scores shows 3 bars side-by-side per category rather than being stacked.
- __Vibrations:__ The bar charts' vibration will change depending on what color bar the user is on, even if on a stacked bar chart, the vibration will still change with color.
- __TTS:__ TTS works very similarly to the scatter charts, where it will read out the text for the axis and the chart if their finger moves to the text. There are also bar titles that can be read out as well. The difference in the bar charts is that TTS will read out the y-axis values to the user as they drag their finger vertically through the graph.
- __Sound:__ In both bar graphs that are used in this application, a bell noise will play if the user moves off the TOP of the bar. The top of the graph is marked by a bolded line, and specifically in the stacked bar chart, TTS will read out which bar they are on by reading out "Allergy A" or "Allergy B" depending on where their finger moves to on the bar.

## LDV Line Chart
There will be one line chart from the LDV_User_Study_2024 app.
- __Vibrations:__ The goal of this chart is to start at one of the 3 lines on the left side of the chart, and to move one finger through the line and the intersections until it reaches its end. Each line has its own frequency at which it will vibrate, this is how the user will keep track of whether they are on the correct line or not.
- __TTS:__ TTS will work as it has with the other charts, the TTS will read out graph and axis titles. TTS will now also read out if the user is at an intersection and tell them which two lines have crossed if the user's finger is held down.
- __Mode:__ The number on the bottom left of the activity will change by swiping 2 fingers to the left. This is for keeping track of data in the csv file based on the line that the user would be moving through. The number on the bottom left will NOT change anything with the vibrations or TTS.
