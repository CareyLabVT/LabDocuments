# Cheatsheet for using Fluoroprobe ("Flora")
*Last updated 11 Sep 25 by MEL and ABP*

### Field Tips

#### *Taking a cast with Flora*

**1.** Unscrew the travel cap and plug in the autostart plug (only other plug in the case).

**2.** Flora will go through a warm-up sequence that takes at least 30 seconds or so  

* Fast orange blink  
* Slow and steady orange blink  
* Slow and steady green blink  
* **The color of the blink indicates the charge of the battery; Flora is perfectly capable of taking data while blinking orange if her battery is low.  If you know she should be fully charged, try for green, but if after several attempts/minutes all she’ll do is blink slow and steady orange, go ahead and take the cast.  You are still likely to get perfectly good data!**  
* If Flora’s warm-up sequence is abnormal, abort the mission by unplugging the autostart plug. Then try again. Sometimes it takes her a couple of tries to get going.
* *I'm thinking we may need to add additional tips here given recent quirkiness with Flora?*

**3.**	**MAKE SURE YOU ARE STABLE AND THE ROPE ORGANIZER IS SECURE. THIS INSTRUMENT COSTS ~$60,000 AND WE DON’T WANT TO LOSE IT IN THE RESERVOIR!!!**

**4.**	Slowly lower Flora – she takes a reading once every 3 seconds, so think about a speed of about 30 seconds/meter for a 10 cm resolution. This means a cast at FCR should take ~5 minutes!

**5.**	When you hit bottom, bring her back up!

**6.**	Disconnect the autostart plug and replace the travel cap – it’s that simple!

******

#### *Downloads with Flora and Checking the Chlorophyll Maximum Depth (adapted from Kate Hamre's 2015 instructions)*

**1.** **Approach Flora in a friendly but firm manner.**  Under no circumstances should she sense fear or hesitancy on your part.

**2.** **Remove the travel cap/autostart plug and ensure the shuttle port is dry** (a good ole Nintendo blow is a great way to accomplish this).

**3.** **Plug in computer cord to Flora** (thick rubber cable; has heart-shaped prongs).

**4.** **Plug in connector cord USB (red) to lab field computer (Hindsight).** 

**5.** **Log into computer** if you have never set up an account on the field computer it could take up to 20 minutes to create the account. If you are in the field, have someone who already has an acocunt log in. 

  * Username: VT PID
  * Password: your PID password

**6.** **Open bbe++ software;** the laptop will ask for permission to allow the software to open/make changes --> click Yes! 

**7.** **Check that Flora is connected.**  There should be a green circle below the “window” tab in the menu.  If this circle is orange, you can click on it and tell the computer to search for the device. If it is still orange then try unplugging and replugging the cable from the instrument.  If the circle is black, the computer is not even attempting to connect; in this case, you can close and re-open bbe+.  If you still have no luck, find a buddy to help you troubleshoot. 

**8.** **Click “Get data”** in menu bar.

**9.** **Have a snack.** (download can take a while)  

  * If the download fails, try again.  Sometimes it takes a couple of tries to work.

**10.** **Navigate your data.** Use the small black arrows in your tool bar to click back and forth between different casts. Sometimes, if casts are taken very close together in time, the software will combine them into one observation. This is ok! We’ll just acknowledge that in the naming protocol.

**11.** **(For in the field only.) If you are taking a phytoplankton sample, check the Chlorophyll Maximum Depth.*** If you are collecting phytoplankton samples from the Chlorophyll Maximum, you will use the FluoroProbe cast to find the depth of the Chlorophyll Maximum. After you have downloaded the FluoroProbe file, check to see where the highest concentration of phytoplankton is. To do this, find the greatest value in the "Total Concentration" column. If the reservoir is fairly mixed and the "Total Concentration" does not change very much across the water column, then you can take the sample from 1.6 m. Once you have identified the Chlorophyll Maximum Depth, close the computer as you will clean up the casts when you get back to the lab. 

