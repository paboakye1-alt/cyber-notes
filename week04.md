# Week 4
## Day 1 notes
Never click Yes on a UAC box you didn't expect.
Show file extensions, always. Read names from the right.
Search by hash, not by uploading private files
Look before you change, startup apps, run keys and services are where malware lives
Use a standard account for daily work if you can.

 BIOS Mode UEFI
 Secure Boot State ON
 Up time - 2:22:03:39

 #Day 2
 whoami - pablo
 pwd    -   /c/Users/pablo 
 tilde stands for the current user's home directory.
 /C/WINDOWS - NO
 /C/WINDOWS and /c/Windows are not the same folder because Linux file paths are case-sensitive. 

# Day 3
2 names that ls -a shows but plain ls doesn't.
1..gitconfig/
2..cluade/
The ls -a should start with a dot (.), which marks hidden files and directories—including
ls -lh
  0 Nov  4  2021  AppData/
-t                         sort by time, newest first; see --time
 -r, --reverse              reverse order while sorting

## Day 4
Starting directory (`cd ~/linuxlab`): `/c/Users/pablo/linuxlab`

* **(a) `cd shop/receipts`, then `pwd`:**
  * **Prediction:** `/c/Users/pablo/linuxlab/shop/receipts`
  * **Actual `pwd`:** `/c/Users/pablo/linuxlab/shop/receipts`
* **(b) `cd ..`, then `pwd`:**
  * **Prediction:** `/c/Users/pablo/linuxlab/shop`
  * **Actual `pwd`:** `/c/Users/pablo/linuxlab/shop`
* **(c) `cd ../..`, then `pwd`:**
  * **Prediction:** `/c/Users/pablo`
  * **Actual `pwd`:** `/c/Users/pablo`
* **(d) `cd -`, then `pwd`:**
  * **Prediction:** `/c/Users/pablo/linuxlab/shop`
  * **Actual `pwd`:** `/c/Users/pablo/linuxlab/shop`

 failed to remove 'shop': No such file or directory
because it only removes empty directories and will not delete a folder that still contains files.