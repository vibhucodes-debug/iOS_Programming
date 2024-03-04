
# Using Segue in Navigation Controller

### Steps
  * Create a **View Controller*** from the *View library* connect it to a class file in our case it is *ColorsDetailVC*.
  * Now, to connect the ColorsTableVC to ColorsDetailVC, go to the top bar of the ColorsTableVC's view controller and hold 'right-click' from the first button, and drag the segue onto the new view controller.

Note: If you select the 'Segue' connecting the Navigation Controller and the ColorsTableVC(Initial view controller) you will see it is 'Root relationship' segue

### Assigning an Identifier to the Segue
--
  * Select the segue and under the *attributes inspector* give a name in the **Identifier* field.

### Creating a button and action
--
  * Open the view controler in a new window
  * Insert a new button in the ColorsTableVC
  * Drag a segue from the button to the newly opened View controller window. Notice, to end the segue after the ***viewDidLoad*** function.
    
Note : Ending the segue before the **viewDidLoad** function will create an ***Outlet***, whereas dropping it after the function will create an **Action**.



