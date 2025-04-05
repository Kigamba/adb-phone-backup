# adb-phone-backup
Allows backup with improvements over adb pull

Requirements
=================

These are the improvements over adb pull:

- Skip errors such as permission denied
- Skip random errors such as file not found, file not directory
- Skip unchanged files
- Generate an index of the files for each backup
- Generate a report of the changed files after done backing-up

Ideally, it just copies over all the files to local PC storage. Allowing me to have a local backup and free-up space 😄 on my phone


