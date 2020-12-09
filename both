# Step 1 of 2: Obtain the data

# E-mail Timestamps

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

Once you've obtained the CSV files from the notebook, continue scrolling to the next data format that is applicable to you.

## Apple Mail

1.  In the Mail app, select Mailbox -> New Mailbox

2.  Name the Mailbox whatever you'd like

3.  Drag and drop the messages you want to include for download into your new Mailbox

4.  Select Mailbox -> Export Mailbox

5.  Select your folder for export. You should see a new mbox file icon appear, which will contain two files: “mbox” and “table_of_contents”. At first the file extension may read “partial.mbox” - this means the file is still downloading from your Apple Mail server, so wait until the “partial” disappears.

6. Manually rename the newly created mbox file to include the “.mbox” file extension, otherwise the iPython Notebook in the next step will not be able to properly read the file type.

7.  Go to the Google Colaboratory iPython notebook link below and follow the instructions in it. Make sure you repeat the process for both mbox files.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/delaiglesialab/DigitalRhythmsProject/blob/main/Get_Email_Timestamps_Notebook.ipynb)

Once you've obtained the CSV files from the notebook, continue scrolling to the next data format that is applicable to you.

## Android

### To obtain your Android app activity data:

The process is quite straightforward but I've made sure to document each step in case you get lost! The page might look lengthy but you're really just a few clicks away.

The first step is to visit https://takeout.google.com/ and ensure you are signed into the same account as the primary one on your android phone.

Next, click on "deselect all" as shown below, since we only want to export the app activity data!


![1](https://user-images.githubusercontent.com/68754864/96494580-2dd69800-1264-11eb-93a3-8a2270246b41.png)


Next, scroll down to find the "My Activity" banner. It is usually between "Maps (your places)" and "My Maps".

Tick the checkbox on the right, and click the "Multiple Formats" button on the left.


![2](https://user-images.githubusercontent.com/68754864/96494591-2fa05b80-1264-11eb-8639-2863cdcbf71d.png)


In the pop-up that opens, be sure that Activity Records is set to the HTML format like the picture below and **NOT** JSON. Click "Ok" to continue.


![3](https://user-images.githubusercontent.com/68754864/96494593-3038f200-1264-11eb-87f8-0b629b36ce14.png)


Now click the button that says "All activity data included" and in the pop-up, first click "Deselect all" and then tick the checkbox for Android as shown. Click "OK" to continue.


![4](https://user-images.githubusercontent.com/68754864/96494595-30d18880-1264-11eb-8b41-3469de97fd8c.png)


Scroll all the way down, and click "Next Step".


![5](https://user-images.githubusercontent.com/68754864/96494596-316a1f00-1264-11eb-814e-f31320e5c922.png)


In the second step, select frequency "Export Once". The file type is your choice, most people are comfortable with .zip, pick the one you know you can open. .tgz files may require extra software on windows and mac, so .zip is safer for most. The default file size of 2GB (.zip) is perfectly fine. The download should not be too large (<100mb) depending on your usage.

Click "Create Export" and you're done! (almost)


![6](https://user-images.githubusercontent.com/68754864/96494598-3202b580-1264-11eb-8605-0c415020ab06.png)


Once you click "create export" you will see a new banner like this, telling you it is under way. The process only takes about 5 minutes.

**However** you may receive a notification on your phone and an e-mail from google, asking you to confirm it was you that requested an export. You may not recieve a download link till you open that e-mail/notification and click "yes". 

So check your e-mail!


![7](https://user-images.githubusercontent.com/68754864/96494600-329b4c00-1264-11eb-8fc3-c50fc6694cd1.png)


Now, you can sit back and wait for the e-mail from google, which can sometimes be delayed even though the process itself is quite fast.

Alternatively, should you reload the page, you will find a new banner on top, with a button for "Manage Exports" as shown below.


![8](https://user-images.githubusercontent.com/68754864/96494602-3333e280-1264-11eb-9783-3fd16e0bfc68.png)


Clicking it opens a new page with your history of exports, and it will say your export is in progress. If you're lucky, you'll see the export with the download link right away (granted you verified it from your e-mail or phone). If not, just wait and reload in a bit and you should get the download option.


![9](https://user-images.githubusercontent.com/68754864/96494604-33cc7900-1264-11eb-9f82-d90ccdc70ec5.png)


The download may require you sign-in again by entering your password.

Once you've downloaded it, open the archive (zip/tgz) using your favourite archive manager. (winRAR, 7z, etc.)(your OS (i.e. windows/mac may also support it within the file manager, so just double click and see what comes!)

Once open, go into the "Takeout" folder, then the "My Activity" folder, then the "Android" folder to find the "My Activity.html" file. 

in the archive: /Takeout/My Activity/Android/My Activity.html


![10](https://user-images.githubusercontent.com/68754864/96496886-76dc1b80-1267-11eb-9805-562158c3a71e.png)


Copy and save this file at a convenient location to upload in the next step.

We highly recommend opening the file yourself! The file loads a seemingly endless webpage with a list of app names and timestamps but no other details. Our process involving de-identification of the data at source (done by you) in the next step ensures we do not have a way of tracing the file directly back to you. 

If you are yet not comfortable sharing it with us as is, we also offer you the choice of extracting the information with the same method that we would use with the file, and checking the CSV file before sharing it with us. Click on the icon below to open a google colab notebook and follow the instructions within. It offers the option of removing appnames as well, but please consider not doing so to allow us the chance to do more interesting analyses with the data!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/delaiglesialab/DigitalRhythmsProject/blob/main/Android_Timestamps_Notebook.ipynb)

<hr>

Make sure you've obtained all the data types applicable,then continue by clicking <a href="https://delaiglesialab.github.io/DigitalRhythmsProject/Questionnaires">here.</a>
