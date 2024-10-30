When you go to edit one of the forms, you will first be taken to a page that displays all of the existing questions for the form you are editing. In some forms, such as the submission form, and review form, there will be a dropdown menu with submission types that you will need to select an option from in order to see questions. Those forms are different for each submission type, so no questions can be displayed before it knows which form to use.

Once questions are displayed, each question will display 5 values on the admin page. Those are:

- Heading - The main heading of the question
- Subheading - Secondary text, usually reserved for extra instructions or clarification of terms
- Options - If a checkbox, radio button, or dropdown field, displays the content of each option for that field. Each option is formatted as "{{value}}||{{label}}" where value is what will be displayed on reports to admins, and label, which is what will be displayed to users
- Required - If the field needs to be filled out to submit. For questions that only show based off of other questions, should be set to "No" even if required when the condition to display the question is met

