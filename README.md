<p align="center">
<img src="https://media.discordapp.net/attachments/1102775142108647424/1103331738660384930/Frame_1.png" > 
</p>

--------------------------------------------------------------------------------------------------------
TutelOS
====================
Another cherry-picking ROM, developed by an usual person, nothing special


To initialize your local repository, use this command:
-----------------------------------------------------

    repo init -u https://github.com/tutelos-repo/android_manifest.git -b 13 --git-lfs

To sync the repository, use this command:
-----------------------------------------

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To Build, use following commands:
---------------------------------
    
    . build/envsetup.sh
    lunch tutel_<devicecodename>-userdebug
    m tutel

---------------------------------------------------------------------------------------------------------

Special thanks to All ROM Developers in this community

---------------------------------------------------------------------------------------------------------

Thank you!

---------------------------------------------------------------------------------------------------------
