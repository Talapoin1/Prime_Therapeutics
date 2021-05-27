### File Description
3 Additional files included to show use of the document.

PPH 3 week tracker Final is the blank master document.

# Prime_Therapeutics

## Business Application:
The included macro enabled Excel file I created to track my work during my job as a pharmacy technician at a pharmacy benefit manager company.

Management wanted to ensure that they were getting the most productivity out of their employees.  Productivity was tracked by management as PPH (Production Per Hour).  This would be the average of how many cases are completed averaged over how many hours is worked by the employee during that time.

This can also be tracked manually by "claiming" cases.  In order to select our work, we pull files from a massive company wide collection of files and put our name on it to claim it as our own so that work is not overlapped.  The danger here is that sometimes claiming a file does not necessarily mean the file can be completed.

The purpose of this tracker was to ease the process of setting a goal and sticking to it.  The employee can track via PPH or cases claimed.  You can additionally enter how many hours you were in production and this tracker would indicate how many files you need to pull through the next few days.

## Fields that allow for input:
* Target PPH goal: This is used to set the overall goal of the tracker.  Typically this is a number between 5-10.
* Hours in Production: Can be manually changed based the employees work day.  Default(7.42) is a typical work day which takes into account lunch and two 15 minute rest breaks.
* Red Rectangular Date: Manually changed by employee to document what the start date(The Monday you want to start) of the sheet should be.
* "Enter data as" toggle: Allowed employee to track based on PPH provided by management (better for past data) or cases pulled (which is more useful if the employee doesn't want to wait a day for management to send PPH results)
* "Enter # of Cases Pulled Here" or PPH:  Employee will enter data here to allow the tracker to measure how much work the employee needs to do to stay on track their PPH goals.

On a day to day basis, the employee will input "# of cases pulled" or "PPH" depending on the setting and the tracker will indicate how many cases the employee should pull that day, the following day and the day after that to stay on track.  This can allow the employee to have a slow day or fast day and still be able to know approximately where the PPH is at or where they want it to be.


## How it works:
* Dates: The dates are all based on the one manually entered date in the red box.  As it is set up, it demands that this date be the Monday you want to start tracking
* PPH: Calculated from dividing the number of cases pulled by the hours in production or referenced from the Target PPH Goal in the absence of data. *When this field is yellow, this indicates an abscence of user data.*
* \# of Cases Pulled: The default value is simply a calculation indicating how many cases should be pulled when working 5 days a week for 3 weeks. *When this field is yellow, this indicates an abscence of user data.* 
* Cases needed to pull to stay on track: A complex equation that measures how many days are left in the 3 week span and how many cases have been pulled by the employee based on entered data.  Conditional formatting is used so the user can only see the current day, and a two day projection of how much work is needed to pull because the equation is inaccurate the further you try to project.  By adding data, the sheet will allow you to see the projections as you go.
* Enter data as: Using Visual Basic, I created a maco that would unlock the "*** Blank" sheets, copy the data over into the primary sheet and relock the "*** Blank" sheets.  the codde is stored in Module2.



