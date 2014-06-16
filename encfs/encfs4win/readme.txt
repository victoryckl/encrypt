1.First time
install required Dokan library; 
Extract executable (or compile by your own). 


2.Every use
open a windows command 
launch "encfs <crypt_dir> <plain_dir>" where crypt_dir is crypted directory while plain_dir is the directory where you can access not crypted files.
NOTE: Windows 7 users should use a drive (like "X:") as plain_dir to avoid case sensitive problems which results in file/folder not found problems. 

3.Using GUI instead of command line 
launch the gui program and use the tray icon menu 

You can also use Ronald Moegel batch included.
Some people asked if is possible to change label of drive. This is actually possible using the volname FUSE option, specifying something like encfs <crypt_dir> <plain_dir> -- -o volname=<label>