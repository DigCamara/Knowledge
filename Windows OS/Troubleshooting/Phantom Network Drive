## Issue: A phantom network drive appears in Windows Explorer and cannot be removed 

### Possible approaches

* The GUI option (Explorer->Connect Network Drive->Disconnect Network Drive)
* The cmd options ( command prompt->)
1. `net use [drive] /d`. This could work whenever net use shows anything at all
1. `disk part
    remove letter=[drive]`. Careful: if it is mapped to a user, it will attempt to login to the network using the user and password it knows about. 
* The regedit option. Permanent mappings are stored under `HKLM\SYSTEM\CurrentControlSet\Control\NetworkProvider\GlobalMappings`. Deleting the phantom drive's letter should work. Requires a restart
