<h1>Automated Message Sender </h1>

<h2>Overview</h2>

When Apple released shortcuts, they originally allowed messages to be sent at a specified time and this was something I utilized often as I would like to send Happy Birthday messages or New Year's messages and ensure that my message would get to the particular owner at 12:00 AM sharp. This was particularly useful when I was on the east coast and most of the people I knew were on the West Coast so utilizing this feature allowed me to not stay up until 3:00 AM. However, due to security concerns, Apple modified this feature so that messages can only be sent when confirmed by the user. This left me with no choice, but to either stay up late or to send a message later than 12:00 AM. To not make any compromises I started developing this script to allow me to still send messages to people I know. This can be utilized by others on mac to send messages to people at any time they specify.

<h2>Requirement To Use</h2>
Script Editor on Mac and Microsoft Excel

<h2>How to run the application: </h2>

1. Download the script and the Excel file all into 1 folder
2. Open the Excel file and include the names of the people you'd like to send the message to in the first column, followed by the message you'd like to send in the second column.
   - The name has to be the name you have the person saved as in your contacts
   - The messages can be unique and do not all need to be the same
3. In the script the time can be modified to whatever time you'd like. (Note: The time must be in your time zone so if someone lives in a different timezone you must calculate the time difference and put that adjusted time in the myTime = "3:00:00 am line)
4. If you are sending the message to more than one person, you must modify the line "repeat until num is 3". If you have 4 people, it should be "repeat until num is 5". It should be the number of people you wanna send a message to -1.
5. In the method getName(i) there is a line "set FileName to ---- " this line must be set to the file path of the Excel file
6. In the method getMessage(i) there is a line "set FileName to ---- " this line must be set to the file path of the Excel file
