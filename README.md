Joxi in Linux
=====================

Takes screenshots and uploads them to joxi using the joxi API and copies the link to clipboard. Recommended for set up with keyboard shortcuts
<br>Utilises __scrot__ for taking screenshots (which must be installed separately).

## Instructions
- Clone or download the repo
- In file "joxi" add your joxi API key to JOXI_API_KEY
  - (You can find your API key at 'access_token' field in response from joxi chrome plugin's login page)
- Make it executable using __chmod +x joxi__
- Place this file wherever you want (recommended: /usr/local/bin)
- Set up keyboard shortcuts within linux
  - (in Ubuntu it's system settings > keyboard > keyboard shortcuts > custom shortcuts)
  - Log out for the changes to take place
  - Here's what it looks like for mine: ![Puush keyboard setup](http://puu.sh/cOyVz/8dcb1cd498.png)

### Commands
``` bash
joxi -a		# area capture
joxi -f		# capture desktop
joxi -w		# capture window

joxi -h  	  # help
```

## Dependencies
- scrot
- curl
- xclip
- notify-send

