Project-Xtended:
====================

A ROM Based on AOSP, with features from almost all Custom ROMs available.

To initialize your local repository, use this command:
-----------------------------------------------------

    repo init -u https://github.com/Project-Xtended/manifest.git -b xq

To sync the repository, use this command:
-----------------------------------------

    repo sync -f -c -j8 --force-sync --no-clone-bundle --no-tags

To Build, use following commands:
---------------------------------
    
    . build/envsetup.sh
    lunch xtended_device-userdebug
    make xtended

Apply for official maintainership [**HERE**](https://forms.gle/D9WPbBcbeVFiBMJb7)

---------------------------------------------------------------------------------------------------------

Thread template refer [**HERE**](https://github.com/Project-Xtended/manifest/blob/xp/Thread_Template.txt)

---------------------------------------------------------------------------------------------------------
