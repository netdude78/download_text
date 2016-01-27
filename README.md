Simple Pythonista script that will download the text from a specific URI shared through iOS Sharing sheet.

I created this simple Pythonista script to be able to download files from github, although it could be used
to fetch the text of any web page and save it to a file inside the Pythonista jailed file system.

	For Example:
	In Safari on your i*device, open up the github website.  Navigate to a file in a repository.  Click the "Raw"
	button to get JUST the script.  Then click the "share" button in iOS.  Choose to open Pythonista and run this script.

	Once the script runs, it will prompt you for a filename to save.  That will be the file saved inside the Pythonista
	filesystem.  Another confirmation dialog will appear with the size (in bytes) of the file.  This dialog gives the user
	an opportunity to abort the download if the file is larger than expected, thus hopefully preventing filling up space on
	the device.

If this script is launched directly instead of from the sharing menu, an error message will be displayed and the program
will exit.

Contributions welcome.  Hack away.  Have fun.