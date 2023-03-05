# Web-Scraping
Web scraping with HTTrack
the process of translating the html codes we pull from the internet;

In the code screen line 13 "files_from_folder" will refer to what is in our html or index folder.
In line 19, we specify that we want the data we want to extract to have an hmtl extension.
On line 23 we are performing file reading.
There is a separate module between Line 25 and 34, we use that module, in that module the part of translating Turkish words in html to Hindi takes place.
We read the files on line 36. It gives a list of all the html files in the html directory, which we call os.listdir on the nu line, and gives them as strings.
In line 43, we pars the data inside our html. then it finds and translates the titles.
It finds and translates the h1s in the for block starting at line 53.
It finds and translates P's in the for block starting at line 65.
in the for blockers below; Whatever data we want it to find in each for block, it finds and translates them one by one.
After the translete operations are finished, it creates a directory on line 106 that it calls translete. After typing, the process is complete.
