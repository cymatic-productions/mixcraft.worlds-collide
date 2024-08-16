<audio controls>
<source src="./track-render.mp3" type="audio/mpeg">
</audio>


# Tips for Development

## External MIDI Controls
* View [this video](https://www.youtube.com/watch?v=GG81OfTMigQ)

## Converting `.mp3` to `.midi`
* The `plugins/NeuralNote.exe` application can be used to convert `.mp3` to `.midi` files.

## Merging Clips Without Crossfade
_Learn more [here](https://forums.acoustica.com/viewtopic.php?t=15397)_
* Create a new Track.
* Select the newly created Track.
* Press `Alt+L` to create a new "Lane".
 * a "Lane" is a way to have multiple clips at the same time offset without being on top of each other.
* Right click the newly created multilane track.
* Select `Mix to New Audio Track`, to merge the clips.

## Controlling Multiple Tracks
_Learn more [here](https://www.youtube.com/watch?v=W0ClXPfhCEg)_
* Select the Tracks (_not the clips_) to be grouped.
* Right click the selection
* Select `Add New Submix` to group the selected tracks to a single "Submix".

## Viewing the Project
* This application has been deployed [here](https://cymatic-productions.github.io/mixcraft.projecttemplate/)

## Ensuring Portability
### Overview
* To ensure full-portability of your project, ensure `SFX`, `Loops`, and most importantly, `stems` are exported locally to the project.
 * a `stems` directory has been created for you.

1. Exporting / Importing Tracks As-is
2. Exporting / Importing Stored Imported Loops and SFX to Local Project Folder

#### Exporting / Importing Tracks As-is
* Select `Mix to Stems` and set the `File Naming Convention` to `{#} - {n}`

#### Exporting / Importing Stored Imported Loops and SFX to Local Project Folder
* To [change the folder of stored imported loops and sfx](https://forums.acoustica.com/viewtopic.php?t=30022), perform the steps below.
* Navigate to `File` > `Preferences` > `Library` set the `Loop Library Directory` library folder.  
  * _Note_
    * Be careful to choose a writeable location.
    * this setting [may be grayed out](https://forums.acoustica.com/viewtopic.php?t=16456) if you are not running Mixcraft as an administrator

* When you import the files, there's an option to copy them to the library.
* If you don't choose that option, Mixcraft will just look in the original location.
* If you're using Mixcraft 9, make sure you have build 470.
* If you're using Mixcraft 10, make sure you have build 579.
