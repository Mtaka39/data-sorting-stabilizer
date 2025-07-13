# data-sorting-stabilizer
The original GoPro data and DJI AVATA2 data are automatically divided into folders for stabilization data and original data using Automator on the Mac
How to use with Automator (zsh only)
	1. go to Automator → New App
	Add "Run Shell Script
	Paste the above script 4.
	Select “/bin/zsh” in the “Shell:” field ← Important. 5!
	Set “How arguments are passed” to “As arguments” 6.
	6. give it a name and save it as .app (e.g. video_autosort_zsh.app)
