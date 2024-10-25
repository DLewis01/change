# change
Change one filetype (image,video,audio) into another

I often have downloads of images, audio or video in different formats to what I need, so this is a simple script to change them into a different format of your chosing.

Requirements:
 - imagemagick
 - ffmpeg

  For MAC 

     brew install imagemagick
     brew install ffmpeg
  For Ubuntu/Debian:
 
     sudo apt-get install imagemagick
     sudo apt-get install ffmpeg
  Fedora

     sudo dnf install imagemagick
     sudo dnf install ffmpeg
  CentOS/RHEL

     sudo yum install imagemagick
     sudo yum install ffmpeg
  Arch

     sudo pacman -S imagemagick
     sudo pacman -S ffmpeg



Put this file, change, into your local bin directory then make the script executable with
chmod +x change

To run it, type change {filename}

examples:

change myfile.mp4

change myfile.webm

chamge myfile.jpg
