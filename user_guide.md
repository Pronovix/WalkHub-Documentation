**'How to' guides:**

[Recording a Walkthrough](#Recording_a_Walkthrough)   
[Adding Step descriptions](#Adding_Step_descriptions)   
[Moving a Walkthrough Step bubble](#Moving_a_Walkthrough_Step_bubble)   
[Changing the Action of a Walkthrough Step](#Changing_the_Action_of_a_Walkthrough_Step)   
[Manually changing the Steps in a Walkthrough](#Manually_changing_the_Steps_in_a_Walkthrough)   
[Configuring the parameters of a Walkthrough](#Configuring_the_parameters_of_a_Walkthrough)   
[Playing Walkthroughs](#Playing_Walkthroughs)   
[Playing a Walkthrough on a different site](#Playing_a_Walkthrough_on_a_different_site)   
[Sharing Walkthroughs](#Sharing_Walkthroughs)   
[Exporting a Walkthrough](#Exporting_a_Walkthrough)   


**Using Selenium to record Walkthroughs:**

[Installing Selenium IDE](#Installing_Selenium_IDE)   
[Recording Selenium tests](#Recording_Selenium_tests)   
[Creating Walkthroughs from a Selenium test](#Creating_Walkthroughs_from_a_Selenium_test)   


**References:**

[Supported Selenium commands](#Supported_Selenium_commands)   
[Supported Step highlights](#Supported_Step_highlights)   



## <a name="Recording_a_Walkthrough">Recording a Walkthrough</a>

The easiest way to record a Walkthrough is to use WalkHub's built-in recorder. (You have to be logged in for this.)


1. To record a Walkthrough, click the red REC button on the top right of your screen. 
2. A pop-up is displayed. Enter the URL of the website you'd like to record your Walkthrough on.
3. Click REC.
4. Click through the page. The red frames show you where you can add a Walkthrough step.
5. When you're done with recording close the Recorder window. 
6. A pop-up is displayed. Enter the title of your Walkthrough and select how much your Walkthrough changes the site it is played on. You have three options: doesn't change it, changes content or changes configuration. This setting will help warn users to only play the Walkthrough on sites where the changes won't cause any issues. 
7. Click "Save". If you decided not to save your Walkthrough and start a new recording, click "Delete, and start a new recording". 




<div class="wt-container">
  <iframe id="walkthrough-slideshow-iframe" frameborder="0" width="400" height="300" src="http://walkhub.net/walkthrough/6764/slideshow" allowfullscreen=""> Your browser doesn't support iframes.</iframe>
</div>



## <a name="Adding_Step_descriptions">Adding Step descriptions</a>

After recording your Walkthrough, you can simply play it and add Step descriptions on the fly.

1. Click "Start Walkthrough" to play the Walkthrough you recorded. The Step bubbles are automatically pre-filled with text based on the action of the Step.
2. Click "Edit" on a Step to edit it.
3. Add a Step description.
4. If your Walkthrough is tour-like, add a title as well. (Optional). If you want to display Step titles, check the Show title checkbox.
5. Click "Save", and continue editing Steps by going through your Walkthrough.

 
## <a name="Moving_a_Walkthrough_Step_bubble">Moving a Walkthrough Step bubble</a>

You can move a Step without recording the Walkthrough again.

1. Click "Start Walkthrough" to play the Walkthrough you recorded.
2. Click "Edit" on a Step to edit it.
3. Click "Move" and select where you want to move this Step with the red frame.
4. Click "Save".

 
## <a name="Changing_the_Action_of_a_Walkthrough_Step">Changing the Action of a Walkthrough Step</a>

1. Click "Start Walkthrough" to play the Walkthrough you recorded.
2. Click "Edit" on a Step to edit it.
3. Click "Advanced settings".
4. Select the action from the "Action" drop-down. See what each action does in the Supported Selenium commands section.
5. Click "Save".


## <a name="Manually_changing_the_Steps_in_a_Walkthrough">Manually changing the Steps in a Walkthrough</a>

It is possible to manually add or remove Steps from a Walkthrough, and to change their order.

1. Open the Edit form for the Walkthrough you want to change. You can do so by clicking the Edit tab for any Walkthrough you have the permissions for.
2. Scroll down to the list of Steps.
3. Edit the Steps:
* To remove a Step: Click on a Step to open its Edit block and click on Remove.
* To add a Step: Click on the "Add another item" button under the steps list. Click on the newly added Step and fill in its Edit form.
* To move a step: Grab a Step by the double-arrow icon in front of it, and drag it to the desired position.
4. Save the form when finished editing.

 
Please play these Walktroughs on Walkthroughs you created to be able to access them. 

<div class="wt-container">
  <iframe id="walkthrough-slideshow-iframe" frameborder="0" width="400" height="300" src="http://walkhub.net/walkthrough/3780/slideshow" allowfullscreen=""> Your browser doesn't support iframes.</iframe>
</div>

<div class="wt-container">
  <iframe id="walkthrough-slideshow-iframe" frameborder="0" width="400" height="300" src="http://walkhub.net/walkthrough/3782/slideshow" allowfullscreen=""> Your browser doesn't support iframes.</iframe>
</div>


## <a name="Configuring_the_parameters_of_a_Walkthrough">Configuring the parameters of a Walkthrough</a>

Parameters make it easy for people to reuse an existing Walkthrough. Under the "Parameters/Proxy Warning" section (by default collapsed) it is possible to manually add or remove parameters for Walkthroughs and to configure their default values.

1. Open the edit form for the Walkthrough you want to change. You can do so by clicking the "Edit" button for any Walkthrough you have the permissions for.
2. Click on "Parameters/Proxy Warning" to open the hidden fieldset that contains the parameters.
3. Edit the parameters: For parameters to be recognised, you have to add the parameter name in square brackets while recording the Selenium steps, for example: [name], then add the parameter name on the Walkthrough edit form without the square brackets, for example: name.
* To remove a parameter: Click the remove button under the parameter.
* To add a parameter: Click on the "Add another item" button under the parameter list.
4. Enter your preferred default value for the parameters.
5. Save the form when finished editing.

**Tips**


* You can use parameters for any arbitrary variable information you want to insert into your Walkthrough.
* You can use parameters in the share url functionality to pass information about a user to WalkHub (e.g. name, information you want to automatically add to their form submission, etc.)

 
Please play this Walktrough on a Walkthrough you created to be able to access it.

<div class="wt-container">
  <iframe id="walkthrough-slideshow-iframe" frameborder="0" width="400" height="300" src="http://walkhub.net/walkthrough/3570/slideshow" allowfullscreen=""> Your browser doesn't support iframes.</iframe>
</div>



## <a name="Playing_Walkthroughs">Playing Walkthroughs</a>

Walkthroughs are stored and played from a WalkHub (this could be WalkHub.net, your own dedicated WalkHub or your Drupal site on which you have enabled the WalkHub module).

1. Open the Walkthrough you want to run.
2. Click on the "Start Walkthrough" link to open the "Start Walkthrough dialogue".
3. Review the Walkthrough parameters in the dialogue and if necessary replace their default values.
4. Click on the "Start Walkthrough" link in the dialogue
5. The Walkthrough will open.
6. At any time you can click the [x] at the top right of the window to close the Walkthrough and to return to the Walkthrough page.

<div class="wt-container">
  <iframe id="walkthrough-slideshow-iframe" frameborder="0" width="400" height="300" src="http://walkhub.net/walkthrough/3770/slideshow" allowfullscreen=""> Your browser doesn't support iframes.</iframe>
</div>

## <a name="Playing_a_Walkthrough_on_a_different_site">Playing a Walkthrough on a different site</a>

You can play the same Walkthrough on different sites as long as they have the same structure.

1. Click on the "Start Walkthrough" link to open the "Start Walkthrough dialogue".
2. Change the URL in the Domain field to the site you want to play the Walkthrough on.
3. When you click the "Start Walkthrough" button, the Walkthrough will be played on the site you specified.

<div class="wt-container">
  <iframe id="walkthrough-slideshow-iframe" frameborder="0" width="400" height="300" src="http://walkhub.net/walkthrough/3777/slideshow" allowfullscreen=""> Your browser doesn't support iframes.</iframe>
</div>

## <a name="Sharing_Walkthroughs">Sharing Walkthroughs</a>

WalkHub makes it easy to create hyperlinks that will launch a Walkthrough with your preferred parameters already pre-filled in the launch dialogue.

1. Open the Walkthrough you want to share.
2. Click on the "Start Walkthrough" link to open the "Start Walkthrough dialogue".
3. Review the Walkthrough parameters in the dialogue and if necessary replace their default values.
4. In the "Share with these parameters" text area, the parameters in the share URL will automatically be changed to match the values you change.
5. Copy the URL in the "Share with these parameters" text area.

You can also share a Walkthrough by playing it to the end and clicking the corresponding buttons to share it

* on Twitter
* on Facebook
* on Google+
* in email

<div class="wt-container">
  <iframe id="walkthrough-slideshow-iframe" frameborder="0" width="400" height="300" src="http://walkhub.net/walkthrough/3771/slideshow" allowfullscreen=""> Your browser doesn't support iframes.</iframe>
</div>

## <a name="Exporting_a_Walkthrough">Exporting a Walkthrough</a>

You can export a Walkthrough to PHPUnit or Selenium.

Exporting to PHPUnit:

1. Click "Export to phpunit" on any Walkthrough you have the permissions for.
2. The code will appear in a new window where you can copy it.

Exporting to Selenium:

1. Click "Export to Selenium" on any Walkthrough you have the permissions for.
2. A save dialog window will appear where you can download the Selenium source code in html format, that you can import to Selenium IDE (copy the html file source and paste into the Selenium source). 

## <a name="Installing_Selenium_IDE">Installing Selenium IDE</a>

Selenium IDE is a Firefox plugin that can record and playback interactions with a browser. WalkHub can turn Selenium tests into Walkthroughs.

1. Using Firefox, first, download the IDE from the SeleniumHQ [downloads page](http://docs.seleniumhq.org/download/).
2. Firefox will protect you from installing add-ons from unfamiliar locations, so you will need to click ‘Allow’ to proceed with the installation.
3. Select Install Now. The Firefox Add-ons window pops up, first showing a progress bar, and when the download is complete, asks you to restart Firefox.
4. Restart Firefox.
5. To run the Selenium-IDE, simply select it from the Firefox Tools menu. It opens with an empty script-editing window and a menu for loading, or creating new test cases.

Selenium IDE only exists as a Firefox plugin, you can install Firefox from [its website](https://www.mozilla.org/en-US/firefox/new/).

If you need a more thorough explanation, follow the steps [here](http://docs.seleniumhq.org/docs/02_selenium_ide.jsp) to install Selenium IDE for your browser.


<div class="wt-container">
  <iframe id="walkthrough-slideshow-iframe" frameborder="0" width="400" height="300" src="http://walkhub.net/walkthrough/3779/slideshow" allowfullscreen=""> Your browser doesn't support iframes.</iframe>
</div>


## <a name="Recording_Selenium_tests">Recording Selenium tests</a>

To create a Selenium test you can simply record your interactions with a website using a tool like Selenium IDE.

1. In Firefox open Selenium IDE under the Tools menu item
2. Create a new test case (Right click on the test case list and select "New Test Case")
3. Make sure the record button is turned ON
4. Type the URL where you want to record the interaction sequence for your Walkthrough.
5. Perform the actions you want your Walkthrough users to perform with example data. Selenium-IDE will automatically insert commands into your test case based on your actions.
6. Copy the source of the test case you have just created to your clipboard. You will later paste this into the "Create from Selenium test" field on the walkthrough creation form.
7. Optionally you can store your test case as an HTML file in Selenium IDE.

**Important**

* Don't skip the 3rd step, even if you are already on the right page, else the Walkthrough you generate won't work!
* Don't use confidential data like usernames and passwords, unless you are planning to share them with anyone who will be playing your Walkthrough.


## <a name="Creating_Walkthroughs_from_a_Selenium_test">Creating Walkthroughs from a Selenium test</a>

Walkthroughs are created as content on a WalkHub. You can use a Selenium test to automatically create steps and example actions for your Walkthrough.

1. Log in to Walkhub.net
2. Open the Import Walkthrough form. On WalkHub.net you can find it under the "Add content" menu.
3. Paste the source of a Selenium test (recommended). You should have copied it to your clipboard in the Recording Selenium Tests Task.
4. Give your Walkthrough a name (required).
5. Add a description (recommended).
6. Click save to save the Walkthrough.
7. After saving the walkthrough, click on the "Start Walkthrough" link (first on the Walkthrough page and a second time on the Start Walkthrough dialogue) to verify if your Selenium test was imported correctly.
8. For each step click on the Edit button and replace the automatically generated title with a title of the Step if needed. Otherwise only add a description.

<div class="wt-container">
  <iframe id="walkthrough-slideshow-iframe" frameborder="0" width="400" height="300" src="http://walkhub.net/walkthrough/3559/slideshow" allowfullscreen=""> Your browser doesn't support iframes.</iframe>
</div>

## <a name="Supported_Selenium_commands">Supported Selenium commands</a>

WalkHub currently only supports the most common Selenium commands. You can use them to trigger an automatic action when a user clicks the next button on a Walkthrough Step.

**Step without commands**

It is possible to create a step that does not contain any commands. In this case the Walkthrough will display the Step on the element indicated in the "Step highlight" field but it won't perform any actions when the "next" button is clicked.

**Open**

Example Step Selenium commands:

* Command 1: open
* Command 2: http://[domain]
* Command 3:

Every Walkthrough needs to start with a step with an open command, else a Walkthrough will not start. Notice that command 2 contains a domain parameter, that will be replaced with it's default value or another value selected by the Walkthrough user.

**Click**

Example Step Selenium commands:

* Command 1: click
* Command 2: link=Show Advanced settings
* Command 3:

This command is also used to toggle checkboxes and radio buttons.

**ClickAndWait**

Example Step Selenium commands:

* Command 1: ClickAndWait
* Command 2: link=Walkthrough
* Command 3:

This command is used when the browser needs to load a new page after a link/button is clicked.

**Type**

Example Step Selenium commands:

* Command 1: Type
* Command 2: id=edit-body-und-0-value
* Command 3: A walkthrough that creates a walkthrough that creates walkthroughs

**Select**

example Step Selenium commands:

* Command 1: select
* Command 2: id=edit-timezone--2
* Command 3: label=Australia/Melbourne: Wednesday, August 7, 2013 - 07:41 +1000


## <a name="Supported_Step_highlights">Supported Step highlights</a>

WalkHub uses the Selenium selector naming conventions to define on what element the Step dialogue will be shown on.

**Steps without "Step highlight"**

The "open" Step at the beginning of a Walkthrough does not contain a Step highlight. Instead the Walkthrough executes the open command automatically and does not wait for user feedback.

**link=**

Link is used to identify hyperlinks. This is a very commonly used selector strategy in Selenium with the disadvantage that the Walkthrough will look for the first instance of a link that contains the link title and click that link. This is a known issue and we are working on a solution to make this more robust.

Example Step highlight: link=Walkthrough

**id=**

id is used to identify an element with a specified CSS id. This is commonly used for the type Selenium command.

Example Step highlight: id=edit-title

**xpath=**

When Selenium IDE can't uniquely identify an element with any of it's other selector strategies, it creates an xpath selector. This is often not very robust.

Example Step highlight: xpath=(//button[@type='button'])[3]



