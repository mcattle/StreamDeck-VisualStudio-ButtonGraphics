# Elgato Stream Deck Button Images for Visual Studio

These are button images for Visual Studio control with an Elgato Stream Deck

[/raw-graphics](./raw-graphics) contains svg icons from the [Visual Studio 2017 Image Library](https://www.microsoft.com/en-us/download/details.aspx?id=35825) pre-rendered as PNG images to the below specifications.

[/visualstudio-commands](./visualstudio-commands) contains button images extracted from the rendered raw-graphics and renamed to match the appropriate Visual Studio command.

## Button image specifications:

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
