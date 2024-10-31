# Skin.Estuary.PVR.plus.omega

EstuaryPVR+ (omega) is a modification of the default Estuary skin, originally written by Phil65 and now maintained by Team Kodi.
This skin aims to offer users some additional PVR features that are not currently available on the default version of Estuary. It also offers some new skin views and a more detailed OSD, whilst remaining a very light weight and easy-to-use skin.
 
### Dependencies

EstuaryPVR+ (omega) does not require any additional dependencies to work. However, some additional PVR features will only work when the Skin.Helper.Script is installed. This addon can be downloaded from here [https://github.com/Fuchs246/repository.fuchs246]

# License

This work has been released under GNU General Public License (GPL), Version 2.0

# New Features Added

(Global)
- Colourised OSD and media flags throughout.
- New smaller posters displayed on Home Screen for movies and TV Shows.
- New OSD layouts and buttons added throughout skin, including new info OSD dialogs .
- 3 new colour themes added to skin (Black, Cobalt (blue), Claret (red)
- 3 new skin views added (Flix Large, Flix Wide and Flix Landscape)

(Live Tv)
- New PVR settings added to skin settings with additional Live TV options.
- Artwork supported on all PVR screens (Can be used individually or combination of Backend, Local and Skin Helper)
- Now/Next programmes displayed on new Live TV OSD layout.
- New 'Last Channel Played' button added to Live TV OSD that switches back to last live tv channel played.
- New TV Channel Screen layouts including Now/Next view. ('Next' artwork only works when local artwork is enabled, otherwise default fallback image is displayed)
- New Layouts for TV Recording and Timer Screens.
- New Layout for OSD Channel Guide.
- New PVR Info Dialog in line with the look of the Video and Music Info Dialogs.
- PVR Recording artwork displayed on Home Menu (Only works when local artwork is enabled, otherwise default fallback image is displayed.)
- Banner Artwork dialog for 'Next/Up' TV Programme appearing 30 seconds before next programme start (Enabled via new PVR Settings in the skin settings or via PVR Sideblade on the EPG screen. This feature only works when local artwork is enabled, otherwise default fallback image is displayed).
- Ability to disable TV Groups from EPG (Via new PVR Settings in the skin settings or via PVR Sideblade on the EPG screen).
- Ability to disable Live TV Genre Colours (Via new PVR settings in the skin setings or via PVR Sideblade on the EPG screen).
- Ability to display actual premiered flags on EPG instead of a '*' as the indicator (Via new PVR settings in the skin setings).
- Movie clapperboard icon added to genre on EPG Screen if genre contains 'Movie or Film'
- New 'Day' indicator added to plot panel on OSD Guide.

(Movies)
- New OSD Layout for Movies.
- New Actor button added to Movie OSD which opens new OSD dialog showing actors for movie being played.
- Ability to add movies to 'Watchlist' via button on 'Flix Large' view or via context menu on any other skin view. (Needs Metedata Editor installed)
- New 'Watchlist' and '4K Movies' added to catagories on Movie Home Menu.
- New 'Watchlist' and '4K Movie' widgets added to Movie Home Menu.
- New 'Decades' widget added to Movie Home Menu which allow you display movies in library by decade.
- New content flags added to OSD and Flix views to display if movie is 'Kodi Local library', 'Netflix', 'Prime', 'iplayer' or 'YouTube'.
- Ability to display clearart above the OSD via the OSD settings or using Skin Settings.

(TV Shows)
- New OSD Layout for TV Shows.
- New Actor button added to TV Show OSD which opens new OSD dialog showing actors for TV show being played.
- Ability to display clearart above the OSD via the OSD settings or using Skin Settings.

(Music)
- New OSD Layout for Music.
- Animated graphic equilizer added to Music OSD when music is playing.
- New Artist Biography button added to Music OSD which opens Music Artist OSD dialog.
- Next 3 tracks coming up shown on the bottom left hand side of  music OSD.
- Support for Fake Disc Art added if no original album disc art exists. If clearlogo is avilable, this will be added to fake disc, other text will be used.
- Ability to enable Disc Art via Music OSD settings.
- Ability to enable Artist Clearlogo via Music OSD Settings.
- Ability to enable scrolling text via Music OSD Settings.
- Ability to switch from colorised equalizer on Music OSD to plain white colour using OSD settings.
- New Recommended Songs Widget added to Music Home Menu.

(Music Videos)
- New OSD Layout for Music Videos.
- New Playlist button added to OSD so users can now view queued Music Video's.

# PVR Artwork

PVR Artwork was an area I specifically wanted to try and improve upon for this skinning project and EstuaryPVR+ lets users decide how they want to fetch the PVR Artwork for their Live TV Set-up.
The following 3 options are available:-

1) Use 'Backend' for PVR Artwork.
2) Use 'Skin Helper Script'  
3) Use 'Local PVR Artwork'

