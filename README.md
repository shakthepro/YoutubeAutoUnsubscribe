# YoutubeAutoUnsubscribe
 
 ## Description
 Get rid of the bunch of accounts you did want to subscribe in minutes.

 ## Preperation:
 1. You want to login to your youtube account that you wish to get rid of the subscriptions on masse.
 2. You want to go through your subscripition list on the side menu on the youtube main page.
 3. Find the account you wish you dont want to subscirbe to no longer and open it in a new tab. Either with holding down the ctrl button and clicking on it or right clicking and pressing "Open link in new tab."
 4. NOTE: You want lots of ram to be able to do this with like 50 plus accounts as Chrome consumes lots of ram. 
 5. The top of your screen should look like this: 
 ![tabList] (YoutubeAutoUnsubscribe\images\tabList.png)

 ## How to use:
 1. Clone the repository or simply copy and paste the code in the unsubscribeFunc.py and the locateCoords.py to your local machine.
 2. Use the locateCoords.py code to find the "Subscribe" button on a youtube channel. 
 ![youtubeImage1] (YoutubeAutoUnsubscribe\images\youtubeIMG1.png)
 3. Then use the code to find the "Unsubscribe" button once the pop up has shown
 ![youtubeImage2] (YoutubeAutoUnsubscribe\images\youtubeIMG2.png)
 4. Lastly, use the code to find the "Unsubscribe" confirmation popup button
 ![youtubeImage3] (YoutubeAutoUnsubscribe\images\youtubeIMG3.png)
 5. Finally, you need to get the coordinates from these three location into the unsubscribeFunc.py into the apporiate locations. 
 6. For instance, the subscribe button will be the first coordinate found in step 2 and so on.


 # Last Step
 1. After plugging in the numbers, you want to run the unsubscirbeFunc.py code in VSCode or in the terminal and tab into the Chrome window with all of your youtube channels open.
 2. Wait a few seconds and let the code do its magic.

 # Note
 I am not responsible for any damage if you run out of memory and your computer shuts down, SAVE ALL UNSAVED WORK.
 I am not responsible if this does not work for you. 
 There is a 85% success rate as  the subscribe button moves because some channels do not have a channel banner or the description is not there. This makes the button move as some elements are either too long or not in the right place.
 I hope this program works for you. Its simple and gets the job done.