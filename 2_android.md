# Step 1 of 2: Obtain the data

It's a short and simple process, but just to make it even easier for you we've documented almost every single click required. So don't you worry, it's not remotely as time consuming as it may seem from this long page.

### To obtain your Android app activity data:

First, click the following link to go to the <a href="https://takeout.google.com" target="_blank">Google Takeout service</a>.

<u>Important:</u> make sure you are signed into the same Google account that is the primary one on your Android phone.



Next, click on the **"Deselect all"** option, since we are only interested in the "My Activity" item.


![1](https://user-images.githubusercontent.com/68754864/96494580-2dd69800-1264-11eb-93a3-8a2270246b41.png)


Next, scroll down to find the **"My Activity"** banner. Tick the checkbox on the right, and then click the **"Multiple Formats"** button on the left.


![2](https://user-images.githubusercontent.com/68754864/96494591-2fa05b80-1264-11eb-8639-2863cdcbf71d.png)


In the pop-up that opens, make sure that the *Activity Records* value is set to **HTML** format like in the picture below <u>**and not JSON**</u>. Ignore everything else. Click **"Ok"** to continue.


![3](https://user-images.githubusercontent.com/68754864/96494593-3038f200-1264-11eb-87f8-0b629b36ce14.png)

Now click the button that says **"All activity data included"**. In the pop-up that opens, first click **"Deselect all"** and then tick the checkbox for **Android** as shown below. Click **"OK"** to continue.

![4](https://user-images.githubusercontent.com/68754864/96494595-30d18880-1264-11eb-8b41-3469de97fd8c.png)


Then, scroll all the way down, and click **"Next step"**.


![5](https://user-images.githubusercontent.com/68754864/96494596-316a1f00-1264-11eb-814e-f31320e5c922.png)



In the next page, under ***Frequency***, select **"Export Once"**. The ***File type and size*** is up to you; pick the one format you know your system will open (most people should be OK with the default *.zip* format).

Leave the default file size at 2GB. **But don't be scared!** The file you will end up downloading should not be nearly as large, and will be most probably smaller than 100MB depending on your phone usage.

Click **"Create export"** and you will be (almost) done!


![6](https://user-images.githubusercontent.com/68754864/96494598-3202b580-1264-11eb-8605-0c415020ab06.png)

Once you click "Create export" you will see a new banner like the one below, in which Google will tell you that the preparation of your file is under way.


![7](https://user-images.githubusercontent.com/68754864/96494600-329b4c00-1264-11eb-8fc3-c50fc6694cd1.png)

The process should only take about 5 minutes. **However, you may receive a notification on your phone and/or an e-mail from Google asking you to confirm that it was indeed you who requested an export. You will most probably not receive a download link for your file until you open that e-mail/notification and confirm**.

So you can sit back and wait to hear from Google, which can take as little or as long depending on the current workload of the Takeout platform. Feel free to come back to this point whenever you have the time to continue. Maybe better to go for a walk, take a bite, do some yoga stretches, or call a friend - just don't keep your eyes on the computer waiting for the file to be available :)

Should you reload the page, you will find a new banner on top, with a button to **"Manage Exports"**, as shown below.


![8](https://user-images.githubusercontent.com/68754864/96494602-3333e280-1264-11eb-9783-3fd16e0bfc68.png)


Clicking it opens a new page with your history of exports, and it will confirm that your export is in progress. If you're lucky, you'll see the already available export file and the download link (provided that you verified it from your e-mail or phone). If not, just wait and reload in a couple of minutes and you should get the download option soon.


![9](https://user-images.githubusercontent.com/68754864/96494604-33cc7900-1264-11eb-9f82-d90ccdc70ec5.png)


The download may require you re-sign in to Google by entering your password. Once you've downloaded the export file, open the compressed archive  using your favorite archive manager (your computer may already be able to do this by nature).

Once open, go into the ***"Takeout"*** folder, then the ***"My Activity"*** folder, and finally the ***"Android"*** folder to find the ***"My Activity.html"*** file.


![10](https://user-images.githubusercontent.com/68754864/96496886-76dc1b80-1267-11eb-9805-562158c3a71e.png)


Copy and save this file at a convenient location to upload in the next step.

**And that's it! Congratulations! You already have your Android phone apps usage data and you are done with this stage of the process.**

We highly recommend you to open the file for yourself, if you'd like. The file will load a seemingly endless webpage with a list of app names and timestamps - **but no personal details whatsoever**.

Once you're comfortable with sharing the file with us anonymously, click the button below.

[<img src="https://user-images.githubusercontent.com/42762378/101690680-9dfae080-3a93-11eb-8552-e4a65f2babfc.png" height="30" width="120">](https://delaiglesialab.github.io/DigitalRhythmsProject/questionnaires-an)

<hr>

However, if you are still concerned, we offer you the choice of extracting the information and obtain a simpler CSV file with no app names before sharing it with us. Click on the icon below to open a ***Google Colab*** notebook and follow the instructions within - but before you do it, please consider the option of sharing the original file with us to allow us the chance to do more interesting analyses with the data! Remember, your data will be anonymized and kept totally secure. If you still feel you'd prefer to erase all application names from the file, open the link below and follow the instructions before continuing.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/delaiglesialab/DigitalRhythmsProject/blob/main/Android_Timestamps_Notebook.ipynb)

After you've obtained the CSV file from the Colab notebook, continue by clicking <a href="https://delaiglesialab.github.io/DigitalRhythmsProject/questionnaires-an">here.</a>
