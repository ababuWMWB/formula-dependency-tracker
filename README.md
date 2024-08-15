Activating a Trigger for Your Google Apps Script Function
Understanding Triggers:
Triggers in Google Apps Script are events that can initiate the execution of a function. In your case, you'll want to set up a trigger to run the onEdit function whenever a cell in your Google Sheet is edited.

Steps to Create an Edit Trigger:

Open Your Script Editor:

Go to your Google Sheet.
From the menu, select Tools > Script editor.
Save Your Script:

If you haven't already, save your script with a meaningful name.
Open the Triggers Menu:

Click the Triggers button in the script editor toolbar.
Create a New Trigger:

Click the + button to add a new trigger.
Select Function and Event Source:

In the Choose which function to run dropdown, select onEdit.
In the Select event source dropdown, choose From spreadsheet.
Set the Event Type:

Choose On edit as the event type.
Choose Execution Options (Optional):

You can set additional options like:
Execution frequency: How often the trigger should run (e.g., every hour, every day).
Failure notification: Whether to receive an email notification if the trigger fails.
Include all form submissions: If you're using Google Forms, you can include form submissions in the trigger.
Save the Trigger:

Click Save to create the trigger.
Verification:

Now, whenever you edit a cell in your Google Sheet, the onEdit function will execute and highlight the referenced cells.
Additional Notes:

If you need to modify the trigger later, you can edit it by clicking the Edit button next to the trigger in the Triggers menu.
You can also create triggers for other events, such as when a sheet is opened, saved, or deleted.
By following these steps, you'll have successfully set up a trigger to automatically run your onEdit function whenever a cell in your Google Sheet is edited.
