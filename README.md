<p align="center">
  <img src="https://raw.github.com/krexus-caf/manifest/caf/krexus-caf-logo.png" width="600">
</p>


*Stock nexus on your Qualcomm device, "as it should be"*
------------------------------

Manifest
========

**Android 6.0.x** (latest is 6.0.1_r13)		
**CodeAURORA 6.0.x** (latest is LA.BR.1.2.7_rb1.11)

1. Initialize the marshmallow repo	
`repo init -u https://github.com/krexus-caf/manifest.git -b caf`

2. Sync		
`repo sync`

3. Load the environment		
`ln -s vendor/krexus/utils/krebuild.sh krebuild.sh`		
`. krebuild.sh`

4. lunch & download device repos	
`lunch ******`

5. Build!
`mka otapackage`

CAF Credits
------------
This CAF Krexus source was made possible by [AOSP-CAF](https://github.com/AOSP-CAF)		
and the work of [Meninblack007](https://github.com/Meninblack007)		

Krexus Credits
------------
Huge thanks to:  
[CallMeAldy](https://github.com/CallMeAldy)		
[Sykopompos](https://github.com/Sykopompos)		
[rascarlo](https://plus.google.com/+CarloDiNuccio/)		
[bgill55](https://github.com/bgill55)		
[BeansTown106](https://github.com/BeansTown106)		
[ZephiK](https://github.com/zephiK)		
[Cyanogenmod](https://github.com/CyanogenMod)  
Google	
AOSP
