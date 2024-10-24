The abstract scheduling module will be used to predominantly create presentation sessions to assign abstracts to during the meeting. Sessions are required to be linked to one of the [[Review System Setup#Acceptance Types|Acceptance Types]] in the system, and all times in the scheduler will be relative to the [[|time zone]] of the event. The below guide will explain the different parts of the system as well as provide information as to setting up the system.

# Scheduler Home

This page will display your presentation sessions as a calendar to allow visualization of the sessions throughout the day. Admins will also be able to drag and drop the sessions as well as drag the edges in order to modify the time slots of each session. 

# Edit Calendar Settings

This page currently only allows admins to edit the color of sessions on the calendar. Each session will appear according to the color of the selected acceptance type, so any color changes will be reflected on all events of a specific acceptance type.

# Session Manager and Import

The session manager page allows creation of new sessions as well as editing / deleting existing sessions, assigning abstracts to sessions, and an import feature to do bulk assignments to sessions.

## Session Editor

Creating a new session or editing an existing session will take you to a page to change any parameter about the session. The form will look like below. __Calendar Group will be changed to Acceptance Type in a future release__. Clicking submit will update / create a new session.

![[Pasted image 20240821151350.png]]

## Importing Session Assignments

An link to an excel template will be provided in the instructions at the top of the screen that has the formatting for the import file that can be used to do mass session assignments. 

EXAMPLE SESSION IMPORT WORKFLOW:
- Create all sessions in the scheduler
- Download the excel template from the webpage
- Run a [[|report]] to get ID's of all submissions
- Create a row for each session that will be assigned abstracts, following the template rows as an example
	- NOTE: dates must be formatted exactly like the example rows
- Copy the rows for each abstract for that session, changing the ID for each one
- Save file, and use it in the import file form field at the bottom of the page
- Review matches to ensure they are correct
- If matches are correct, save the matched rows to the database as session assignments
