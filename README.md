# INSTRUCTIONS

1. Copy the contents of `nanorc` here on github.

2. Determin at what access level you want to edit the config:
    - If you want to override just the settings for your user account (recommended):
        Remove any potential old nanorc file and create a new one
        - `rm ~/.nanorc; nano ~/.nanorc`
    - If you have root access and want to override the settings globally (not recommended on multi-user systems):
        Remove the old nanorc file and create a new one:
        - `sudo rm /etc/nanorc; nano /etc/nanorc`
  
3. Paste the contents
    - Are you running nano natively (or in a vm) with a gui?
        - `alt+u` (defualt paste)
    - Are you connected through ssh?
        - `right click`

4. Save the file:
    - `ctrl+o` (as in the letter "o" is default save)

5. Exit the file:
    - `ctrl+x` (is defualt)

6. Go test out your new settings and make sure to use the help guide at the bottom of nano to better understand the commands.
    - `ctrl+h` will bring up a help menu for commands. I highly recommend you read these.
    To get you started though:
      - `^` is `ctrl`
      - `M` is `alt`
      - `mouse_scroll_up`, `mouse_scroll_down`, and `mouse_cursor_click` work now, however, drag clicking might not.
      - Selection delete `alt+del`
      - The file will autosave on exit, you can disable that if you would like.
      - Mass comment with `shift+arrow` then (`alt+3`)
      - Word delete back with 
