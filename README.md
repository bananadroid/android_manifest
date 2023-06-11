<p align="center">
<img src="https://camo.githubusercontent.com/d84b1cf346fb6c8ff7a9972a2a0b54d6afdce767f74a204a6b96b3fc0d69ab6c/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f313130323634323633363034363734353638302f313131333434303530373430363836303332382f626c7961745f6875656d5f706f5f6c62755f6e655f64616c6f2e706e67" > 
</p>

--------------------------------------------------------------------------------------------------------
TutelOS Legacy
====================
(as of right now your only building LineageOS 14.1 using this repo but it doesnt work using the tutel command)

To initialize your local repository, use this command:
-----------------------------------------------------

    repo init -u https://github.com/tutelos-repo/android_manifest.git -b 7.1.2 --git-lfs

To sync the repository, use this command:
-----------------------------------------

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch

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
