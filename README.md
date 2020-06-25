# automatic-tinder-swipe-macbook
Automatic tinder swipe script for macbook

Steps:
1. Press "Command" key + "Space" key, enter script editor in the prompt. Press "Enter" key to open it. <br/>
![open script editor](src/resources/img/open_script_editor.png?raw=true "Open Script Editor")

2. Click on "New Document" <br/>
![click new document](src/resources/img/script_editor_pre_window.png?raw=true "Click New Document in Script Editor")

3. It will open a window like this:
![script editor blank window](src/resources/img/script_editor_window_without_code.png?raw=true "Script Editor Blank Window")

4. Paste this code to the editor area:
  ```
  tell application "System Events"
	  delay 2
	  repeat with i from 1 to 1000
      delay 0.5
      keystroke (key code 126)
      delay 1
      keystroke (key code 124)
	  end repeat
  end tell
```

It will look like this:
![script editor with code](src/resources/img/script_editor_window_with_code.png?raw=true "Script Editor with code")

5. Enter the code and press run.

6. Go to chrome and open tinder. Make sure cursor focus is on tinder page.

7. Sit back and enjoy.
