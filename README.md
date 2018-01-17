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

* Detailed instructions to copy/paste lines of text in vi using yank and put
  ## Copy (YANK)
  ## To copy one line in vi:
* In the command mode, move the cursor to the line that needs to be copied and type `yy` or type `Y`
  
  ## To copy two line in vi:
* In the command mode, move the cursor to the first line that needs to be copied and type `2yy` or type `2Y`

  ## (likewise, any number of lines can be copied)
  To copy all lines from the current location to the end of the file:
* In the command mode, move the cursor to the first line that needs to be copied and type `yG` 
  
  To copy all text from the current location to the end of the current word:
* In the command mode, move the cursor to location from where text needs to be copied and type `yw`

  ## To copy all text from the current location to the end of the line:
* In the command mode, move the cursor to location from where text needs to be copied and type `y$`

  ## Paste (PUT)
  To paste text in the clipboard - after the location of the cursor:
* In the command mode, type `p`

  To paste text in the clipboard - before the location of the cursor:
* In the command mode, type `P`

  ## To kill a runnig software
  kill -9 <ID> which is looking in system monitor

* ## To convert from Video to Audio from URL use below command:
  youtube-dl youtube-url --extract-audio --audio-format mp3

  ## /etc/networks/interface file resolved the issue.
* iface lo inet dhcp
