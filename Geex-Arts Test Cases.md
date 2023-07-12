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
|4|Enter valid email (both fill in the field and copy/paste)|
|5|Click on "Next"|
|6|Create Password (enter valid password)|
|7|Setup the birthday -> click on "Next"|
|8|Pick the interests -> click on "Build my feed"|
|9|After getting the generated username click on "Next"|


|**Expected Result**|If signing up a user with a valid email should successfully create it with a success message.|
| :- | :- |
|**Notes**|When creating a user with an email should, after registration should send a verification email that allows to log in the registered user.|


*Scenario 2:*

|**Test Case ID**|EBT - 002|**Designed by**|Mariam Avetisyan|
| :- | :- | :- | :- |
|**Test Priority (Low/Medium/High)**|Medium|**Designed date**|11/07/2023|
|**Module Name**|Sign Up User|**Test Executed by**|Mariam Avetisyan|
|**Scenario ID**|2|**Test Execution date**|10/06/2023|


|**Test Title**|Verify Sign Up user with a valid phone|
| :- | :- |
|**Test Objective**|To sign up with a valid phone|


|**Preconditions**|
| :- |
|<p>1. The browser should be updated to the latest version (Chrome: 114.0.5735.110 (Official Build) (64-bit))</p><p>2. The testing environment should be stable and up.</p><p>3. Open the <https://eyeb-web-git-dev-eyeb.vercel.app/feed></p>|


|**Steps No**|**Test Steps**|
| :- | :- |
|1|Click on the “Sign Up” button|
|2|Click on “User phone or email”|
|3|Select the "Phone" option|
|4|Enter valid phone|
|5|Click on "Next"|
|6|Create Password (enter valid password)|
|7|Setup the birthday -> click on "Next"|
|8|Pick the interests -> click on "Build my feed"|
|9|After getting the generated username click on "Next"|


|**Expected Result**|If signing up a user with a valid phone should successfully create it with a success message.|
| :- | :- |
|**Notes**|After registration should not login user automatically.|


*Scenario 3:*

|**Test Case ID**|EBT - 003|**Designed by**|Mariam Avetisyan|
| :- | :- | :- | :- |
|**Test Priority (Low/Medium/High)**|Medium|**Designed date**|11/07/2023|
|**Module Name**|Sign Up User|**Test Executed by**|Mariam Avetisyan|
|**Scenario ID**|3|**Test Execution date**|10/06/2023|


|**Test Title**|Verify Sign Up user with a valid phone|
| :- | :- |
|**Test Objective**|To sign up with a Google Account|


|**Preconditions**|
| :- |
|<p>1. The browser should be updated to the latest version (Chrome: 114.0.5735.110 (Official Build) (64-bit))</p><p>2. The testing environment should be stable and up.</p><p>3. Open the <https://eyeb-web-git-dev-eyeb.vercel.app/feed></p>|


|**Steps No**|**Test Steps**|
| :- | :- |
|1|Click on the “Sign Up” button|
|2|Click on “Continue with Google”|
|3|Choose an account|
|4|Get back to the signup page|
|5|Setup the birthday -> click on "Next"|
|6|Pick the interests -> click on "Build my feed"|
|7|After getting the generated username click on "Next"|


|**Expected Result**|If signing up a user with a Google account should successfully create it with a success message.|
| :- | :- |
|**Notes**||

*Scenario 4:*

|**Test Case ID**|EBT - 004|**Designed by**|Mariam Avetisyan|
| :- | :- | :- | :- |
|**Test Priority (Low/Medium/High)**|Medium|**Designed date**|11/07/2023|
|**Module Name**|Sign Up User|**Test Executed by**|Mariam Avetisyan|
|**Scenario ID**|4|**Test Execution date**|10/06/2023|


|**Test Title**|Verify Sign Up user with a valid phone|
| :- | :- |
|**Test Objective**|To sign up with an existing user (email, phone)|


|**Preconditions**|
| :- |
|<p>1. The browser should be updated to the latest version (Chrome: 114.0.5735.110 (Official Build) (64-bit))</p><p>2. The testing environment should be stable and up.</p><p>3. Open the <https://eyeb-web-git-dev-eyeb.vercel.app/feed></p>|


|**Steps No**|**Test Steps**|
| :- | :- |
|1|Click on the “Sign Up” button|
|2|Click on “User phone or email”|
|3|Select the "Phone"/"Email" option|
|4|Enter valid phone/email (which already has an account)|
|5|Click on "Next"|


|**Expected Result**|If signing up a user with an existing account (phone/email) should be redirected to the sign-in pop-up.|
| :- | :- |
|**Notes**||
