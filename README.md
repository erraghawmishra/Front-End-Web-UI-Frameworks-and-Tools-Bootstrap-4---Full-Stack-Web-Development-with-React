# Full-Stack-Web-Development-with-React---Front-End-Web-UI-Frameworks-and-Tools-Bootstrap-4
Full-Stack Web Development with React:- Front-End Web UI Frameworks and Tools: Bootstrap 4 by The Hong Kong University of Science and Technology
<h2>Assignment 1: Bootstrap and Responsive Design</h2>
InstructionsMy submissionDiscussions
In this assignment you will add a second page, aboutus.html, to your website. You will make use of the Bootstrap skills learnt in this module to prepare this web page for integration into the website.

Assignment Resources

aboutus.html.zip
Objectives and Outcomes

In this assignment, you will continue to work with the website that you have been developing in the exercises. You will add the About Us web page to the website. To get you started, you are provided with a partially formatted aboutus.html.zip file given above that you need to download, unzip and move the aboutus.html to the conFusion folder that contains your website. At the end of this assignment, you should have completed the following tasks:

Updated the page to make use of Bootstrap classes and Bootstrap grid
Formatted the contents of the web page using the container, row and column classes
Use the responsive utilities (hidden-* classes) to enable hiding of the detailed descriptions in the extra small screen size devices
Assignment Requirements

This assignment requires you to complete the following tasks. Detailed instructions for each task are given below. The picture of the completed web page included below indicates the location within the web page that will be updated by the three tasks.

Task 1

In this task you will be updating the aboutus.html page to make use of the Bootstrap classes and components:

Update the page to make use of the Bootstrap CSS classes.
Update the page to also use your custom styles defined in your styles.css file, and
Update the page to make use of all the Bootstrap JS components.
Task 2

In this task you will be adding appropriate formatting to the web page contents using container, row and column classes using the Bootstrap grid so that the web page is formatted to look like the figure given below. 

The "About Us" title should stretch the entire width of the row. 
The "Our History" part should occupy only half the width of the row for small to extra large screens, leaving space on the right side for more content to be added later. The content should be stacked for extra small screens.
The "Corporate Leadership" section should stretch the entire width of the row.

Task 3

In this task you will use some responsive utilities provided by Bootstrap to hide some of the content only for extra small screens. You will make use of the d-none and d-sm-block CSS classes provided by Bootstrap. To understand how to use these classes, please read the documentation here (in particular see how the combination of classes shown here enables you to hide the content for xs screen sizes) to learn how to apply the d-none and d-sm-block classes. This will get you into the habit of consulting the Bootstrap documentation whenever you need to learn more about the various components and classes of Bootstrap. You should apply the classes so that the <p> elements containing the detailed descriptions of the corporate leadership is hidden only for extra small screens. Thus, your page should look like the figure below on extra small screens.


More details about the d-none and d-sm-block CSS  classes can be found at http://getbootstrap.com/docs/4.0/utilities/display/.

While you are at it, please also apply the same classes to the descriptions in the index.html page. This is not part of the assignment, but should be completed to update your website.

Review criteria
less 
Upon completion of the assignment, your submission will be reviewed based on the following criteria:

Task 1:

The page is update to correctly use the Bootstrap CSS classes
The page is updated correctly to use the custom CSS classes from styles.css
The page has been updated to use the all the necessary JavaScript classes
Task 2:

The container class has been applied to the content at the correct location.
Row class, including the row-content class has been applied to the rows of the content. Do not apply row-content to the row containing the page heading
Column classes have been appropriately applied to the content within each row to provide responsive layout of the content.
Task 3:

The d-none and d-sm-block classes are correctly applied to the content in the Corporate Leadership section to hide the detailed description of the corporate leaders.
You are required to include two full-page screenshots of your completed web pages, one for normal screen size, and one for extra small screens. To take a full-page screenshot of your page use the Chrome extension: Full Page Screen Capture.
  
 <h2>Assignment 2: Bootstrap CSS Components</h3>
 InstructionsMy submissionDiscussions
Objectives and Outcomes

In this assignment, you will continue to work with the website that you have been developing in the exercises. You will edit the home page (index.html). You will start with the current home page at the end of the last exercise in this module. At the end of this assignment, you should have completed the following tasks:

