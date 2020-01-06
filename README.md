# Elgato Stream Deck Button Images for Visual Studio

These are button images for Visual Studio control with an Elgato Stream Deck

Button image specifications:

* The button image files MUST:
  * Have a 72 x 72 resolution
  
* The button image files SHOULD:
  * Be in PNG format with transparent background
  * Have the bottom 18 rows of pixels left blank for button Title Text
  * Leave 12 columns of pixels on the left and right and 6 rows of pixels on the top blank for conformity
  * Have a file name that matches the Visual Studio command text, for ease of installation
  
* The command icons within the button image files SHOULD:
  * Be a 48 x 48 image within the above image file, after margins are accounted for

To use these icons in your Stream Deck:
1. Download or save the images from this repository
1. In the Stream Deck application:
   1. Install the **Visual Studio 2017 & 2019** actions (**More Actions...** button)
   1. Select the **Visual Studio -> Execute Command** action for a button
   1. Set the button image from the appropriate file
   1. Set the Command Name to match the image

Tips:
* Use the [Command Explorer](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.commandexplorer) Visual Studio extension to extract command names.
