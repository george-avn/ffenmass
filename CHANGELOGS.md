







## Changelogs

**0.2.9**

- Added more extensions to the extension filter list.



**0.2.8**
- This Version Was Skipped due to an issue with pipy




**0.2.7**
 - Rich and ffpb are now dependencies.
 - Added a file filter, now only media files will be parsed when scanned.
 - Using ffbp for a progress bar because I dont want to make one.
 - Using Rich to make text prettier.
 - Yaspin no longer a dependency, replaced by ffbp.
 - Code cleaned up, file related functions are under their own Class.
 - Small changes to comments to be more thorough. 


**0.2.6**
 - Parsing FFmpeg input to display speed.
 - Fixed exit bug when creating non-existing output folder.


**0.2.5**
 - Migrated from os.path over to pathlib.(yay)
 - Added additional required argument `-ext`.
 - FFenmass now handled file extensions
 - `-f` argument is no longer required by ffenmass and is not checked.
 - Some ground work to prepare for windows testing and debuging.
 - Updated Readme with better examples.
 - Additional Code docs to help me mostly.


**0.2.4**
 - FFenmass will now clean after itself, if interupted during processing, the item that was last in progress will be deleted.
 - FFenmass will skip files that already exist with the same filename in the output directory.
 - Encoding queue is now sorted alphanumerically.
 - Yaspin is now a dependency.
 - TQDM is now a dependency.
 - Prettyfied output.
 - FFmpeg is now mute (again).




**0.2.3**
 
 - Made ffmpeg less verbose using -hide_banner
 - FFenmass will now clear the terminal after each encode bc ffmpeg talks too much
 - Made a less ugly and proper Readme


**0.2.2**
 
 - Simplified code, optimized imports
 - Rich is no longer a dependency
 - Updated README and Made Changelongs and TODO reside under CHANGELOGS.md



 **0.2.1**
 
 - Recursive fix
 - FFmpeg made Verbose
 - Yaspin is no longer a dependency

 **0.2.0**
 
 - Ignores extensions, will now work with audio,video,subs etc.
 - Made into a pip module.

 **0.1.0**
 
 - Module was created and uploaded
