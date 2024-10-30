Configures system-wide information and settings that will be used in all aspects of the abstract process.

# Form Fields

#### Uses NeonCRM SSO, SSO URL, SSO OAuth Token, OAuth Client Id, OAuth Client Secret, OAuth Redirect URI, New Account URL

- Admins can ignore all of these, they will be set up by IT, and will be set up before access is graned to client teams in most cases. Please reach out to IT if any issues arise related to Neon integration, logins, or account editing.

#### Client Name

- **Type:** Text Input

- **Description:** The abbreviated name of the Client.

#### Contact Email

- **Type:** Text Input

- **Description:** The contact email address for communications with the system. Will be displayed for users to submit questions to as well as be the address that emails from the system are sent through.

#### Contact Email Alias

- **Type:** Text Input

- **Description:** An alias for the contact email address.

#### Client Logo URL

- **Type:** Text Input

- **Description:** The URL of the client's logo. Can be any url that points to an image file. Many teams choose to point to a copy of the logo in the wp-content folder of their websites.

#### User Account Form URL

- **Type:** Text Input

- **Description:** IT related field. Can be ignored

#### Meeting Dates

- **Type:** Text Input

- **Description:** The dates of the meeting that the submissions will be presented

#### Meeting Location

- **Type:** Paragraph Text

- **Description:** The location of the meeting, paragraph field can be used to format the info if more verbose location info needs to be put in
  

#### Meeting Location Timezone

- **Type:** Dropdown

- **Description:** The timezone of the meeting location. Should be set by IT but ensure it is correct before system opens  

#### Login Page Text

- **Type:** Paragraph Text

- **Description:** The text displayed on the login page. Text informs users of how to create an account and complete the account creation process with Neon, as well as how to log in as an existing user. Boilerplate text can be found in other submission systems or can be provided by request if needed.  

#### Review Page Text

- **Type:** Paragraph Text

- **Description:** The text displayed on the review page. Reviews already have built-in instructions so this would contain any extra text needed by the specific instance. The text will be displayed on the "My Review" tab of the homepage underneath "Thank you for taking the time to review for the {{Client Name}} Annual Meeting."

#### Guidelines URL

- **Type:** Text Input

- **Description:** A link to resources containing guidelines for submission. If guidelines are same for all submissions, the link can be as simple as a PDF. For abstract systems with more than one set of guidelines, it is recommended to create a page in wordpress that contains links to all of the different guidelines, then link to the WP page as the guidelines URL to allow users to see multiple files. 

#### Add Call for Reviewers

- **Type:** Checkbox

- **Description:** Indicates whether to show the reviewer signup page on the homepage. Form needs to be set up according to the specifications listed here [[Reviewer Call Form]] before call for reviewers can be enabled
