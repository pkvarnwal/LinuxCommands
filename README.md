## Important commands for linux machine

* To check free space of RAM: free -h | awk '/Mem:/{print $2}'
* To check memory info: sudo lshw -short -C memory
* To install software in ubuntu using terminal: sudo dpkg -i Skype.deb
* To update ubuntu: sudo apt-get update
* To open png image: xdg-open Image.png
* To Rename file: mv current_file_name.ext new_file_name.ext
* To delete file: rm -rf File name
* To print the first n lines in a file: head -n 10 /var/log/syslog
* To print the last n lines in a file: tail -n 10 /var/log/syslog
* To check that you have locales package installed: dpkg -l locales
* To make sure that your system an UTF-8 locale is generated. As root: dpkg-reconfigure locales
