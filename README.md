# TarkBotExe
Executable for TarkBot

Source code @ https://github.com/midscreant/TarkBot

<--------------------->

INSTALLATION:

  Download all files from master branch and extract. 
  EXE file is located in /dist/tgui/tgui.exe
  Should be ready to go out of the box.
  Running the exe will open a cmd prompt as well as the GUI.

<--------------------->

RUNNING THE BOT:

-GUI Buttons

  As a general rule, inserting a value of -1 to sections will run them indefinitely (with the exception of "Checkup Freq")

  -Preset
  
    -Set and delete presets in the top left (select option, then click "Insert" or "Delete"
    -Create new presets by filling out full form then naming and saving the preset in the "Preset Name" section
    
  -Time
  
    -How long you want the bot to run for (n * 15min)
    - -1 input will run indefinitely
    
  -Checkup Freq
  
    -How long in between hideout checkups. A break in between full runs (n * 15min)
    
  -Path to BSGLauncher.exe
  
    -Needs this to boot game on software start
    
  -Checkboxes
  
    -Enable Inventory Quicksort: Once every full run, bot attempts to quicksort inventory to make room
    -Enable Insurance Checks: Checks Prapor and Therapist for insurance items to claim
    -Enable Flea Checks: Checks Ragman for money or items to claim from the flea
    -Enable Reboot Attempts: On encountering a fatal error, the program attempts to reboot itself and start from where it left off. Does this up to 2 times
    
  -Nodes
    
    If run count or selection is left blank, won't run that node. Need to select both to run it.
  
    -Generator: Amount of fuel cans you're willing to add to generator
    -Water: Amount of water filters you're willing to buy (max)
    -Booze: Amount of booze you want to produce
    
    -Scav: Scav Case selction & run count
    -Workbench: Workbench selction & run count
    -Intel: Intel selction & run count
    -Medstation: Medstation selction & run count
    -Lavatory: Lavatory selction & run count
    -Nutrition: Nutrition selction & run count
    
Once "Time", "Checkup Freq", "Path to BSGLauncher.exe" and at least 1 node activty filled out, you can press "Start"
This brings up a confirmation window with all of your choices
Once confirmed, DO NOT TOUCH THE MOUSE UNLESS YOU ARE READY TO KILL PROGRAM
Tarkov will boot on its own
I would recommend watching the bot until it successfully opens the hideout for the first time. Can get hung up if game takes too long to load and will need to be restarted

<--------------------->

FINAL NOTES

In the future, I plan on adding mobile control options
Considered adding a "Sell On Flea" function, but seemed like it may violate EFT TOS

If you run into any bugs, feel free to let me know. This is a WIP and I don't expect it to run flawlessly.
Discord: vluther123#8297

 ___  _, __, _,_ __,  _, ___
  |  /_\ |_) |_/ |_) / \  | 
  |  | | | \ | \ |_) \ /  | 
  ~  ~ ~ ~ ~ ~ ~ ~    ~   ~
    
<--------------------->

DEPENDENCIES

pytesseract, tesseract
opencv
pyautogui
pillow
    
