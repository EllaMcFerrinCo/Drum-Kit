# Drum Kit

A drum kit accessible in your web browser

![Image](/images/Screenshot.png)

## Structure

This game is made with:
- html
- css
- javascript

## Implementation

when the page is loaded 7 buttons are displayed\
when you press the image or the key corresponding to said image the sound of the instrument is played

How this works:
- using DOM to select all the elements with the .drum class
- adding the event listener click to those elements and calling the functions that make the sounds and cause the button animations
- below that is another dom that selects the drum elements by their class, but adds the keydown event listener instead
- the function that makes the sounds uses a switch statement to determine what sound to play based on what key you preseed
- the function that animates the buttons uses the DOM to select the active button and then adds the .pressed class which enables a white outline around the current active button

## How to run
1. Clone or download this repository
2. Open index.html file in your browser
3. Click on the buttons or press the keys corresponding to the buttons to make a sick beat