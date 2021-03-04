# CVREDocumentation

## Installation

### Initial Steps

- Download [this zip file](https://github.com/cvrebeatsaber/Documentation/releases/download/v2.0.0/ManualTA_Install_v0.5.0.zip)
There are two things inside this zip:

![Zip File](/uploads/00_zip_contents.png "Zip Contents")

- Run [ModAssistant](https://github.com/Assistant/ModAssistant) (make sure you have the core mods)
**NOTE: Make sure you have opened the game at least once before attempting to run ModAssistant, otherwise your mods may not work properly!**

- Extract the zip file to your **base game directory!** This is where your `BeatSaber.exe` is located!
**NOTE: This directory is different depending on your game! Follow the instructions below to see where your Beat Saber is located!**

#### Steam Beat Saber Location

`Beat Saber.exe` is most likely located at: `C:\Program Files (x86)\steam\steamapps\common\Beat Saber\`

You can double check this by right clicking on the game in steam and choosing properties --> local files --> browse local files.

![Steam Location](/uploads/01_steam_location.png "Steam Location")

#### Oculus Beat Saber Location

`Beat Saber.exe` is most likely located at: `C:\Program Files\Oculus\Software\Software\hyperbolic-magnetism-beat-saber\`

You can double check this by clicking the menu icon next to Beat Saber in your Oculus Library, and then clicking details.

![Oculus Location](/uploads/02_oculus_location.png "Oculus Location")

### Beat Saber Folder

- Your Beat Saber folder should look similar to the following (after you extract the zip file into it):

![Beat Saber Folder](/uploads/03_beatsaber_folder.png "Beat Saber Folder")

There should be several libraries in your `Libs` folder: `Google.Protobuf.dll`, `System.Memory.dll`, `System.Runtime.CompilerServices.Unsafe.dll`, and `TournamentAssistant.Shared.dll`, and `TournamentAssistant.dll` should be within your `Plugins` folder (along with `BS_Utils.dll`, `BSML.dll`, and `SongDataCore.dll`).

If it doesn't look like this or you are missing plugins, please skip down the the [FAQ Section below](https://github.com/cvrebeatsaber/Documentation#faq)

You have now installed the mod!

## Signup for a BeatKhana account

- Go to [BeatKhana](https://beatkhana.com/) and register for an account. Link it to your Discord that you use on the CVRE discord server.
- [Sign up for the tournament](https://beatkhana.com/tournament/2147484223) and enter your school name
- **Ask your captain and type it in EXACTLY as they state! IF YOU DO NOT, YOUR QUALS SCORES MAY NOT BE PROPERLY SAVED!**

![Sign up for tournament](/uploads/15_signup_bk.png "Signup for CVRE Tournament")

That's it!

## Usage for PC

Enter the game. On the left hand side, you will see a mods menu. Click the `TournamentAssistant` button and select the `quals` button, as seen below:

![TA Button](/uploads/10_beatsaber_quals_button.png "Beat Saber TA Button")
![Quals from TA](/uploads/11_beatsaber_ta_quals_button.png "Beat Saber Quals Button")

After this, select the CVRE Qualifications event (if multiple appear, select either) and play the songs listed, which will automatically download.

![Events](/uploads/12_beatsaber_events.png "Beat Saber Events")

The leaderboard in game may or may not appear, instead, use the [BeatKhana leaderboard](https://beatkhana.com/tournament/2147484223) for a more reliable sense of the qualifications (see CVRE Discord). Note that the official leaderboard may have further adjustments made to it after the qualification phase is complete.

## Usage for Quest

Coming soon, but you will need to download your quest ID for use with the mod, available from your BeatKhana profile page.

## FAQ

Q: My folder doesn't look like it should after I extracted the zip. What did I do wrong?

A: You probably extracted in the incorrect directory. You can also copy over each file/folder from the .zip file into your Beat Saber directory.

Q: I see two events, does it matter which one I choose?

A: No. Both will work.

Q: I see a grey box for song selection without a percentage indicating its loading. Can I still play it?

A: Yes, simply select it anyways.

Q: The leaderboards don't work

A: They may not, and aren't necessarily accurate. Check [BeatKhana for the correct leaderboard](https://beatkhana.com/tournament/2147484223).

Q: I see 0 events. What can I do?

A: Restart your Beat Saber. If it still fails to appear, check your internet connection. If no events appear, delete your `UserData/TournamentAssistant.json` file and reload the game. If STILL no events appear, both Sc2ad#8836.

**NOTE: IT IS GENERALLY GOOD PRACTICE TO TAKE PICTURES OF YOUR SCORES IN THE EVENT OF AN UPLOAD FAILURE! PLEASE DO THIS IF YOU HAVE ISSUES!**

In general, please DM Sc2ad#8836 on Discord with any questions, comments, concerns, or more.
