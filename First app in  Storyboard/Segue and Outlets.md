
# Using Segue in Navigation Controller

### Steps
  * Create a **View Controller** from the *View library* connect it to a class file in our case it is *ColorsDetailVC*.
  * Now, to connect the ColorsTableVC to ColorsDetailVC, go to the top bar of the ColorsTableVC's view controller and hold 'right-click' from the first button, and drag the segue onto the new view controller.

Note: If you select the 'Segue' connecting the Navigation Controller and the ColorsTableVC(Initial view controller) you will see it is 'Root relationship' segue

### Assigning an Identifier to the Segue
----------------------------------------
  * Select the segue and under the *attributes inspector* give a name in the **Identifier* field.

### Creating a button and action
--------------------------------
  * Open the view controler in a new window
  * Insert a new button in the ColorsTableVC
  * Drag a segue from the button to the newly opened View controller window. Notice, to end the segue after the ***viewDidLoad*** function.
    
Note : Ending the segue before the **viewDidLoad** function will create an ***Outlet***, whereas dropping it after the function will create an **Action**.

  * Upon dropping the segue below *viewDidLoad* a small window will pop-up to set the action.
  * Give a *name* in the action window, select type as **UIButton** and click on **Connect**. Doing that a chunk of code must appear after *viewDidLoad*
  * Now add ***performSegue*** function with identifier, inside the **action** function
  * Inside of the ***performSegue*** function we have to give an **Identifier** which we gave to the **Navigation Segue** previously.
  * Lastly set the **sender** parameter as *nil*.



NOTE ERROR : *'this class is not key value coding-compliant for the key'*
 If this error is encountered please check if the button has un-removed references left.
 For that right click on the button, and delete any unnecessary references.

##### Removing an Action
   * Deleting the **@IBAction** function code from the ViewController file won't fix things, we have to delete the button from ViewController UI or remove references by Right clicking the *button* ,and delete the events attatched with the button.
 

 
