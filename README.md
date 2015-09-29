# SEBHVAConfig
Working SEB for exams on moodle for the HVA

Change the permissions of the start.sh file
chmod +x GIT_FOLDER/seb/browser/bin/linux/64/start.sh

Make it easier to launch via the terminal (did not work in dmenu2 :C):
ln -s GIT_FOLDER/seb/browser/bin/linux/64/start.sh /usr/bin/seb

Disclaimer:
The only thing I did was fix the start.sh in the x64 folder to correctly open xulrunner for x64 and set the correct URL for moodle.
https://github.com/eqsoft/seb
