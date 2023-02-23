# KControls
These a bunch of components made for Java Swing to beautify user interfaces and give UI’s a modern look. They include :
* KButton
* KKGradientPanel
* Frame Resize and Move Utility

![Example](https://github.com/k33ptoo/KControls/blob/master/images/demo.gif)
 
How to install KControl(s)
 - Download jar [file](https://github.com/rayanhcm2/KControls/blob/main/KControls/dist/KControls-2.0.jar)
 - Open Netbeans Create your Swing application, head to Palette right
   click and select Palette Manager select Add from Jar and browse to
   the location of the downloaded jar file.
 - Select and proceed, select KControls [KButton, KGradientPanel.. ]
   components proceed to select the category and hit Finish.
 - Open your JFrame drag KGradientPanel/KButton to it and set the
   properties in the properties window.

Add your components to your code as described here

Note: Custom properties starts with K eg KStartColor


## 1. KButton

KButton is an extended version of JButton – it has basically everything else a JButton has, that said we will look only the custom properties.
  ![Example](https://github.com/k33ptoo/KControls/blob/master/images/kbutton.png)

Custom Properties

 - **kAllowGradient(Boolean)**
      Enables or disables gradient property of the button.
 -  **kBackgroundColor(Color)**
Gets or sets the background color of the button.
 - **kBorderRadius(int)**
       Gets or sets the radius of a button (recommended 0 to 30).
 - **kEndColor(Color)**
Gets or sets the button’s gradient end color to the right.
 - **kFillButton(boolean)**
Allows the button to be filled or not with color/gradient
 - **kForeGround(Color)**
Gets or sets the component’s label.
 - **kHoverColor(Color)**
Gets or sets the color of the control when a mouse is hovered over it.
 - **kHoverEndColor(Color)**
Gets or sets the button’s gradient end color when it receives a mouse hover event.
 - **kHoverForeGround(Color)**
Gets or sets the button’s label color when it receives a mouse hover event.
 - **kHoverStartColor(Color)**
Gets or sets the button’s gradient start color when it receives a mouse hover event.
 - **kPressedColor(Color)**
Gets or sets the button’s color when it receives a mouse click event.
 - **kStartcolor(Color)**
Gets or sets the button’s gradient end color to the left.
 - **kAllowTab(boolean)**
Gets or sets the button’s tab property by making kButtons have a tab–like feature.
 - **kIndicatorColor(Color)**
Gets or sets the button’s indicator color.
 - **kIndicatorThickness(int)**
Gets or sets the button’s indicator thickness.

## States & Properties	
(Properties to watch out for quicker UI designing)
## Hover State

 - **kHoverColor(Color)**
 - **kHoverEndColor(Color)**
 - **kHoverForeGround(Color)**
 - **kHoverStartColor(Color**

## Normal State

 - **kAllowGradient(Boolean)**
 - **kBackgroundColor(Color)**
 - **kAllowTab(Boolean)**
 - **kBorderRadius(int)**
 - **kEndColor(Color)**
 - **kFillButton(boolean)**
 - **kForeGround(Color)**
 - **kStartColor(Color)**
 - **kPressedColor(Color)**

## 2.	KGradientPanel
This is an extended version of JPanel with awesome gradient effect. 
Custom properties
![Example](https://github.com/k33ptoo/KControls/blob/master/images/gradient.png)
 - **kEndColor(Color)**
Gets or sets the button’s gradient end color to the right.
 - **kGradientFocus(int)**
Gets or sets the location to which the gradient should focus (accepts negative value)
 - **kStartcolor(Color)**
Gets or sets the button’s gradient end color to the left.
 - **kBorderRadius(int)**
Gets or sets the radius of a KGradientPanel(recommended 0 to 30).

## Frame Resize and Move Utility

Download Jar [Here](https://github.com/rayanhcm2/KControls/blob/main/KControls/dist/KControls-2.0.jar)
Thank you.
