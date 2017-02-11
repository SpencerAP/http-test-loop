# HTTP Test Loop

Experiencing an itermittent connectivity or routing issue? Curious about the frequency or pattern of that issue? HTTP Test Loop runs curl in a loop, attempting to hit a given URL every 10 seconds, and recording either "fine" or "TIMEOUT". The log file can be eyeballed or parsed programmatically to gain perspective on the issue.

Should work for both macOS & Linux.

# CLI (Terminal) Instructions

1. Place the http-test-loop script on your desktop
2. Edit it to set the URL you'd like to test
3. Change working directory to your Desktop (`$ cd ~/Desktop`)
4. Mod executable (`$ chmod +x ./http-test-loop`}
5. Run it! (`$ ./https-ps-test`)

The script will begin logging successes/failures to the log file until you tell it to stop (Ctrl-C). The log file will be placed in the user's home directory.

