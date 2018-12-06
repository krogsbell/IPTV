# IPTV
Kodi programs related to IPTV like GlowIPTV, PremiumIPTV, NTV.mx, ACE TV, ROQ TV, Rytec EPG download and recording.


How to Krogsbell Addons on Kodi

Start by installing the Git Browser
Download zip from https://github.com/tvaddonsco/script.module.commoncore/archive/master.zip and install zip in Kodi

Download zip from https://github.com/tvaddonsco/plugin.git.browser and install zip in Kodi

Start Git Browser and Search by Addon ID: nordicchannels and install the newest version

End Git Browser

Without Git Browser find https://github.com/krogsbell/IPTV and download the .zip file you need

Enable The Krogsbell Addon

Start The Krogsbell Addon – You will be warned that recording directory is not writeable – select OK

Next box shows previous configurations – if only one – select cancel.

You are now in the settings of the addon.

Insert Username and password if you have one - otherwise write None as username and omit the password

Now you set your timezone in 3 places. If you are in Central Europe use 1

‘Time Zone offset in Hours’: If UK set to 0 unless daylight savings time – set to 1. If Central Europe use 1 and during daylight saving time use 2

‘Time Zone for Archives’: If UK set to 0, if Central Europe set to 1. This setting is not using daylight saving.

‘Time Zone for EPG file’: Set to the same as the first Time Zone.

On the recording tab set the recording path if you plan to record or disable recording and ffmpeg test.

Then OK to start.

The channels and EPG are collected in a local database each four hours of the day.

Until the local database is completed you can watch your channels by selecting Streams and one of the white menu entries.

You can use Search Channels to find your channels of interest and mark them Favorite of Nordic Channels Rec. Then you only have to browse through the channels of your interest.

Open the Favorites view and see all your channels with EPG to the left. With the menu you can watch the TV guide for the selected channel. Lines starting with green REC can be selected for recording just by hitting enter or you can start a Recursive recording for all programs with this title or you can modify the text to search for. Recording requires the installation of the program ffmpeg for your platform.

To investigate futher about the addon, consult the changelog.txt file in the program directory. 
