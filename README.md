# swsh-shiny-den-walkthrough
Documentation on finding a shiny den in SWSH with DUDU.

Remember: only save when prompted to. This walkthrough was created with assistance from [BLAINES's video](https://www.youtube.com/watch?v=awVEWio9feM). 

### Step 1: find den

Find a den with the appropriate beam color. If you're looking for a rare shiny, reset until you get a purple beam. Once you've found the desired beam:
 - disable auto-save
 - stand in front of the den if you aren't already
 - save the game

### Step 2: capture

Enter the den screen, start the battle, and capture the Pokemon that appears. We will be resetting the game later, so using masterballs is fine. You may want to write down the Pokemon you caught, as well as their star rarity, for future reference.

Do *not* save your game after capturing the Pokemon. 

### Step 3: trade with DUDU

Visit the DUDU website at http://116.202.105.91. The default tradecode will appear at the top of the page; it is currently 9162, but may change in the future.

![](https://i.imgur.com/eCmb3f3.png)

You'll have to initiate a link trade using this code and connect to the DUDU bot. This may take multiple attempts, as many other players are also trying to connect to it. The other player's name will display in the top right of the screen in the trade menu. If the name is *not* DUDU, exit out of the trade and try again.

![](https://i.imgur.com/y8poyl2.png)

Once you connect to DUDU, trade it the Pokemon you just caught from the den. The trade will be cancelled.

### Step 4: save seed & restart

After your trade with DUDU is cancelled, your seed will be displayed on the DUDU website (http://116.202.105.91).
![](https://i.imgur.com/cCnKB44.png)

Copy and save this seed. Quit SW/SH, and then re-open it. You should now be looking at the beam you used to catch the previous Pokemon with.

### Step 5: finding frame

Head over to [this seed checker](https://leanny.github.io/seedchecker/index.html) website. Fill in the information regarding your den, the Pokemon you encountered, and your seed. Enter 0 for *Start Frame*, and 10,000 for *Number of Frames*.

Click *Search Next Shiny Frame*. The next shiny frame will be displayed below. Keep track of the data displayed here.

### Step 6: setup for getting to frame

**Setup**:
Set your Nintendo Switch date to 01/01/2020. This makes tracking your destination date easier.

Save your game.

Travel to the nearest Pokemon center, and walk inside. This is done to prevent a crash that can occur in the next step.

Enter a ranked doubles battle and forfeit. Spam B to get back to the game. This is done to speed up the Date and Time skip exploit. Without it, you normally would have to re-enter your game and interact with the den. With it, you only have to hit OK after changing the console date.  

**Check-in**: you are now in a Pokemon center, and just lost a ranked doubles battle. You saved your game before going into the ranked doubles battle. With this, your console will date skip easier, and you won't crash due to your location.

**Next**:
Calculate *target_frame* days out from 01/01/2020 (which your console should be at). If your frame was 470, as shown in BLAINES video, your target date would be *April 15th, 2021* (04/15/2021). [Google can help with this.](https://www.google.com/search?q=470+days+from+january+1st+2020&rlz=1C1CHBF_enUS882US882&oq=470+days+from+january+1st+2020&aqs=chrome..69i57.5965j1j7&sourceid=chrome&ie=UTF-8). 

Store **this date** (04/15/2021) and **5 days before it** (04/10/2021). The latter date is used for manipulating what shiny appears in the den.

### Step 7: date skipping to frame

Enter your Nintendo Switch settings page, go to the Date and Time section, and increment the date by 1 (-> 01/02/2020). Hit the OK button. Repeat this process until hitting your -5 date (04/10/2021) **after reading the following note**:

*Note: re-enter your game and save every ~6 months. This can be used as a backup incase your game crashes.*

You're now at 04/10/2021. Enter your game, **save**, and **disconnect from the internet** in the Y-COMM. 

Now, using the old fashioned date skip method, advance 5 days (to the final, original date). As a refresher:
- enter den UI
- hit "Invite Others"
- go to Switch settings and increment Date & Time date by 1
- go back into the game, B out of the den UI, and repeat to the final date (5 times total).

If you enter the den now, the Pokemon will/should be shiny. You can verify as long as you don't save before-hand. We now know that shiny is 5 frames away-- the next step is manipulating what Pokemon appears.

### Step 8: manipulating shiny

Restart the game so you get to the state 5 days prior to your final date (or before the 5 old-fashioned skips). 

Old-fashioned skip 1 day, exit the den UI, and save your game. You are now 4 frames away from the shiny.

**Refresher**: after restarting your game, the first 3 Pokemon are the **same**. The 4th Pokemon *type* changes, but it's data (stats/shiny/HA) does *not* change. 

Repeat the following steps until the 4th Pokemon (which is shiny) is the one you want:
- date skip 4 days, old fashioned style
- check 4th Pokemon
- if not desired Pokemon, restart game

Catch and enjoy!
