Automated Message Sender

A script that can be used by Mac users to send messages to people in their contacts at the time specified.

Tech used: AppleScript and Excel



How to run the application:

1. Download the script and the Excel file all into 1 folder
2. Open the Excel file and include the names of the people you'd like to send the message to in the first column, followed by the message you'd like to send in the second column.
   - The name has to be the name you have the person saved as in your contacts
   - The messages can be unique and do not all need to be the same
3. In the script the time can be modified to whatever time you'd like. (Note: The time must be in your time zone so if someone lives in a different timezone you must calculate the time difference and put that adjusted time in the myTime = "3:00:00 am line)
4. If you are sending the message to more than one person, you must modify the line "repeat until num is 3". If you have 4 people, it should be "repeat until num is 5". It should be the number of people you wanna send a message to -1.
5. In the method getName(i) there is a line "set FileName to ---- " this line must be set to the file path of the Excel file
6. In the method getMessage(i) there is a line "set FileName to ---- " this line must be set to the file path of the Excel file
