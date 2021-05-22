# Step 1 of 2: Obtain the data

It's a short process that's really easy, but just to be clear we've documented each click required. So don't you worry, it's not remotely as time consuming as the length of this page makes it look.

### To obtain your Android app activity data:

The first step is to click the link below to go to the google takeout service.

### <a href="https://takeout.google.com" target="_blank">takeout.google.com</a>

ensure you are signed into the same account as the primary one on your android phone.

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

You're done with this stage of the process!

We highly recommend you to open the file yourself! The file loads a seemingly endless webpage with a list of app names and timestamps but no personal details. In the next stage of the process (after you click continue), you will receive a code and rename the file with it, such that it cannot be identified back to you.

Once you're comfortable with sharing the file with us anonymously, click the button below.

[<img src="https://user-images.githubusercontent.com/42762378/101690680-9dfae080-3a93-11eb-8552-e4a65f2babfc.png" height="30" width="120">](https://delaiglesialab.github.io/DigitalRhythmsProject/questionnaires-an)

<hr>
<hr>
<hr>

However, if you are still concerned, we offer you the choice of extracting the information with the same method that we would use with the file, and obtaining a CSV file before sharing it with us. Click on the icon below to open a google colab notebook and follow the instructions within. It offers the option of removing appnames as well, but please consider not doing so to allow us the chance to do more interesting analyses with the data!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/delaiglesialab/DigitalRhythmsProject/blob/main/Android_Timestamps_Notebook.ipynb)

Once you've obtained the CSV file from the notebook, continue by clicking <a href="https://delaiglesialab.github.io/DigitalRhythmsProject/questionnaires-an">here.</a>
