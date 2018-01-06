# scripts
Handy scripts from ~/bin

** !!! No longer maintained.
Replaced by [scripts-ng](https:github.com/toxygeneb/scripts-ng) project !!! **

 * **`clean`**

    Clean Arch Linux install of all packages except those listed in ignoregrp & ignorepkg

        - TODO: lists of groups and packages as arguments
        - TODO: arguments to append/override defaults groups and packages
        - TODO: add error checking for groups & packages

 * **`gpgencrypt`**

    Encrypt folder with GnuPG using speciified email address. 
    Example: `gpgencrypt ~/Documents me@example.com`
    
 * **`mkimg`**
 
    Make ISO image file of optical drive
    
        - TODO: Add mount check
 
 * **`pornoff`**

    Unmount EncFS folder

        - TODO: check existence of directory before unmounting
        - TODO: check for unmounting errors
        - TODO: add multiple folder support
        - TODO: add keyfile support

 * **`pornon`**

    Mount EncFS folder

        - TODO: check existence of directory before mounting
        - TODO: add keyfile support

 * **`setalbumartist`**

    Set id3v2 album artist tag from track artist tag for all mp3 files in current directory

 * **`setbpms`**

    Set id3v2 bpm tag from comma separated list of filenames and bpms

 * **`totalsizebytype`**

    Display collective file size for all files of a certain type

 * **`unrarall`**

    Unpack all rar files in directory
