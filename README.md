Universal Mute ([Download v1.0](https://raw.github.com/helgeblod/alfred-universalmute/main/universalmute.alfredworkflow))
=====================

Alfred App Workflow for muting videoconferencing apps with the same hotkeys across apps. 

## Requirements
1. [Alfred App v4](http://www.alfredapp.com/#download)
1. [Alfred Powerpack](https://buy.alfredapp.com/)

## Installing
1. Click the download buttons below
2. Double-click to import into Alfred
3. Review the workflow to add custom Hotkeys

## About
After working from home became the norm, my day consists of meetings in a myriad
of different videoconferencing apps. Muting the mic has become an essential
skill in this new world. I'm not really a fan of using the mouse for this, keyboard shortcuts are great for these tasks.  

There are [exellent solutions](https://mutify.app) for muting and unmuting you mic globally using
the mic input volume, but doing this has several shortcomings:

- No support for pro setups (like like my focusrite + XLR-mic)
- You will be asked to mute in meetings (because you are constantly unmuted)
- Admins in the meetings will mute you (they don't know about your awesome
  global volume muting)
- Some apps (eg. Google Meet) think your mic is not working when muted and will constantly hassle you 
- You need to configure a global shortcut so unmuting by accident can easily
  happen if you don't choose a really complicated hotkey

This workflow solves this by making it possible to add a set of hotkeys to
toggle mute for the most popular videoconferencing apps.

## How it works
The workflow is configured to only work when certain apps are in focus, and it
then binds the hotkeys to toggle mute for the particular app when in focus. This
has the added benefit of not interfering with the build-in shortcuts in other
apps, so the mute toggle can actually be something really simple (eg: double tap
command or option).

## Supported apps
- Zoom
- Dischord
- Slack App 
- Google Meet (Chrome, Chrome canary, Firefox, Safari, Vivaldi) 
- Skype for Business 

Adding support for more apps is a breeze, PRs welcome!

## Commands
Selected hotkeys will toggle mute/unmute in supported apps when app window is in focus 

## Contributors
- [@helgeblod](https://github.com/helgeblod)
