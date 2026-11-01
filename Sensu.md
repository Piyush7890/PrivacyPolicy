# Sensu privacy policy

Effective 2026-10-31

## The short version

Sensu has no account, no analytics and no ads, and there is no Sensu server. What it reads to work is read on your phone and used there, and none of it is sent anywhere.

## Accessibility service

The accessibility service is what Sensu runs in. It draws the pie and its handles over other apps, passes a tap or swipe on a handle that doesn't open the pie on to the app under it, and carries out the slices you choose: back, home, recent apps, the notification shade, lock, screenshot and the rest.

It checks where the keyboard is, so a handle can sit above it. It notices which app is open, so the handles can step aside in games, in full-screen video and in apps you pick, so App info and Current app act on that app, and so Recent apps can show the last few apps you used. That list is kept in memory only, never saved or sent, and is gone when Sensu or the phone restarts. For Page up, Page down and Scroll to top it finds the list on screen and asks it to scroll.

For Force stop in Current app, unless you use Shizuku, it opens that app's page in Settings and presses Force stop there, then OK on the question that follows, as you would. It finds those two by the words Settings itself shows for them.

Apart from that, it doesn't read the text on your screen.

## Apps and shortcuts

To let you put apps and shortcuts in the pie, Sensu lists the apps on your phone that have a launcher icon or offer shortcuts, with their names and icons, and the shortcuts they offer. They are read on your phone to show them in the pie and its pickers, and kept nowhere else. A shortcut you put in the pie is saved on your phone with your other pie settings: its name, its app and what it opens, which for some shortcuts is a contact or a place you picked in that app.

## Media and video

To step aside in full-screen video, Sensu asks Android whether something is playing. It learns only that something is, never what.

## Settings Sensu can change

The brightness slider, and slices like auto-rotate and screen timeout, change those settings only once you allow Modify system settings. Night Light, inversion, grayscale and animation speed need advanced access, which you give over adb yourself. Slices that only the shell can do run through Shizuku, only once you allow Sensu in Shizuku's app. Each changes only the setting you move it to.

The flashlight slice turns on the camera's light. It never opens the camera.

## Notifications and Do Not Disturb

Clear notifications and Now playing work only once you turn on notification access for Sensu. Android says an app with it can read your notifications. Sensu never reads, keeps or sends them: it connects only for the moment it clears them. Now playing reads what is playing from the app playing it (the title, the artist, the cover and how far through it is) to show it in the pie, and passes on to that app the buttons you press there. It keeps none of it and sends none of it anywhere. Do Not Disturb and Sound mode change those settings only once you allow Do Not Disturb access, which notification access also brings.

## Calendar

Calendar works only once you allow Sensu to read your calendar. It reads today's and the next two days' events (their titles, times, whether they're all day and whether they're busy or free time) to show what's left of your day in the pie, and looks through their place, their notes and the Meet link Google Calendar keeps with them only to find a link to join a call. It reads each event's guests' names and email addresses only to offer you an email to them, which your email app writes and you send. It never changes your calendar, and keeps none of it and sends none of it anywhere. Opening an event or starting a new one is done by your calendar app.

## Screenshots

The screenshot slice asks Android to take one, as the power and volume buttons do. Android saves it; Sensu never sees it.

## Backups

Export settings writes your slices, rings and looks to a file in the place you choose, and Import settings reads the file you pick. Sensu never uploads either. If Android's own backup is on, your phone may include Sensu's settings in the copy it keeps in your Google account, as it does for other apps.

## Google Play

When you open Sensu, it asks Google Play whether a newer version is out, so Google Play can offer it to you. Once you have used Sensu for a while, it may also ask Google Play to show its rating card. Both are Google Play's, under Google's own privacy policy, and Sensu never learns whether you rated it or what you wrote.

## Bug reports and email

Report a bug opens your email app with Sensu's version, your phone's model and its Android version filled in. Nothing is sent until you send it, and you can change or delete any of it first. Emails are used only to reply to you.

## Changes

A new version of this policy comes with an update to Sensu, under a new effective date.

## Contact

Questions about this policy: oto.music121@gmail.com
