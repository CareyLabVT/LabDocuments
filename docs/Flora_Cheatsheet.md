# Cheatsheet for using Fluoroprobe ("Flora")
*Last updated DD Mon. YYYY by MEL and ABP*

### Field Tips

#### *Taking a cast with Flora*

**1.** Unscrew the travel cap and plug in the autostart plug (only other plug in the case).

**2.** Flora will go through a warm-up sequence that takes at least 30 seconds or so  

* Fast orange blink  
* Slow and steady orange blink  
* Slow and steady green blink  
* **The color of the blink indicates the charge of the battery; Flora is perfectly capable of taking data while blinking orange if her battery is low.  If you know she should be fully charged, try for green, but if after several attempts/minutes all she’ll do is blink slow and steady orange, go ahead and take the cast.  You are still likely to get perfectly good data!**  
* If Flora’s warm-up sequence is abnormal, abort the mission by unplugging the autostart plug.  Then try again.    Sometimes it takes her a couple of tries to get going.
* *I'm thinking we may need to add additional tips here given recent quirkiness with Flora?*

**3.**	**MAKE SURE YOU ARE STABLE AND THE ROPE ORGANIZER IS SECURE. THIS INSTRUMENT COSTS ~$60,000 AND WE DON’T WANT TO LOSE IT IN THE RESERVOIR!!!**

**4.**	Slowly lower Flora – she takes a reading once every 3 seconds, so think about a speed of about 30 seconds/meter for a 10 cm resolution.

**5.**	When you hit bottom, bring her back up!

**6.**	Disconnect the autostart plug and replace the travel cap – it’s that simple!

******

#### *Downloads with Flora (adapted from Kate Hamre's 2015 instructions)*

**1.** **Approach Flora in a friendly but firm manner.**  Under no circumstances should she sense fear or hesitancy on your part.

**2.** **Remove the travel cap/autostart plug and ensure the shuttle port is dry** (a good ole Nintendo blow is a great way to accomplish this).

**3.** **Plug in computer cord to Flora** (thick rubber cable; has heart-shaped prongs).

**4.** **Plug in connector cord USB (red) to Christ book.** *This is definitely not the computer we are using and I am not sure the cord is still red either?*

**5.** **Wake up computer** *What updated computer information should be added here?*

  * Username: CNTRLSRVS\CareyLab
  * Password: *see computer*

**6.** **Open bbe++ software;** the laptop will ask for permission to allow the software to open/make changes --> click Yes! *Has any of this changed in newer versions of bbe++ or are we using same version?*

**7.** **Check that Flora is connected.**  There should be a green circle below the “window” tab in the menu.  If this circle is orange, you can click on it and tell the computer to search for the device.  If the circle is black, the computer is not even attempting to connect; in this case, you can close and re-open bbe+.  If you still have no luck, find a buddy to help you troubleshoot. *Any other troubleshooting tips that need to be added?*

**8.** **Click “Get data”** in menu bar.

**9.** **Have a snack.** (download can take a while)  

  * If the download fails, try again.  Sometimes it takes a couple of tries to work.

**10.** **Navigate your data.** Use the small black arrows in your tool bar to click back and forth between different casts. Sometimes, if casts are taken very close together in time, the software will combine them into one observation. This is ok! We’ll just acknowledge that in the naming protocol.

**11.** **Manually “clean up” each cast.**

a.	Select the first data point, then control+shift+arrow down until you see the beginning of your cast.  
b.	There will be a few readings at a constant, shallow depth before she starts taking data.  You can delete these.  I usually delete everything shallower than 0.2 m because of light quenching. Be careful not to delete data you need!     
c.	Delete data by right-clicking in the selected data and selecting “Delete data”; delete only the selected data.
d.	Continue scrolling through your data and use the depth of the cast and the timestamp to make sure you have the right reservoir/site.
e.	Delete the upcast (everything after the deepest point of the cast)

**12.** **Export the cast.**  Go to File -> export (ASCII) and export into the Flora 2018 folder (on the Desktop) with the appropriate filename *(does this still happen?)*

i.	YYYYMMDD_RESERVOIR_SITE
ii.	Ex: 20240604_FCR_50
iii.	Every cast should be exported individually, e.g., if casts are taken at both Sites 10 and 20 in FCR, you should select the relevant observations for each cast and export them separately as 20240806_FCR_10 and 20180806_FCR_20
iv.	Your cast will be exported as a .txt file

**13.** **Back dat cast up.**  *What do we want to say here now? We haven't talked about GitHub at all and I think we need to include getting the cast to GitHub?*

**14.** **Continue with navigation, cast editing, export, and backing up** until you have processed all the casts for the day.
