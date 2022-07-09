# CIS-Java-Lab2
Git Hub Instruction


Instructions to Complete Week 2 - Lab 2 

Set up GitHub and GitHub Desktop

If you have not already done so set up a GitHub account at: 

          https://github.com/join

 Download and install the GitHub desktop application from: 

           https://github.com

 Login into D2L and navigate to the Contents Page for CIS-1500

 Scroll down to Week 2 contents and then to the Lab 2 Assignment

Click on the blue link below the words “Please use the link to have GitHub Classroom create your repository” 

Wait approximately 5 seconds and then refresh the page. The page will indicate that you are ready to go and that the repository was created.

    3.    Click on the blue link under the text that says “Your assignment repository has been created”

GitHub online should open with a repository which contains a .gitignore and README.md file

Click on the Green “Code” button

Click the option “Open with Github Desktop”

A dialog window may pop up confirming that you want to open GitHubDesktop choose the “Open GitHubDesktop.exe” option

   4. Github Desktop Application will open

You should see a window that says “Clone a Repository”

 You can leave the default setting or change the Local Path to a different location. The local path is where the repository will be stored on your local machine

Make a note of this path because you will need it in the next few steps.

           i. It is a good idea to copy the path

Leave the GitHub desktop client open (you can minimize it)

  5.  Open IntelliJ

        a. Select from top menu bar: File → New → Project

         b.  A dialog box will open. Fill in the name of the project (for this case most likely  lab2)

         c.  The location needs to match the local path from step 4.b above. You can paste it in the box or choose the browse option. 

               The browse option can be accessed from the folder icon on the right hand side of the location text input area. 

         d. Make sure the language is set to Java

         e. JDK  - this should be set to a version of “openjdk-18 Oracle OpenJDK version 18.0.1”  if not select Download JDK… form                the dropdown. A window will open with some information populated. The vendor should refer to Oracle such as “Oracle                    OpenJDK 18.0.1.1” You can leave the location the same. Click ‘Download”

          f. Click the “Create” button

  6. Navigate to the source file in the left file system

 The source file will be named src

Right click on the source file (src) select New→ Package

Fill in a package name (lowercase for packages) = lab2

   7. Select and right-click on the lab2 package file from the file navigator

Select: New→ Java Class

Give the class a name (Capitalize first letter) i.e. Lab2

8. Code the Program.

Create a main function inside the lab2 class

            i. You can use shortcut  psvm followed by the  tab key

Create a variable for the tax rate of type double and initialize it to .1 representing 10%

Declare a scanner object giving it a name such as keyboard

Prompt the user to enter the hourly wage

             i. use System.out.println to display your message

Get the user input using the scanner object declared above with the nextline() function

            i. We want this value to be a double so use the Double.parseDouble function around the keyboard.nextline() command of 

                the form: Double.parseDouble(keyboard.nextLine())

             ii. Set the value returned from the nextline command to a double variable representing the hourly wage 

Prompt the user to enter the hours worked this week

              i. use System.out.println to display the message

            ii. Get the input by using the scanner object with the nextline() function

             iii. Set the value returned from the nextline command to a  variable of type double representing the weekly hours worked.                      Use Double.parseDouble(keyboard.nextLine()) to force it to be a double.

Calculate the Gross pay

            i. Declare a double variable and set it’s value equal to variable for  hourly wage times the variable containing weekly hours                     worked

       h. Calculate the Taxes Owed

             i. Declare a double variable and set it’s value equal to the variable for gross pay times the variable for tax rate

        i. Calculate the Net Pay

            i. Declare a double variable and set its value equal to the variable for Gross pay minus the variable for taxes Owed.

      j.   Display the results

           i. Display to the value of the gross pay using the system.out.println command declaring a string informing the user what                        variable you are listing concatenated with the variable itself such as: System.out.println("Gross Pay: $"+grossPay);

           ii. Use another System.out.println command to display the taxes owed

          iii. Use one final System.out.println command to display the value of the net pay

9. Run the code

There are several methods to run the code

           i. Method 1:  From the menu at the top choose Run → Run Lab2

           ii. Method 2: Left click on the green triangle and then select and click Run Lab2.main()

10. Commit and Push the completed code

        a. You will see a list of files on the right.

         b. Left click on the Lab2.java file

         c. Below the area where you select the files enter a description like “Lab2 Completed”

          d. Click the “Commit to Main” button

          e. Click the “Push Origin” button

          f. If you click on the “View on Github” button it will open your repository online which should contain the recent updates. 

           g. Navigate to the Lab2 → src/lab2 → Lab2.java file

            h. Click on the Lab2.java and confirm that it contains the code you have written so far.

                 i. Once you confirm that it is correct  copy the URL from the browser while you are in the java file and then submit that 

                   to D2L as your completed assignment
