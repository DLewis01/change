# change
Change one filetype (image,video,audio,pdf) into another

I often have downloads of images, audio, pdf's or video's in different formats to what I need, so this is a simple script to change them into a different format of your chosing.

Requirements:
 - imagemagick
 - ffmpeg
 - poppler

  For MAC 

     brew install imagemagick
     brew install libvpx ffmpeg
     brew install poppler
  For Ubuntu/Debian:
 
     sudo apt-get install imagemagick
     sudo apt-get install ffmpeg
     sudo apt-get install poppler
  Fedora

     sudo dnf install imagemagick
     sudo dnf install ffmpeg
     sudo dnf install poppler
     
  CentOS/RHEL

     sudo yum install imagemagick
     sudo yum install ffmpeg
     sudo yum install poppler
     
  Arch

     sudo pacman -S imagemagick
     sudo pacman -S ffmpeg
     sudo pacman -S poppler



Put this file, change, into your local bin directory then make the script executable with

      chmod +x change

To run it, type change {filename}

examples:

    change myfile.mp4

    change myfile.webm

    chamge myfile.jpg
