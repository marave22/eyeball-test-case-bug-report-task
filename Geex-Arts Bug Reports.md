  -----------------------------------------------------------------------------------------------------------------------------------------------
  **Category**      **Label**       **Value**
  ----------------- --------------- -------------------------------------------------------------------------------------------------------------
  **Bug ID**        

                    ID number       #001
                    
                    Name            Signed user doesn't get a verification email

                    Reporter        Mariam Avetisyan

                    Submit Date     07/10/23

  **Bug overview**  

                    Summary         Login with mar2@mailinator.com email doesn't get an email of verification
                    
                    URL             https://eyeb-web-git-dev-eyeb.vercel.app

                    Screenshot      [[screen
                                    recording]{.underline}](https://drive.google.com/file/d/1wAuE9hq58lg5-bYFN4lYY4MROyAyQGDn/view?usp=sharing)

  **Environment**   Platform        Windows 11 Home

                    Operating       22H2 x 22621.1778
                    System          

                    Browser         Chrome: 114.0.5735.110\
                                    Firefox: 114.0.1

  **Bug details**   Preconditions   Should have already signed up a user with performance user permissions.\
                                    **Username**: performance_glitch_user\
                                    **Password**: secret_sauce

                    Steps to        1\. Open the https://www.saucedemo.com/ website\
                    reproduce       2. Enter valid performance_glitch_user credentials\
                                    3. Click on the \"Login\" button\
                                    4. Verify that the user is successfully logged in and redirected to the Products page

                    Expected result The user should be successfully logged in and redirected to the homepage.\
                                    The application should behave normally without any performance glitches.

                    Actual result   When users log in with performace_glitch_user the redirection to product page takes a long not applicable
                                    time limits

                    Description     /

  **Bug tracking**  Severity        Major

                    Assigned to     /

                    Priority        High

  **Notes**         Notes           /
  -----------------------------------------------------------------------------------------------------------------------------------------------
