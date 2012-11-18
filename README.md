# SpotiFree
SpotiFree is a tiny simple **AppleScript** application, that automatically detects and mutes Spotify's ads on OS X.

## How it works
**SpotiFree** is polling Spotify every **.5** seconds to see if current track has **0 popularity** (as all ads do) and is  **less then 40 seconds long** (and all Spotify ads are). If it is, Spotify is paused, its volume is set to **0** and the playback is restored. When an ad is over, the volume is set to the way it was before.

## Installing
1. Download **SpotiFree** github project.
2. Open the script using AppleScript Editor and export it as an App file (File, Export...)
3. Copy the new generated App in your Applications folder

3. If you do not need to modify the script, you can just move SpotiFree.App to your Applications folder
4. Additionally, you can launch it at startup (System Preferences, Users and Groups, Login Items) by pressing the "+" sign and selecting the App

## Troubleshooting
1. Kill **SpotiFree** process (if any) using the **Activity Monitor** (Applications → Utilities → Activity Monitor);
2. Get a fresh app from the [Downloads](https://github.com/ArtemGordinsky/SpotiFree/downloads) page, and install it, replacing the old one.
3. Run the app again.
4. If nothing helps, open a [new issue](https://github.com/ArtemGordinsky/SpotiFree/issues) here on original GitHub project.

## Origin
**SpotiFree** is based on the AppleScript script made by the Macrumors user **ctferrara**. If not for him, this app probably wouldn't have existed.
Forked from ArtemGordinsky .
