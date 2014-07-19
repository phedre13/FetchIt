FetchIt
=======

FetchIt is a python-based scraper.  It is not intended for illegal purposes, and this is my first real project in Python.  Everything previously has been in the form of mini-scripts.  Feel free to take it, but if you do illegal things with it, then you have edited it beyond its intended purposes.
=======

Running This Script:
1. Download the file and put it where you want its generated files to be.
2. REMEMBER WHICH DIRECTORY IT IS IN (or write it down).
3. In your terminal, type "python fetchit".
4. Follow the script's instructions for further running (IE type in 'y' and hit enter for the first question).
5. Use the files that were created!

How It Works:
First, we verify that the user realizes this script was created for LEGAL purposes.  Then, we proceed with grabbing the main site from which we will find our subsequent links.  Until this is revised for more generic purposes, that is remotecentral's remote brand list.  From there, we follow every link that will match the stem "http://www.remotecentral.org.com/".  The generated URLs are parsed for further pages, which are combined with the links from the initial pages and parsed for 'tv' or 'TV'.  After this is done, the script will go into anything that was labelled correctly and create separate files for each segment of view source code.  Those will in turn be parsed for "power", "on", or "off".  Any lines containing those terms will be placed line-by-line into a file.  This last file is meant to be the necessary information.

Have fun and stay out of trouble!!
