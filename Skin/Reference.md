# Reference.md

## Outline of Reference

 1. Definition of Terms in Reference
 2. How to set up a Javafx Project with the CIRDLES Style
 	1. list of needed Resources
 	2. implement resources in javafx project
 3. How to implement specific components in JavaFX projects with CIRDLES Style
 4. Primitive & Complex Components
 	* Primitive Components
 	* Complex Components

### 1. Definition of Terms in Reference

 css: refers to JavaFX css. The documentation of which can be found [here](http://docs.oracle.com/javafx/2/api/javafx/scene/doc-files/cssref.html)

 components: any user interface object. Components can be containers or controllers. They can also be primitive or complex.

 Container Component: holds other components, used for laying out other components.

 Controller Component: UI objects with which the user interacts with.

 Primitive Components: JavaFX Controller and Container components which do not need to be assigned any css classes to be a CIRDLES standard UI object.

 Complex Component: pre arranged collection of javafx UI components and/or containers of primitive components.

### 2. How to Set up a JavaFx Project with the CIRDLES Style

#### Needed Resources

 * The fxml folder and CIRDLES.css file found here in the DRAKE repo. __ TODO __ link to resources

#### Setting up JavaFx Project

 1. Save a copy of the CIRDLES.css file in the project
 2. Set the style of the project
    1. Programmatically
        * in start method for application, set the scene's style sheet to CIRDLES.css.

        ```
          public class Main extends Application {
            @Override
            public void start(Stage primaryStage) throws  Exception{
              ...
            scene.getStylesheets().add("CIRDLES.css");
              ...

            }
        ```
      2. Scene Builder
        * in Scene Builder, have the root pane selected
        * in the Properties panel, find the JavaFX CSS section
        * click the + button and navigate to your project
        * in your project, find the copy of CIRDLES.css and select it.
        * confirm your selection



### 3. How to impl specific styles to components in JavaFX projects with CIRDLES Style

* set the style of the component you wish to modify to the class name of the style.

### 4. Glossary of Primitive & Complex Components

#### Glossary of Components

* __ TODO __ write when to use what, and any notes about that component
##### Controls / User Interaction Components
strike out components have no preview
* Button
    * used to start an action or acknowledge an alert
    * __Not used__ as hyperlinks,
    * ![alt text][Button]
* CheckBox
    * use when there are multiple true or false options from a set.
    * ![alt text][CheckBox]
* ChoiceBox
    * toggles some state of one option of the list on.
    * ![alt text][]
* ComboBox
    * allows user to select and search from one or more items from a drop-down list or box list.
* DatePicker
    * used to get some date value from the user
* Hyperlink
    * used to send the user to some webpage in a browser
    * ![alt text][Hyperlink]
* Label
    * Typeface used is Lucida Sans
    * used to display text to a user,
    * ![alt text][Label]
* MenuBar
    * a collection of functions separated into drop down lists
    * ![alt text][MenuBar]
* MenuButton
    * a button which drops down to reveal more options.
* PasswordField
    * a textfield but the user's entered text is concealed as dots
    * ![alt text][PasswordField]
* ProgressBar
    * a bar which becomes more full as some task is completed
* ProgressIndicator
    * a icon which becomes more full as some task is completed
    * ![alt text][ProgressBar]
* RadioButton
    * used when the user can select 0 or exactly 1 option from a set.
    * ![alt text][RadioButton]
* Slider (Horizontal and Vertical)
    * used to get numerical data in some finite range from the user
    * tick marks and intervals can be visible or not  
    * ![alt text][Slider]
* Spinner
    * allows users to iterate and select some value via a text box and two small buttons
* SplitMenuButton
* TableView
    * displays a table to the user
* TextArea
    * used to get multiple lines of text from the user
    * ![alt text][TextArea]
* TextField
    * used to get one line of text from the user
    * ![alt text][TextField]
* ToggleButton
    * toggles some state of some option
* ~~ TableColumn ~~
* ~~ TreeTableColumn ~~
* ~~ TreeTableView ~~
* ~~ TreeView ~~
* ~~ WebView ~~
* ~~ MediaView ~~
* ~~ HTML Editor ~~
* ~~ Imageview ~~
    * used to display an image to the user
* ~~ Pagination ~~
    * used to navigate between multiple pages of content
* ~~ Separator (Horizontal and Vertical) ~~
    * used to separate unrelated component groups
* ~~ ListView ~~
    * displays ordered or unordered data to the user
* ~~ ScrollBar (Horizontal and Vertical) ~~
* ~~ ColorPicker ~~
    * used to get some color value from the user


#### Glossary of Attributes of Components

* __ TODO __ write glossary of Attributes.
* attribute name, used on what components, example


[Button]: imgs/button.png "Enabled and Disabled Buttons"
[CheckBox]: imgs/checkbox.png "Enabled and Disabled CheckBoxes"
[ChoiceBox]:
[ColorPicker]:
[ComboBox]:
[DatePicker]:
[Hyperlink]: imgs/hyperlink.png "Example of Hyperlink"
[Label]: imgs/label.png "Example of Label"
[MenuBar]: imgs/menubar.png "Example of MenuBar"
[MenuButton]:
[Pagination]:
[PasswordField]: imgs/passwordfield.png "Enabled and Disabled PasswordField"
[ProgressBar]: imgs/progress.png "ProgressBar ( left ) and ProgressIndicator ( right )"
[RadioButton]: imgs/radiobutton.png "Enabled and Disabled RadioButtons"
[Slider]: imgs/slider.png "Enabled and Disabled Slider"
[Spinner]:
[SplitMenuButton]:
[TableView]:
[TextArea]: imgs/textarea.png "Enabled and Disabled TextArea"
[TextField]: imgs/textfield.png "Enabled and Disabled TextField"
[ToggleButton]:
