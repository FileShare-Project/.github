# FileShare Project

This project intends to create an easy-to-use, cross-platform, peer-to-peer, end-to-end encrypted, file sharing software.  

## The motivation

The need to create such a software arised because there is no way of sending a file from a device to another over the internet without having to either setup a FTP server, or using a Cloud-based solution.

None of theses solutions are ideal, because setting up a FTP server requires a certain knowledge (most people don't know how to), and requires opening a port on one's domestic router (most people also don't know how to).  
There is also security concerns on properly securing an FTP installation (how many publicly reachable FTP servers have `admin:pass123` as credentials ?) and opening router ports.

On the other hand, using a Cloud-based solution does not require any knowledge, and is secure. The issue here, is the requirement to upload your files to some remote server (even temporarily).  
The server could keep your files, and theses solutions are usually not free (most do offer some free space however).  
While they are definitively a better alternative to manually setuping FTP servers, it is not ideal to have to upload a file, wait for the upload to finish, then start the download on the 2nd device and finally delete the file if all you wanted was a file transfer from Device A to Device B.  
In the end, theses are cloud-storage solutions, and are not intended to be used for file transfers.

## The goal 

Having a software available on Windows/Linux/Mac/Android/IOS, with almost no configuration required (but advanced configuration available), to securely send files across devices over the internet, with no third-party ever storing the files or seeing them unencrypted.

A lot of features are planned, but here is a non-exhaustive list :
- Automated synchronization of specific files across devices
- Optional file content history (allows to restore a transfered file to a previous version)
- Automated backups
- Transfer pause/resuming
- Bandwith usage limitation
- Remote file explorer and file download (requires configuration first)
- LAN devices discovery (requires manual authentification step before transfers are allowed)
