  ----------------- --------------- -------------------------------------------------------------------------------------------------------------
  **Bug ID**        

                    ID number:       #001
                    
                    Name:            Signed user doesn't get a verification email

                    Reporter:        Mariam Avetisyan

                    Submit Date:     07/10/23

  **Bug overview**  

                    Summary:         Sign Up with mar2@mailinator.com email doesn't get an email of verification
                    
                    URL:             https://eyeb-web-git-dev-eyeb.vercel.app

                    Screenshot:      https://drive.google.com/file/d/1eNZkEYDozgeVj8s9ivhuvQe0fEBsky8b/view?usp=drive_link

  **Environment**   

                    Platform:        Windows 11 Home
                    
                    Operating        22H2 x 22621.1778
                    System:          

                    Browser:         Chrome: 114.0.5735.110\
                                     Firefox: 114.0.1

  **Bug details**   

                    Preconditions:   -
                    
                    Steps to         1. Open the https://eyeb-web-git-dev-eyeb.vercel.app/ website
                    reproduce:       2. Click on the “Sign Up” button
                                     3. Click on “User phone or email”
                                     4. Select the "Email" option
                                     5. Enter valid email (both fill in the field and copy/paste)
                                     6. Click on "Next"
                                     7. Create a Password (enter a valid password)
                                     8. Setup the birthday -> click on "Next"
                                     9. Pick the interests -> click on "Build my feed"
                                     10. After getting the generated username click on "Next"

                    Expected result: If signing up a user with a valid email should successfully create it with a success message.


                    Actual result:   When creating a new account with a valid email doesn't get a verification email.

                    Description:     -

  **Bug tracking**  

                    Severity:        Major
                    
                    Assigned to:     -

                    Priority:        High

  **Notes**         
  
                    Notes           -
  -----------------------------------------------------------------------------------------------------------------------------------------------
  ----------------- --------------- -------------------------------------------------------------------------------------------------------------
  **Bug ID**        

                    ID number:       #002
                    
                    Name:            Sign Up can't fill in email by typing

                    Reporter:        Mariam Avetisyan

                    Submit Date:     07/10/23

  **Bug overview**  

                    Summary:         Sign Up with mar3@mailinator.com email and fill in the input by typing (not copy paste)
                    
                    URL:             https://eyeb-web-git-dev-eyeb.vercel.app

                    Screenshot:      https://drive.google.com/file/d/19nQjf4e-21VKwizPJRUZA8P1ZF0j-LxB/view?usp=drive_link

  **Environment**   

                    Platform:        Windows 11 Home
                    
                    Operating        22H2 x 22621.1778
                    System:          

                    Browser:         Chrome: 114.0.5735.110\
                                     Firefox: 114.0.1

  **Bug details**   

                    Preconditions:   -
                    
                    Steps to         1. Open the https://eyeb-web-git-dev-eyeb.vercel.app/ website
                    reproduce:       2. Click on the “Sign Up” button
                                     3. Click on “User phone or email”
                                     4. Select the "Email" option
                                     5. Enter valid email by typing (not copy/paste)
                                     
                    Expected result: If signing up a user with a valid email should successfully allow entering the email into the input.


                    Actual result:   When trying to fill in the input of email after the 7th character doesn't allow to enter.

                    Description:     -

  **Bug tracking**  

                    Severity:        Major
                    
                    Assigned to:     -

                    Priority:        High

  **Notes**         
  
                    Notes           -
  -----------------------------------------------------------------------------------------------------------------------------------------------
   ----------------- --------------- -------------------------------------------------------------------------------------------------------------
  **Bug ID**        

                    ID number:       #003
                    
                    Name:            Password requirement is weak

                    Reporter:        Mariam Avetisyan

                    Submit Date:     07/10/23

  **Bug overview**  

                    Summary:         Sign Up Create Password allows you to enter a weak password
                    
                    URL:             https://eyeb-web-git-dev-eyeb.vercel.app

                    Screenshot:      https://drive.google.com/file/d/1ML3H9mXMOsIkcIeguEgH-RiTW8z-t1C2/view?usp=drive_link

  **Environment**   

                    Platform:        Windows 11 Home
                    
                    Operating        22H2 x 22621.1778
                    System:          

                    Browser:         Chrome: 114.0.5735.110\
                                     Firefox: 114.0.1

  **Bug details**   

                    Preconditions:   -
                    
                    Steps to         1. Open the https://eyeb-web-git-dev-eyeb.vercel.app/ website
                    reproduce:       2. Click on the “Sign Up” button
                                     3. Click on “User phone or email”
                                     4. Select the "Email" or "Phone" option
                                     5. Enter a valid email/phone
                                     6. Click on "Next"
                                     7. Fill in the Passwords with the weak entries (only lower or upper letter, or only number)
                                     8. Click on "Next"
                                     
                    Expected result: The password field must be allowed at least 8 characters and filled with the English alphabet 
                                     letters and include three character types lowercase letters, uppercase letters, and numbers. 
                                     You also have the option to use any of these special characters


                    Actual result:   When trying to fill in the password allow enter only letters, numbers or symbols.

                    Description:     -

  **Bug tracking**  

                    Severity:        Major
                    
                    Assigned to:     -

                    Priority:        High

  **Notes**         
  
                    Notes           -
  -----------------------------------------------------------------------------------------------------------------------------------------------
  ----------------- --------------- -------------------------------------------------------------------------------------------------------------
  **Bug ID**        

                    ID number:       #004
                    
                    Name:            Navigation issue on enter

                    Reporter:        Mariam Avetisyan

                    Submit Date:     07/10/23

  **Bug overview**  

                    Summary:         Sign Up with the email tab to keyboard enter navigates the wrong page
                    
                    URL:             https://eyeb-web-git-dev-eyeb.vercel.app

                    Screenshot:      https://drive.google.com/file/d/1jA4SZLbpIvAEpJTq8nlq6VCSF89xtOhg/view?usp=sharing

  **Environment**   

                    Platform:        Windows 11 Home
                    
                    Operating        22H2 x 22621.1778
                    System:          

                    Browser:         Chrome: 114.0.5735.110\
                                     Firefox: 114.0.1

  **Bug details**   

                    Preconditions:   -
                    
                    Steps to         1. Open the https://eyeb-web-git-dev-eyeb.vercel.app/ website
                    reproduce:       2. Click on the “Sign Up” button
                                     3. Click on “User phone or email”
                                     4. Select the "Email" option
                                     5. Enter a valid email (could be a registered user or a new one)
                                     6. Tab on "Next" from a keyboard
                                     
                    Expected result: If entering email and tabbing to "Next" from the keyboard, if the user exists should navigate to 
                                     the 'Sing In' pop-up otherwise opens the 'Create Password' pop-up.


                    Actual result:   When filling in or without filling in the email and tabbing to [Enter] navigates to the wrong page.
                                     (link: https://eyeb-web-git-dev-eyeb.vercel.app/search/)

                    Description:     -

  **Bug tracking**  

                    Severity:        Major
                    
                    Assigned to:     -

                    Priority:        High

  **Notes**         
  
                    Notes           -
  -----------------------------------------------------------------------------------------------------------------------------------------------