Designed a form to enable users to submit a reservation request for a table. Note that at this stage the form will be inactive. This form should have been included in a new content row that you create just before the footer of the page.
Formatted the contents of the second row of the page using media class. The content column of the row should have been converted to a media object. In addition it should include a badge.
Added a button to the Jumbotron to enable users to access the form to reserve a table at the restaurant. Clicking on this button should take you to the reservation form at the bottom of the page.
Assignment and Requirements

This assignment requires you to complete the following three tasks. Detailed instructions for each task are given below. The picture of the completed web page included below indicates the location within the web page that will be updated by the three tasks.

Task 1

In this task you will be adding another content row to the page. The content row should contain the following:

You should create a reservation form for the user to reserve a table. The reservation form should contain a field using radio that enables the users to specify the number of guests (1-6).
The form should contain fields to specify the date and time of the reservation. The fields should contain appropriate placeholder information to identify the purpose of the fields.
The form should contain a button named Reserve to initiate reservation of the table.
The form should be enclosed inside a card with the heading "Reserve a Table". The card should occupy 8 columns and centred in the row for small to extra-large screens. For extra-small screens, the card should span the entire row.
Task 2

In this task you will be formatting the content in the second row of the page. The formatting should result in the following:

Format the content of the second column with the media class together with the media object class. Use the buffet.png image file provided for you in the img folder. The image should displayed to the right of the content description. See figure below.
Add a badge with the word “NEW” to the content as shown in the figure below.
Task 3

In this task you will be adding a block-sized button to the Jumbotron to the right of the restaurant logo:

The block-level button and the restaurant logo should share the right six columns of the row. The restaurant name and description can now be reduced to occupy the left six columns. Use the small button (btn-sm).
Clicking on the button should take you down to the form for reserving a table.


Submission

You should submit the updated index.html file with all the tasks completed. A reviewer should easily be able to take your file and substitute it into their own web project and see it working correctly.
Also upload a screenshot of your browser window showing the completed index.html page in png or jpg format.
Review criteria
less 
Upon completion of the assignment, your submission will be reviewed based on the following criteria:

Task 1

The new content row is correctly formatted and includes the reservation form and the “Reserve a Table” card header.
The form contains the radios to enable specification of the number of guests.
The form includes a date field
The form includes a time field
The form contains a reserve button.
Task 2

The content in the row has been correctly formatted using the media class
The image is displayed to the right of the content using the correct media-* classes and at the correct position.
The badge is correctly displayed in the second row.
Task 3

The Reserve Table button is correctly included in the Jumbotron and is a block size button.
The button is correctly enclosed inside a div with the correct column specification.
The reserve button when clicked takes us to the form. The link in the button should be set up correctly to take us to the form.

<h2> Assignment 3: Bootstrap JavaScript Components</h2>
  
  InstructionsMy submissionDiscussions
In this assignment you will remove the tooltip from the Reserve table button. Then you will move the table reservation form into a modal that will be shown when the Reserve Table button is clicked. The updated reservation form will include a new radio button group allowing you to select the smoking/non-smoking section of the restaurant.

Objectives and Outcomes

In this assignment, you will continue to work with the website that you have been developing in the exercises. You will edit the home page (index.html). You will start with the current home page at the end of the last exercise in this module. At the end of this assignment, you should have completed the following tasks:

Moved the table reservation form from the last content row into a modal.
Included a radio button group in the table reservation form to enable diners to ask for a table in the smoking/non-smoking section of the restaurant.
Removed the tooltip from the Reserve Table button.
Updated the Reserve Table button to show the modal containing the table reservation form when the button is clicked.
Assignment Requirements

This assignment requires you to complete the following four tasks. Detailed instructions for each task are given below. The picture of the completed web page included below indicates the location within the web page that will be updated by the four tasks.

Task 1

In this task you will move the table reservation form from the last content row into a modal. You should also remove the last content row.

The form should be completely shifted to a modal.
Add a Cancel button in the form that will dismiss the modal when clicked.
The modal header should contain a X button to dismiss the modal.
Task 2

In this task you will be adding a radio button group to the form to allow the selection of the smoking/non-smoking section of the restaurant.

The radio button group should start out with the non-smoking section selected by default.
The row containing the button group will have the label Section displayed preceding it in the form.
Note: Read Bootstrap Buttons Checkbox/Radio for more information on how to design checkbox/radio buttons.

Task 3

In this task you will be updating the Reserve Table button in the Jumbotron:

