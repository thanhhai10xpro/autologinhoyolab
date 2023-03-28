<h1 align="center">
  <br>
  <a href="https://github.com/thanhhai10xpro/autologinhoyolab"><img src="https://cdn.donmai.us/sample/98/a6/__elysia_and_elysia_honkai_and_1_more_drawn_by_jubeol126__sample-98a62a7ba84e8ff8d1b501979cec2296.jpg" alt="Red - Discord Bot"></a>
  <br>
  Hoyolab Auto Daily Check-in
  <br>
</h1>

<!-- <p align="center">
  <a href="#overview">Overview</a>
  •
  <a href="#installation">Installation</a>
  •
  <a href="#license">License</a>
</p> -->


# Overview
Hoyolab auto daily check-in - this is a simple program that allows you to always claim daily login rewards from hoyolab, supports the game Genshin Impact & Honkai Impact 3rd

# Installation
1. Make a WayScript Account
https://wayscript.com/home

2. Download the Script<br>Click +New Lair -> Github URL and insert my link: <br>https://github.com/thanhhai10xpro/autologinhoyolab<br>
![(clone)](https://imgur.com/gallery/YXWTRNe)

3. Set up the time<br>
![(time)](https://i.imgur.com/ECpJlSY.png)

4. Set up the .secrets <br> Add the keys `COOKIE` and `USER_AGENT`, the `DISCORD_WEBHOOK` is optional, see at end of page for webhook instructions<br>
![](https://i.imgur.com/Qf9l2JH.png)
<br>**How to get OS_COOKIE ?**
<br>1\. Go to the Hoyolab website https://www.hoyolab.com/
<br>2. Login with your account
<br>3. Open the developer tools on your web browser (F12 on firefox/chrome)
<br>4. Click on the “Console” tab
<br>5. Type in  `document.cookie`  in the console
<br>6. Copy all text output from console without quotes `'`
<br>7. **PLEASE DON'T SHARE YOUR COOKIE TO ANYONE**
![(token)](https://i.imgur.com/7fSEeB8.png)
<br>**Multiple account**
<br>The multi-account feature will make the program run multiple accounts in one run. Use the features properly !.
<br>in the `COOKIE` variable add a separator with `#` character for each cookie, example:
![](https://i.imgur.com/urZRZLq.png)
<br>**How to get USER_AGENT ?**<br>
You can get your user agent like so:
![enter image description here](https://i.imgur.com/Jy07NPf.png)
<br>**How to get DISCORD_WEBHOOK ? (OPTIONAL)**<br>
Goto [Discord Webhook Configuration](#discord-webhook-configuration)If you want to setup discord webhook.
1. Run the script <br>
![](https://i.imgur.com/MvFMagm.png)
![](https://i.imgur.com/YqqP1Wc.png)

# Discord Webhook Configuration
This is an  **OPTIONAL**  step to let the script send you a notification on Discord whenever it runs a check-in.
1. Create your own discord server and private channel.<br>
![](https://i.imgur.com/eY4HkBP.png)
2. Edit channel settings<br>
3. Go into Integrations and view webhooks.<br>
![](https://i.imgur.com/Euo2CX2.png)
4. Create a new webhook and copy the URL.!<br>
![](https://i.imgur.com/3c7yuCi.png)
5. Go back to the “.secrets” tab and add a new secret called DISCORD_WEBHOOK.<br>
