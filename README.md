# YouTube Music Playlist Creator
This Python Selenium code reads a list of song titles from a text file and searches for them on YouTube Music. If a song is found, it's added to a playlist. If it's not found or a video is found instead, the program moves on to the next song.

# Prerequisites
1. Python 3
2. Selenium WebDriver
3. undetected_chromedriver
4. Chrome browser

# Usage
* Clone this repository or copy the code into a Python file.
* Make sure you have the prerequisites installed.
* Edit the name of the text file with your song titles on line 11 ("갖고있는 모든 노래.txt") to match the name of your file.
* Run the program.
* Wait for the program to finish.
* Check the generated files for any errors or songs that couldn't be found.

# Generated files
The program will generate two text files:

1. 동영상.txt: This file will contain a list of song titles that couldn't be found because a video was found instead.
2. 오류.txt: This file will contain a list of song titles that couldn't be searched for because of an error.

# Notes
* This program uses XPath expressions to interact with the web page. If the layout of the page changes, the XPath expressions might need to be updated.
* The program uses a 0.2 second delay between interactions to give the page time to load. If the page is slow, you might need to increase this delay.
