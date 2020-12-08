This protocol assumes your work/university email account is hosted by Gmail or Apple Mail. Other commonly used email clients like Microsoft Outlook also allow you to download your email data - instructions to do so using these clients are coming soon.

## G-Mail

1.  Log in to your Gmail account in the Gmail web interface.

2.  On the left-hand side of your Gmail display, scroll to the bottom of the menu options that have “Inbox” at the top and select “Create new label”.

3.  Call your new label name “Emails for Export” and click “Create”.

    ![](https://user-images.githubusercontent.com/42762378/101547694-a63e1780-39d0-11eb-963a-e9a1c31b55ec.png)

4.  Select all of your outgoing emails within the following two time ranges using the check box on the left-hand side of each email thread.
    
      April 1 - May 31, 2019 (Pre-pandemic)
      
      April 1 - May 31, 2020 (Mid-pandemic)
      
    Once all emails are selected, click the “Labels” button at the top of the Gmail display, and select the new label you just created, “Emails for Export”.

    IMPORTANT NOTE: While we are taking precautions to make sure that the sensitive contents of your email data are protected during this process (more on this later), we understand that you may have privacy concerns about sharing your email data. While it’s true that the more emails you share the better this will be for our analysis, you have full discretion over which and how many of your outgoing emails you choose to contribute to our dataset. If there are some messages in these time ranges that you feel are too sensitive to include, simply exclude them!

    ![](https://user-images.githubusercontent.com/42762378/101547892-02a13700-39d1-11eb-8111-9b7f22adb646.png)

5.  All of the e-mails you’ve selected should now have a label reading “Emails for Export” in small text next to the subject line.

6.  While still logged in to your Gmail account, navigate to Google Takeout: https://takeout.google.com/settings/takeout

7.  Under the menu titled “CREATE A NEW EXPORT” you will see a long list of data types connected with your account that Google allows you to download. Select “Deselect All” at the top of the menu.

8.  Navigate to “Mail” and select this option ONLY.

    ![](https://user-images.githubusercontent.com/42762378/101548046-472cd280-39d1-11eb-82b4-2eb4c456b3f7.png)

9.  Click “All Mail data included”. Deselect the “Include all messages in Mail” option and select the new label you just created, “Emails for Export” ONLY.

10.  Scroll to the bottom of the main Google Takeout screen and click “Next Step”.

11.  For the “Choose file type, frequency and destination” menu, select the options below:

   ![](https://user-images.githubusercontent.com/42762378/101548170-6d527280-39d1-11eb-9a27-6cff6b1d3dc5.png)

12.  Google Takeout may take a few minutes to complete your request depending on the size of your email export. Once it is complete, you should see a screen like this:

   ![image](https://user-images.githubusercontent.com/42762378/101548241-88bd7d80-39d1-11eb-89ca-4147070aa47b.png)

13.  Select “Open in Drive”. You should now be able to download a zipped file with your email metadata.

14.  Unzip the file on your computer. You should find a folder titled “Takeout” containing a subfolder titled “Mail”. Open “Mail” and confirm you have a file titled “Emails for Export.mbox”. This is your Gmail data!

15.  Go to the Google Colaboratory iPython notebook link below and follow the instructions in it. Make sure you repeat the process for both mbox files.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/delaiglesialab/DigitalRhythmsProject/blob/main/Get_Email_Timestamps_Notebook.ipynb)

You're all set! Go back to the main page and continue to the next (final) step!

## Apple Mail

1.  In the Mail app, select Mailbox -> New Mailbox

2.  Name the Mailbox whatever you'd like

3.  Drag and drop the messages you want to include for download into your new Mailbox

4.  Select Mailbox -> Export Mailbox

5.  Select your folder for export. You should see a new mbox file icon appear, which will contain two files: “mbox” and “table_of_contents”. At first the file extension may read “partial.mbox” - this means the file is still downloading from your Apple Mail server, so wait until the “partial” disappears.

6. Manually rename the newly created mbox file to include the “.mbox” file extension, otherwise the iPython Notebook in the next step will not be able to properly read the file type.

7.  Go to the Google Colaboratory iPython notebook link below and follow the instructions in it. Make sure you repeat the process for both mbox files.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/delaiglesialab/DigitalRhythmsProject/blob/main/Get_Email_Timestamps_Notebook.ipynb)

You're all set! Go back to the main page and continue to the next (final) step!
