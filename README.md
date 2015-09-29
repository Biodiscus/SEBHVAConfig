# SEBHVAConfig
Working SEB for exams on moodle for the HVA

Clone the project with the submodule
git clone --recursive git@github.com:Biodiscus/SEBHVAConfig.git
If you forgot the resursive part and just cloned normally:
cd SEBHVAConfig/seb && git submodule update --init --recursive

Create the profile directory
mkdir GIT_FOLDER/seb/browser/data/profile

If you're running a 64 bit linux, change the start.sh to correctly get the xulrunner (the file automaticly targets to a 32 bit system).

Make it easier to launch via the terminal (did not work in dmenu2 :C):
ln -s GIT_FOLDER/seb/browser/bin/linux/64/start.sh /usr/bin/seb

Default closing password: 
password

Disclaimer:
The only thing I did was fix the start.sh in the x64 folder to correctly open xulrunner for x64 and set the correct URL for moodle.
https://github.com/eqsoft/seb
