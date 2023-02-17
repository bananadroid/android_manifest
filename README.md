<p align="center">
<img src="https://github.com/bananadroid/android_manifest/blob/13/banner.png?raw=true" > 
</p>

---------------------------------------------------------------------------------------------------------
BananaDroid
====================
Another cherry-picking ROM, developed by an usual person, nothing special


To initialize your local repository, use this command:
-----------------------------------------------------

    repo init -u https://github.com/bananadroid/android_manifest.git -b 13

To sync the repository, use this command:
-----------------------------------------

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

Before build need adapt your tree:
---------------------------------

in your device tree search for rom_devicecodename.mk and rename to banana_devicecodename.mk

on this file you have to edit to

    PRODUCT_NAME := banana_devicecodename
    
    $(call inherit-product, vendor/banana/config/common.mk)
    
in AndroidProducts.mk

    PRODUCT_MAKEFILES := \
    $(LOCAL_DIR)/banana_lavender.mk

    COMMON_LUNCH_CHOICES := \
        banana_devicecodename-user \
        banana_devicecodename-userdebug \
        banana_devicecodename-eng
        
build flags:
---------------------------------

    # GApps Build
    WITH_GAPPS := true
    
    # Core GApps
    WITH_GAPPS := true
    BUILD_CORE_GAPPS := true
    
    # Core GApps Extras
    BUILD_CORE_GAPPS_EXTRA := true
    
    # Additional features for full GApps build
    TARGET_SUPPORTS_GOOGLE_RECORDER := true
    TARGER_SUPPORTS_NEXT_GEN_ASSISTANT := true
    
    # Specific maintainer
    BANANA_MAINTAINER := yournickname
    
    # Blur
    TARGET_ENABLE_BLUR := true
    
    # Device UDFPS
    TARGET_HAS_UDFPS := true
    
    # Face Unlock
    TARGET_FACE_UNLOCK_SUPPORTED := true
    
    # Default build has Matlog, disable it with this flag
    TARGET_EXCLUDE_MATLOG := true

To Build, use following commands:
---------------------------------
    
    . build/envsetup.sh
    lunch banana_<devicecodename>-userdebug
    m banana

---------------------------------------------------------------------------------------------------------

Special thanks to All ROM Developers in this community

---------------------------------------------------------------------------------------------------------

Join our [**Telegram Group**](https://t.me/bananadroid) and follow our [**Telegram Channel**](https://t.me/bananadroidchannel)

Thank you!

---------------------------------------------------------------------------------------------------------
