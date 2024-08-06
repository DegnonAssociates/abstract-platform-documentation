Go back: [[Degnon Abstract System]]

This page will mostly cover the structure of how the abstract system handles all of the different parts involved in a complete abstract system, as well as how those parts interact with each other and the users. This page may be helpful for admins who need clarification on a specific part during the setup of any part.
### Instances
Each separate meeting system will have its own client-specific url, and will hereby be referred to as an "Instance" which would contain information for the whole abstract system such as meeting dates, meeting logo, neon integration, things like that. Once an instance is created, an admin can go in and make changes in the "General Configuration" page of the admin portal.

Instances cannot hold any info about abstracts on their own, instead they break the abstract system down into customizable parts that can be edited by admin. Those will be detailed below.

### Submission Types

The first step after setting up the instance will be to set up one or multiple submission types that users will submit abstracts as. Those can have different questions, review processes and be judged separately, just like previous systems. Submission types will hold information relevant to that abstract path, such as open and close dates, what author info to capture, whether there are child abstracts, etc.  

### Submission Fields

Each submission type contains a variety of submission fields, which are basically questions asked in the abstract submission form, and are customizable by the admin users to build the form that captures all information for that submission type. Each submission field has options such as heading/subheading, what type of question it is (single line text, paragraph, checkbox, radio ...), as well as options for validation such as if a paragraph text field will be included in the overall word count if the submission type has one, or if it is required for final submission. 

Submission fields that are of type radio, checkbox, or dropdown, will also have a field appear for "Options." Those options act as the different checkboxes or radio buttons that will appear for that question as values for the user to select. A valid field with options must contain at least one option.

### Review Fields

Review fields are almost identical to submission fields, but will be used to create the form that reviewers will fill out once the review process begins. Those are also grouped by submission type, as each abstract submission type must also have a unique review form.

### "Other" Fields

There are a couple of other miscellaneous forms that have the same structure as review fields and submission fields. Those include CME Questions, and Call for Reviewer Questions, among others.
### Abstract Data

Not important for any work required of admins, mainly for IT. Abstract data is how every piece of information is stored apart from a few hard-coded questions in some forms (abstract title, confirmed/declined to present, etc) and is linked to questions and submissions by a combination of ids, question ids, and the "type" column for data, which tells the system what form the information comes from.

