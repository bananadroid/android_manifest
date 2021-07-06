<p align="center">
<img src="https://github.com/bananadroid/docs/blob/master/bananadroid_banner.png?raw=true" > 
</p>
-------------------------------------------------------------------------------------------------------

BananaDroid:
====================
Another cherry-picking ROM, developed by an usual person, nothing special


To initialize your local repository, use this command:
-----------------------------------------------------

    repo init -u https://github.com/bananadroid/manifest.git -b 11

To sync the repository, use this command:
-----------------------------------------

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

To Build, use following commands:
---------------------------------
    
    . build/envsetup.sh
    lunch banana_<devicecodename>-userdebug
    make banana

---------------------------------------------------------------------------------------------------------

Join our [**Telegram Group**](https://t.me/bananadroid) and follow our [**Telegram Channel**](https://t.me/bananadroidchannel)

Thank you!

---------------------------------------------------------------------------------------------------------