**11.** **Manually “clean up” each cast.**

a.	Select the first data point, then control+shift+arrow down until you see the beginning of your cast.  You can also hold control and click on the casts you would like to delete. 
b.	There will be a few readings at a constant, shallow depth before she starts taking data.  You can delete these.  I usually delete everything shallower than 0.2 m because of light quenching. Be careful not to delete data you need!     
c.	Delete data by right-clicking in the selected data and selecting “Delete data”; delete only the selected data.
d.	Continue scrolling through your data and use the depth of the cast and the timestamp to make sure you have the right reservoir/site.
e.	Delete the upcast (everything after the deepest point of the cast). Becareful because some of the casts will be combined. Look at the time stamp to determine if there are multiple casts and do not delete them. 

**12.** **Export the cast.**  Go to File -> export (ASCII) and export into the Raw_fluoroprobe folder on the C:\ drive (this should be the folder automatically called when you save the file) with the appropriate filename 

a.	YYYYMMDD_RESERVOIR_SITE
b.	Ex: 20240604_FCR_50
c.	Every cast should be exported individually, e.g., if casts are taken at both Sites 10 and 20 in FCR, you should select the relevant observations for each cast and export them separately as 20240806_FCR_10 and 20180806_FCR_20. If casts from different sites end up in the same file. I will save both of the casts together and export the file. Then copy the text file and clean it in the Notepad program. 
d.	Your cast will be exported as a .txt file

**13.** **Continue with navigation, cast editing, and exporting** until you have processed all the casts for the day.

**14.** **Back dat cast up. Put files on GitHub**  

a. Open up your GitHub account and go to your forked Reservoirs repo. If you don't have the Reservoirs repo ask someone else to upload the files for you. Then go to the Get Going in Git tutorial. 
b. Make sure your repo is up to date.
c. Go to Reservoirs-> DataNotYetUploadedToEDI-> Raw_fluoroprobe folder
d. Click on the "Add File" button in the top right hand corner and select "Upload files"
e. In the file manager window open the C drive on the computer and go to the folder where you save the casts. It should be C:\GitHub\Reservoirs\Data\DataNotYetUploadedToEDI\Raw_fluoroprobe
f. Select the files your want to add and drag to the "Drag files here to add them to your repository"
g. Add a description to your committ. I usually say DATE RESERVOIR Fluoro files
h. Click on the commit changes button
i. Now create a pull request to add the files to the main repository. (If unsure see instructions on how to do this)

**15.** **Log out of all accounts and shut down computer**

******

#### *Prepare for next field day*

**1.** **Clean the bottom of the instrument.** Dirt likes to get stuck in the cover. In the sink, squirt some water between the bottom of the instrument and the plate attached to the bottom of the instrument. Twice a year or when she is really dirty, take off the bottom plate with a screw driver and clean that out. Then reattach the plates.

**2.** **Check with the field crew to see if she needs to be charged.** If the top LED never turned green when she started up or the LED stopped blinking at the end of the cast, charge her. 

a. Attach the cable as if you were downloading files. You can also do this after downloading files.  
b. Open BBE+
c. Make sure Flora is connected (see instructions above)
d. Click on the "Edit Parameters" button near the connected circle
e. Find the "Begin Measurement on Start up" parameter and change this to "No"
f. Save and apply the settings
g. Close the program and shut down the computer
h. Plug the charger into the wall outlet. Check the LED on the top of her and unplug when it is green. DO NOT LEAVE HER PLUGGED IN OVER NIGHT. This will cause the battery to overcharge and malfunction.
i. Once she is charged open the program and change the setting line "Begin Measurement on Start up" back to "Yes". Save settings. If you do not do this she will not record data in the field. 

**3.** **Let her air out between field days** Leave her standing up with all caps off of the top plug. Before the field day, attach the flat screw-on plug to the top of her and then pack her up in the case. 

