Lock_Patch Porting for cm10 WIP
===============================












OLD CM9 patch intructions (no need)

3. Step - Correct the META-INF folder
Open the Semc Debrand Engine Rom's flashable zip
Delete the "META-INF" folder
Open my patch zip
Copy the "META-INF" folder to the SDE zip

4. Step - Add recovery and ramdisk for locked bootloader
Open the /system/bin directory in SDE zip
Delete the "chargemon" file
Copy these files from my patch zip to SDE /system/bin directory:

 "chargemon", "charger", "ramdisk.tar", "recovery.tar"

5.Step - Add sh to make the script working
Go to /system/xbin directory in the SDE zip
Copy the "sh" file from my patch zip

6. Step - Fix the wifi on locked bootloader
Go to /system/etc/init.d directory in the SDE zip
Copy the "00wififix" file from the patch zip

7. Step - Install
Now the rom is ready for install. Just put the SDE zip to your Sdcard/internal memory 
and install it with recovery. (Don't forget to do full wipe)
