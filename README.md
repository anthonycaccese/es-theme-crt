# CRT, an EmulationStation theme with video support
A simple theme for Emulation Station and RetroPie with support for the video view added by fieldofcows.  Originally based on the Carbon theme by Eric Hettervik; and then rebuilt from scratch so I could learn the theming system for ES.  Discussion ongoing in this thread: https://retropie.org.uk/forum/topic/7022/new-theme-crt-with-support-for-video-preview

---

### Updates

*5/3/2017*
- Updated CRT Bezel images from PNG to SVG to help with clean scaling on different resolutions
- Added future support for z-index layering being discussed in this thread - https://retropie.org.uk/forum/topic/9785/z-index-support-for-themes

*4/30/2017*
- Fixed box art scaling issue on video view
- Added 4x3 layout option
- Added display of genre and release date metadata
- Added backward compatibility check for older versions of retropie without video support
- Added child friendly ES support

*1/15/2017*
- Created "CRT Centered" theme variant - https://github.com/anthonycaccese/es-theme-crt-centered

*1/12/2017*
- Increased the size of boxart displayed on the video view
- Replaced genre and release date metadata with last played (genre and release date metadata does not appear to be consistent and last played does look like it will be more helpful overall)
- Tightened up spacing and reordered metadata on detail and video views

---

## Preview

### Video Walkthrough
https://www.youtube.com/embed/_elwCV5hxeA

### Screenshots

*Video View*
![Video View](http://i.imgur.com/e6y0kIl.png)

*Detailed View*
![Detailed View](http://i.imgur.com/tA6mfEc.png)

*Basic View*
![Basic View](http://i.imgur.com/npqHCZy.png)

*4x3 Layout*
![Basic View](http://i.imgur.com/pubsyyv.png)

[For more images view the album on Imgur](http://imgur.com/a/w7JNT)


## Details

- Has support for system, basic, detailed and video views
- Displays the following metadata on detailed and video views: rating, description, # of players, genre, publish date & last played
- Matching splashscreens are included in the \_inc/images folder
- 16x9 layout Tested on 720p and 1080p resolutions
- 4x3 layout tested on 480p/480i resolutions

## How to use

- Requires a Pi2/3 (videos are very choppy on a Pi0/1)
- Install latest version of retropie through the setup script (versions after 4.1.8 work)
- Add <video> elements to your gamelist to reference videos for each game on your pi (videos can be stored anywhere just like images)

## Possible Future Updates

- Support for marquee tag
- System specific backgrounds that match historical poster designs for a given system (I built an NES example to check out here: http://i.imgur.com/XCx3Tko.png)
- Grid view support

## Acknowledgments

- Inspired by old console poster designs (see: http://imgur.com/J4eeTun and http://imgur.com/Ut0SWfJ for examples) 
- All Logo graphics are from the default Carbom theme made by Eric Hettervik (see: https://github.com/RetroPie/es-theme-carbon/)
- Static.mp4 default video from OldRoom theme by Nismo (see: https://retropie.org.uk/forum/topic/5823/looking-for-testers-for-es-video-preview-on-raspberry-pi/20)
- Video support possible because of work done by fieldofcows (see: https://retropie.org.uk/forum/topic/4820/video-preview-in-emulationstation)
- Theme tutorial written by mattrixk was a huge help in learning how to build this (see: https://github.com/RetroPie/RetroPie-Setup/wiki/Creating-Your-Own-EmulationStation-Theme)
