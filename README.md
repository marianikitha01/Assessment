
## Feedback Form

This HTML form captures user feedback along with additional details and displays the records in a tabular format. The project uses HTML, CSS with Bootstrap, and JavaScript for the frontend and localStorage for data persistence.

I have used input boxes in addition to text areas in this project. Name, Phone Number, and Password fields are input boxes, whereas, Address, Feedback and Additional Comments field are text areas. 

## How to Run the Project
To run this project locally:

Download or clone the repository.
Open the assessment.html file in a web browser.

## Functionality
The feedback form validates user input for various fields such as name, phone number, password strength, and input length for address, feedback, and comments. An error will be thrown and the user won't be able to submit the form if they do not enter atleast one sentence in Address, Feedback and Additional Comments field. Users can submit their feedback, and the data will be displayed in a table below the form.

## Relevant Information
The project uses Bootstrap for styling and layout.
JavaScript is utilized for form validation and handling user interactions.
Data is stored locally using the localStorage object.
The table dynamically updates with the submitted feedback records.
Users can edit or delete their submitted feedback from the table.

## Screenshots

![form](https://github.com/marianikitha01/Assessment/blob/main/images/form.png)
**This is a screenshot showcasing the basic html form that I created.**


![error](https://github.com/marianikitha01/Assessment/blob/main/images/error.png)
**This is a screenshot showcasing the error thrown when an user doesnot enter more than 1 sentence in a text area.**


![table](https://github.com/marianikitha01/Assessment/blob/main/images/table.png)
**The content entered in the form is added to the table shown in the figure. The table also contains an edit and delete button, user can click on the buttons to perform CRUD opration on the form data.**

![edit](https://github.com/marianikitha01/Assessment/blob/main/images/edit.png)
**This is a screenshot showcasing the form after clicking on the edit button in the table.**

![local_storage](https://github.com/marianikitha01/Assessment/blob/main/images/local_storage.png)
**This is a screenshot showcasing the local storage. The details entered in the form is reflected in this table.**