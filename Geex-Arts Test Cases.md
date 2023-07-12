**Project Name:** *eyeball*

*Scenario 1:*

|**Test Case ID**|EBT - 001|**Designed by**|Mariam Avetisyan|
| :- | :- | :- | :- |
|**Test Priority (Low/Medium/High)**|Medium|**Designed date**|11/07/2023|
|**Module Name**|Sign Up User|**Test Executed by**|Mariam Avetisyan|
|**Scenario ID**|1|**Test Execution date**|10/06/2023|


|**Test Title**|Verify Sign Up user with a valid email|
| :- | :- |
|**Test Objective**|To sign up with a valid email (not generated)|


|**Preconditions**|
| :- |
|<p>1. The browser should be updated to the latest version (Chrome: 114.0.5735.110 (Official Build) (64-bit))</p><p>2. The testing environment should be stable and up.</p><p>3. Open the <https://eyeb-web-git-dev-eyeb.vercel.app/feed></p>|


|**Steps No**|**Test Steps**|
| :- | :- |
|1|Click on the “Sign Up” button|
|2|Click on “User phone or email”|
|3|Select the "Email" option|
|4|Enter valid email (not copy and paste)|
|5|Click on "Next"|
|6|Create Password (enter valid password)|
|7|Setup the birthday -> click on "Next"|
|8|Pick the interests -> click on "Build my feed"|
|9|After getting the generated username click on "Next"|


|**Expected Result**|If signing up a user with a valid email should successfully create it with a success message.|
| :- | :- |
|**Notes**|When creating a user with an email should, after registration should send a verification email that allows to log in the registered user.|

