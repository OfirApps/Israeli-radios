# mpv9tv.sh
Fullscreen watching 9 TV channels with Linux shell script. It's very useful watching 9 TVs at the same time with opened muted and volume control with mouse scroll (double click fullscreen).

### Requirements
1. sudo yum install mpv youtube-dl
2. 1920X1080 screen resolution (if not or different, need to calculate --geometry parameters)
3. Add this two-line to "~/.config/mpv/input.conf" for volume control with mouse scroll.  
  MOUSE_BTN3 add volume 2  
  MOUSE_BTN4 add volume -2  
4. Make executable the shell script file.  
  sudo chmod +x mpv9tv.sh  
    
      
      