These options can be found under the new 'PVR Settings' heading of the Skin settings option and can be used individually or in combination with each other.
Artwork provided by a 'Backend' server always takes precedence over the 'Skin Helper Script' and 'Local Artwork', unless this option has been disabled.
If your backend server already provides PVR Artwork, you might not want to use options 2 or 3, but bear in mind the Skin Helper Script also displays other PVR info as well, such as 'First Aired Date/Movie Premiered Date', 'IMDB Star Ratings' and 'Movie/TV Show classification rating'. 
By using local artwork, you will get additional features such as 'Next' programme poster artwork on the 'Now/Next view', Poster and Landscape artwork for TV Recordings and also 'Next-Up' banner artwork appearing shortly before the next Live TV show begins.
Disabling all 3 options will result in the default poster artwork being displayed. 

### PVR Settings Screen

[![New PVR Settings Screen which can be found under the 'Skin Settings' option.](./resources/screenshot-20.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-20.jpg)

# PREMIERE FLAGS ON THE EPG SCREEN

The new 'PVR Settings' heading on the Skin settings has an option to display actual premiere flags on the EPG screen instead of using an '*'.
The flags shown are as follows:-
- 'Live' 	- A Orange coloured flag represents a Live TV Broadcast such as sport or news event.
- 'New' 	- A Yellow coloured flag represents a 'New' Episode or TV Show has been identified using the Guide Data.
- 'Prem' 	- A Red Coloured 'Prem' Flag represents 'TV Premiere' where the Season and Episode number are equal to 'S01E01' *
- 'Prem' 	- A Green Coloured 'Prem' Flag represents 'Season Premiere' where the Episode number is equal to E01 and the season number is higher than season S01, eg 'S02E01'
- 'Fin' 	- A Blue coloured flag represent season finale.
* The TV Premiere flag is not completely bulletproof, as sometimes S01E01 could be a repeat and therefore might not be true TV Premiere, ie something never broadcast before.

# Artwork Attributions
New Parental Rating Classification icons on this skin created using a combination of wyrm65's classification icon pack and braz's colour country flag resource pack:
https://github.com/wyrm65/resource.images.classificationicons.colour and https://github.com/braz96/resource.images.moviecountryicons.flags <br/>
Some media icons and flags sourced from the Leia version of the Madnox skin by Mike_Doc and Schimi2k:
https://github.com/MadMikeDoc/skin.aeon.madnox.leia/tree/master/media/flags


# Screenshots

### Live TV Home Menu with Recording thumbnail artwork
[![Live Tv Home Layout with Recording thumbnail artwork](./resources/screenshot-01.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-01.jpg)

### New EPG Layout with 'New', 'Premier' and 'Film' flags
[![New EPG Layout with 'New', 'Premier' and flags](./resources/screenshot-02.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-02.jpg)

### New PVR OSD Layout with 'Now-Next' Programmes
[![New PVR OSD Layout with 'Now-Next' Programmes](./resources/screenshot-03.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-03.jpg)

### New PVR Info Dialog View
[![New PVR Info Dialog Layout](./resources/screenshot-04.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-04.jpg)

### New PVR Channels 'PVR Now-Next' View
[![New PVR Channels 'PVR+ Now-Next' View](./resources/screenshot-05.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-05.jpg)

# New OSD Layouts

### Movie OSD
[![New movie OSD](./resources/screenshot-07.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-07.jpg)

### Movie OSD with Info-Panel activated
[![New movie OSD with Info-Panel activated](./resources/screenshot-08.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-08.jpg)

# New and Updated Skin Views

### Flix Landscape view
[![New Flix Landscape view](./resources/screenshot-09.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-09.jpg)

### Updated List view
[![Updated List view](./resources/screenshot-10.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-10.jpg)

### Updated Poster view
[![Updated List view](./resources/screenshot-11.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-11.jpg)

### New MediaInfo view
[![Updated List view](./resources/screenshot-12.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-12.jpg)

### New Card view
[![Updated List view](./resources/screenshot-14.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-14.jpg)

### Updated InfoWall view
[![Updated InfoWall view](./resources/screenshot-15.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-15.jpg)

### New Music Artist List view
[![Updated InfoWall view](./resources/screenshot-17.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-17.jpg)

### New Music Album List view
[![Updated InfoWall view](./resources/screenshot-18.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-18.jpg)

### Updated Music OSD 
[![Updated InfoWall view](./resources/screenshot-19.jpg)](https://github.com/SplitEnz/skin.estuary.pvr.plus.omega/blob/master/resources/screenshot-19.jpg)