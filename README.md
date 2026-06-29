## build-sid
### Create a Debian sid minimal live system similar to 'DebianDog'

See more info about usage and changes/fixes at https://forum.puppylinux.com/viewtopic.php?p=172966#p172966       

This works very similar as the 'mklive-sid' script:    
https://forum.puppylinux.com/viewtopic.php?t=824     
except that it's very much simplified.

Support for "xlibre" install (replacement of xorg). NOTE: only for amd64      
Run with .conf file *-xlibre.conf, e.g `./build-sid configs-sid/lxqt-full-xlibre.conf`


`fredx181, 2026-06-27, stripped down version of mklive-sid`    
`supports only .conf files as an argument, e.g. ./build-sid /path/to/myconfig.conf`    
`no dependency on yad (as this has no GUI), no dependency on files to download from the 'MakeLive' repository.`    


`Usage: ./build-sid <config_file> (presets are in configs-sid) `   
 `-help show this help `   
 `Example using one of the preset config files:`    
 `./build-sid configs-sid/lxqt-full.conf`     
 `Example using one of the preset config files to install xlibre rather than xorg:`       
 `./build-sid configs-sid/lxqt-full-xlibre.conf`       
 `Example with custom config file:`    
 `./build-sid /path/to/my.conf `   

 
