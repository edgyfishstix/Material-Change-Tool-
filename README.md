*More readable version provided in folder*

Hello, thank you for downloading the Material Change Tool v. 1.0 (MCT)! 

My name is Hayden Linden, the original creator of the Material Change Tool (please credit when sharing publicly). I believe in making resources and education as accessible as possible, so customization is highly encouraged. Please email haydenlinden1@gmail.com for any accessibility concerns. The base UI code is also provided as a plain text file for phone editing. This script currently isn’t and will not be monetized as it’s intended to stay open source. Anyone charging money for this tool is a scammer and should be ignored. It will always be free. 

With all of that said:

MCT is meant to be a modular and  customizable tool that’s easy for artists to use. This tool is compatible with any Maya experience level. Follow all directions closely in order to get maximum use out of this program, including editing tips about how to customize properly. Compatible with Maya 2022 and later.

—————————————————————
Installation

In order to install the MCT, you need the following files:
node_network_base_setup - Copy.mb 
MCT_UI.mel
MCT_icon.png



Open up your file in Maya that you intend to use this editor in.
 Open up your script editor (the  icon in the bottom right corner of the screen OR Windows > General Editors > Script Editor). 
Open the “MCT_UI.mel” file by double clicking it like you would a word document.
Copy the text and paste it in the Maya script editor (make sure your tab is set to “MEL”). 
In the editor, go to File > Save Script to Shelf. Save the icon as whatever name you want to a shelf for fast access.
Click this icon to access the Material Change Tool interface.
(optional) To change the icon to the uploaded MEL_Icon.png file, go to the gear icon in the shelf, then click “edit shelf”. On the right hand side, make sure your shelf label is there. In the “icon name” field, open up the source of the icon file you wish to use, then click “save all shelves”. 

Upon clicking, the interface features 2 windows: The MCT Importer, as well as the Material Quick Changer main window. 

To finish installation, click the “Import Material Base Code” button in the MCT Importer window. Import the file named “node_network_base_setup - Copy.mb”. If you haven’t downloaded it, now is the time to do so, or the script won’t work. This file is a material library arrangement that was made via the node editor**. Close out of the MCT Importer permanently since it’s a one time use, as indicated by the blacked out color it takes on once clicked. The MCT is now ready to use! 
Warning: importing the node network more than once will cause issues. Exit out of the file without saving to reset it, as deletion doesn’t clear it completely. Do not rename the base file, as the code will be rendered useless. 
**Editing Tip: It’s viewable upon finding the “node_network_base_setup___copy:lambert_base” material via either Hypershade or the outliner (uncheck “DAG objects only” to find it this way). Use the network to customize material type. The default is lambert.  

—————————————————————

MCT UI: How to Use

The Material Quick Changer window has the following drop downs, from top to bottom (buttons in italics):
Base Material Placement / Apply Base Material to Geometry
Material Showcase / Materials 1-8 
Material Sourcer / Mat. 1-8 Source

Select your geometry, then click the “Apply Base Material to Geometry” button in the Base Material Placement drop down in order to place the base material that’s hooked up to the node network you imported earlier**. 

**Editing tip: By default, you’re provided 8 materials that you are free to edit. Some connections may come undone when changing the material type (I.e. lambert to standardSurface). Place the “node_network_base_setup___copy:lambert_base” material in the node editor via dragging it from the outliner. Click the  icon to view all inputs and outputs of the base color. Click the same button on the various lambert materials to see their connections (good to refer to when changing material types, I’d suggest adding a new tab in the node editor and doing this and leave the lambert base on the first tab). 


The Material Showcase drop down is used to preview different materials with the click of a button. Names of materials must be either kept in tact as imported or edited in the script as well**.

**Editing Tip: when changing the names of materials, copy the new name. Right click the icon you made on your shelf and click “edit script”. Go to wherever the current material name is ( usually by the -c flag adjacent to the button command), highlight the old name, and paste the new one in its place. Make sure they are inside quotes so the program reads it as a script. The material button name can be changed here as well. Keep in mind that all of this must be done every time you change the name, so choose one and stick with it. 


The Material Sourcer drop down is used to select each material so it can be viewed in the attribute editor or ready to add in Hypershade for more complex editing (you still need to click the  button to officially add it for the Hypershade route). Sources 1 - 8 are in the same exact order from left to right as the Material Showcase buttons, as both button sets reference the same root material. 