Remove the tooltip from the button. This is to facilitate the button to be used to trigger the modal containing the table reservation form in the later tasks. A single button can support only one Javascript plugin via the data-* attributes. Make sure to remove the JavaScript script at the bottom of the page. Also remove the corresponding JavaScript code for the tooltip from the bottom of the page.
You will update the Reserve Table button to show the modal containing the table reservation form when the button is clicked.
At the end of this assignment, your index.html file should look like this:


Submission

You should submit the updated index.html file with all the tasks completed. A reviewer should easily be able to take your file and substitute it into their own web project and see it working correctly. 
Also upload a screenshot of your browser window showing the completed index.html page with the modal containing the table reservation form overlayed on top of the web page in png or jpg format.
Review criteria
less 
Upon completion of the assignment, your submission will be reviewed based on the following criteria:

Task 1:

The form has been moved into a modal.
The modal HTML code is included towards the top of the body of the page near the other modal code.
The modal includes a Cancel button to dismiss the modal.
The modal header includes a X button to dismiss the modal.
Task 2: 

A correct radio button group with the labels non-smoking in green and smoking in red is included in the form. Use the correct button color classes for the buttons.
The label of the row containing the buttons is set to Section.
The non-smoking button is checked by default.
Task 3:

The tooltip has been removed from the Reserve Table button and the corresponding JavaScript code has been removed from the bottom of the page.
The Reserve Table button will show the modal containing the table reservation form when clicked.
  
  <h2> Assignment 4: Bootstrap, JQuery and Sass</h2>
    
    InstructionsMy submissionDiscussions
In this assignment you will use the JavaScript methods to control the showing and hiding of the modals in the index.html page. You will replace the data-* attributes of the buttons and instead add JavaScript method to control the modals. In addition, you will write some SCSS code to style the modal background.

Step-By-Step Assignment Instructions
less 
Objectives and Outcomes

In this assignment, you will continue to work with the website that you have been developing in the exercises. You will edit the home page (index.html), the JavaScript code (scripts.js) and the SCSS code (styles.scss). You will start with the current home page at the end of the last exercise in this module. At the end of this assignment, you should have completed the following tasks:

Removed the data-* attributes from the Reserve Table button and the Login link in the Navbar that control the two modals.
Updated the button and the link so that they will trigger the appropriate JavaScript code when clicked.
Included appropriate JavaScript code using the modal methods to toggle the showing and hiding of the modals when the two buttons are clicked.
Add SCSS code to style the modal with colors.
Assignment Requirements

This assignment requires you to complete the following four tasks. Detailed instructions for each task are given below.

Task 1

In this task you will be removing the data-* attributes from the Reserve Table button in the Jumbotron that enable the toggling of the Reserve Table modal. Similarly you will also remove the data-* attributes from the Login link in the Navbar that triggers the Login modal.

Task 2

In this task you will add appropriate JavaScript code to the page so that the Reserve Table modal will be toggled when the Reserve Table button is clicked:

You will add the appropriate JavaScript code to the script.
You will update the button so that the modal is triggered when the button is clicked.
Note: Read Bootstrap Modal Methods for more information on how to implement the JavaScript methods.
Task 3

In this task you will add appropriate JavaScript code to the page so that the Login modal will be toggled when the Login link is clicked:

You will add the appropriate JavaScript code to the script.
You will update the Login link so that the modal is triggered when the link is clicked.
Task 4

In this task you will add appropriate SCSS code to styles.scss whereby the colors of the Modal are appropriately styled. These colors are already set up in the styles.scss file.

You will set the modal header to dark background and change the text color to floralwhite, and use nesting to change the color of the close button to floralwhite.
You will set the modal body to the pale background


Submission

You should submit the updated index.html file and styles.scss with all the tasks completed. A reviewer should easily be able to take your files and substitute it into their own web project and see it working correctly.
Review criteria
less 
Upon completion of the assignment, your submission will be reviewed based on the following criteria:

Task 1:

The data-* attributes have been removed from the Reserve Table button.
The data-* attributes have been removed from the Login link.
Task 2: 

Appropriate JavaScript code has been added to the page to trigger the Reserve Table modal.
The Reserve Table button has been appropriately updated to enable the triggering of the modal.
Task 3:

Appropriate JavaScript code has been added to the page to trigger the Login modal.
The Login link has been appropriately updated to enable the triggering of the modal.
Task 4:

Appropriate SCSS code has been added to styles.scss to set the modal header and body background colors appropriately.
Set up the modal header text color to floralwhite.
Set up the close button color to floralwhite.
