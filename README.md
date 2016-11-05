# scriptit
As you may have guessed I am a Ubuntu Noob and a recovering Windows user. Windows 8 finally made me to commit to Linux and leave it behind forever.

To install just unpack the archive anywhere you want. I just put it in my home directory. The scripts should be executable by using ./scriptname. If that doesn't work then bash scriptname with get it to work. You can make them executable if they aren't already by using the script mkexit, you will be prompted for the file name just type the name of the file and make it executable. It's a lot easier than chmod +x file. 

To make the scripts executable system wide you will need to edit /etc/environment file by adding [:/home/username/scripts] to the path declaration. Once that is done a reboot and you will be able to execute any of the scripts in the scripts folder just by typing its name from a terminal, you won't need to use ./ before the name just its name, such as fetchit. Or optionally you can put it in /usr/local/bin

List of Files
addit	adds ppa to the sources file and then runs updateit
autormit	runs apt-get autoremove
fetchit	runs sudo apt-get install and prompts for the package name
mkexit	runs chmod +x and prompts for the file to make executable
muit	runs sudo su
nanoit	provides a list of files to open with nano
purgeit	runs sudo apt-get purge and prompts for package name
rmfit	deletes a non empty folder
updateit	runs sudo apt-get update

All of the scripts are fully editable more will be available as I can update them.
