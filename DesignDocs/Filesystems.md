# Filesystems brief
## Situation
We are currently using __ext4__ filesystem on or __MAN-00__ protoype.
Together with power cuts, it makes the SD card corruption-prone. 
Online backups don't really match our 'own-secure-server' product philosophy.
Read more on filesystems: [JFS](http://en.wikipedia.org/wiki/Journaling_file_system),
[LSFS](http://en.wikipedia.org/wiki/Log-structured_file_system)
[COW](http://en.wikipedia.org/wiki/Copy-on-write)
[Seleting a FS](http://superuser.com/questions/248078/choice-of-filesystem-for-gnu-linux-on-an-sd-card)
[RasPi SD problems](http://comments.gmane.org/gmane.comp.file-systems.btrfs/31821)

## Mission
Come up with a solution to minimize or eleiminate this risk.

## Execution
Our current options are:
+ Select a different, more reliable filesystem (__BTRFS__, __ZFS__, see links in the _Situation_)
+ Implement an offline/secure backup solution
+ Cry and give up
