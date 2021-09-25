# Bridge of Dawn

*Bridge of Dawn* is a free, open-sourced 3D arcade/racing style game for Windows, OS X, and Linux. It was created for the 2021 Epic MegaJam by Kimberly Blais of [Mama Makes Games](https://www.mamamakesgames.com). *Bridge of Dawn* features music by Australian hip-hop star [YNG Matryr](https://open.spotify.com/artist/357dDcxIE2hkKGn03PClIF), rising artist YNG SiLICON, and Madame X

The source code and Unreal Engine 4 project for this game is available for free under the MIT Open Source license. You can download this project to learn how the game was made, make any changes you'd like, and then release your own version of the game! Just install [Unreal Engine](https://www.unrealengine.com), clone this repository, and open the `BridgeOfDawn_UEProj.uproject` file to get started. If you're comfortable sharing, I'd love to know what you make with it, so send me an email at kim@mamamakesgames.com or let me know on [Instagram](https://www.instagram.com/mamamakesgames/) with #bridgeofdawn. 

More information about the game can be found at http://www.bridgeofdawn.com 

## IMPORTANT: How to get the current source

The game was originally made using some free assets from Epic's "permanently free" collection. I had tried to keep these assets fairly minimal to keep the game under 1 GB in order to avoid using Itch.Io's `butler` upload tool. As fate would have it, the game ended up being slightly over 1 GB and I scrambled to upload it before the jam closed. Fortunately, `butler` was easy to use (though very slow uploading), and *Bridge of Dawn* was uploaded before the jam closed with minutes to spare.

After the jam closed, I switched to [Landscape Pro 2.0]
(https://www.unrealengine.com/marketplace/en-US/product/landscape-pro-auto-generated-material), which was also part of the permanently free collection but quite a bit larger. This led me to a new discovery: GitHub has a 10 GB repository limit. After wrestling to keep within this for several days, I stopped trying to host the code on GitHub and now the source code is available here:

[https://www.dropbox.com/sh/usobnsuqcuq3fbs/AAA5IXEZqfpcEtwhvLhM8OERa?dl=0](https://www.dropbox.com/sh/usobnsuqcuq3fbs/AAA5IXEZqfpcEtwhvLhM8OERa?dl=0)

(This is a 5.7 GB zip file download!) The GitHub repository might remain interesting to some, however, as it shows the game's development during the game jam week.

## Download and Play

The game is currently available pre-built for Windows 64-bit systems here (~1.6 GB):
[https://www.dropbox.com/sh/6e6kwh84y9b6aoi/AAAAZtzvnK7jm0qS3C5TEa9qa?dl=0](https://www.dropbox.com/sh/6e6kwh84y9b6aoi/AAAAZtzvnK7jm0qS3C5TEa9qa?dl=0)

## Features

- Exciting arcade-style gameplay featuring one- and two-player support, with two different multiplayer modes
- Easy-to-learn, hard-to-master action with shareable score/time screenshots for bragging rights
- A fun fairytale-like story drawn from the fantasy world of the [Isle of Mist](https://www.thelostweld.com)
- Animated cutscenes with voice-acting by professional voice actor [Erica Schroeder](https://www.ericaschroeder.com/)
- Available in English, Spanish, and Chinese, with full translation of subtitles and user interface
- Dynamic music that adapts to your progress and performance
- Highly scalable graphics with NVidia Real-Time Ray Tracing (RTRT) support
- Created by an all-female team led by [Kimberly Blais](https://www.instagram.com/mamamakesgames/) from [Mama Makes Games](https://www.mamamakesgames.com)
- Available for completely free to download, play, and modify however you'd like

## Technical Aspects

If you're looking for an example of how to do certain things in the Unreal Engine, this project might be helpful. Here are some of the interesting engine features or techniques this project implements:

- Procedural foliage generation
- Dynamic music
- Decision-tree based AI with hearing and seeing
- Actor-to-actor socketing (used by the Timekeepers "riding" and "holding" the fox)
- Subtitles and localization
- MP4 display within a cinematic sequence
- Local multiplayer
- Adjustable graphics quality
- Angle-based velocity adjustments (faster downhill, slower uphill)
- ...and the usual suspects like landscapes, saving game settings, HUDs, multilevel game state, etc.
