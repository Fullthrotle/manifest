X-TremeOS
========

## Downloading Source
To initialize your local repository, use this command:

	repo init -u https://github.com/X-TremeOS/manifest.git -b 9.x

Then to sync, use this command:

	repo sync -c -j8 --force-sync --no-clone-bundle --no-tags
	
	
	
## Building X-TremeOSOS
After download X-TremeOS source now you able to build rom by type
```
. build/envsetup.sh 
  lunch xtreme_CODENAME-userdebug
```
Then to start build
```
  mka xtreme
```

## Credits
-  [GZOSP](http://GitHub.com/gzosp)
-  [LineageOS](http://GitHub.com/LineageOS)
-  [BaikalOS](http://GitHub.com/BaikalOS)
-  [AospExtended](http://GitHub.com/AospExtended)
