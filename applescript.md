```applescript
-- Scrape all URLs from all tabs in all windows
-- https://forum.keyboardmaestro.com/t/save-and-restore-safari-session-tabs/15036/4
set AppleScript's text item delimiters to linefeed
tell application "Safari"
   set urlList to (URL of tabs of windows) as text
end tell
return urlList
```
