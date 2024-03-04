

# Storyboard

### Steps for creating your first storyboard project in XCode

  * Open XCode and select *Create new project*
  * Then, under the iOS panel select *App* inside the application section
  * Now, give a Name to your project in the *Product name* field. In our case it is 'RandomColors'.
  * Select interface as *Storyboard* and language as *Swift*.
  * Now, click next, and choose a location where you want to save your project, and hit create.


### Cleaning the Project 
------------------------
 * Inside the Main.storyboard delete the iPhone screen that you see.
 * Next delete the ViewController.storyboard file from the files menu

### Creating a View Controller
------------------------------
 * Inside the *Main.storyboard* file click the ***+*** button in the top right corner or just press 'cmd+shift+l' and search for view controller, and drag and drop the *View controller*
 Note *All the view controllers in storyboard have to be connected to a file* 
 * In the Project folder create a new *Cococa Touch Class*. Shortcut key : 'cmd+n'. We are gonna name it 'ColorsTalbeVC' ,after that select 'UIViewController' as the *Subclass*, language as 'Swift'
 * To connect our *View controller* to the *ColorsTableVC.swift* file :
     * Click the 1st button on the top of View Controller
     * Then, inside the Identity selector, select the Class as *ColorsTableVC*

### Creating a Navigation Controller
------------------------------------
 * Inside the Main storyboard file Select the *View controller*, then click on the *Editor* option in the top bar Menu of the MacOS
 * Under the *Editor* menu select the *Embed In* option ,and then click on the  *Navigation Controller* option.


### Changing Background color of the View Controller
----------------------------------------------------
 * Move inside the ***Scenes*** menu and select the ***View*** for *ColorsTableVC*
 * After selecting the *View* go to the **Attributes Inspector** and change the **Background** of your choice.


    
