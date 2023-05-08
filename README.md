An autostart (half-way kiosk mode) for the Quest AppLauncher on the Oculus Quest 1/2<br>
Why only half way? Because it does not restart the AppLauncher after it has been exited, and the menu button is not being disabled.<br>
This is a fork of https://github.com/weimingjue/AccessibilityExample<br>

1.) Install the QuestAppLauncher<br>
https://github.com/tverona1/QuestAppLauncher

2.) Enable developer mode<br>
https://www.youtube.com/watch?v=mxzkVtrUWzc

3.) Disable the Guardian<br>
https://uploadvr.com/how-to-disable-quest-guardian/

4.) Enable Multitasking<br>
https://vrscout.com/news/oculus-quest-update-multitasking-mic-swap-more/

5.) Install QuestKiosk through SideQuest<br>
https://sidequestvr.com/<br>
https://github.com/DennisHeine/OculusQuestKiosk/releases/tag/v1.0

6.) Start QuestKiosk <br>
Start QuestKiosk through the "unknown sources" menu

7.) Enable the accessibility service<br>
Enable QuestKiosk<br>
<b>UPDATE NEW FIRMWARE:</b> <br>
-install ADB and grant debugging permissions inside the headset<br>
-run the following command: adb shell settings put secure enabled_accessibility_services com.heine.dennis.hongbaotest/com.heine.dennis.QuestKiosk.HongBaoService<br>
<br>
8.) Restart<br>
Restart your Oculus Quest 1/2
