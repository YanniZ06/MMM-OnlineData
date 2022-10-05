# MMM-OnlineData
Repository for storing online data to send to every MondayModMixxin' application.

## WHAT THIS WILL DO
Shortly put its like a lightweight twitter variant exclusive to each and every build, and changing the "newsMenu.txt" file over GitHub and then getting info over it from the main app over http requests allows us to give updates and other shit easily without forcing people to download new builds whatsoever!


# HOW TO USE
## SYNTAX
For this shit to work you need to follow a special syntax i had to come up with, one example has already (as of now) been made inside the target file "newsMenu.txt".
All of the fancy shit goes on in that text file and gets encoded into a cool article in the actual build using http and a ton of StringTools shit!!
### ARTICLE HEADER
Article headers are marked by the starting-keyword "##ENTRY_HEADER", followed by whatever the article title/header should be, enclosed in brackets.

FOR EXAMPLE: ##ENTRY_HEADER["First Online entry woohoo!!"] (the quotations are not mandatory, and will be added into the article name if put)
### NEW LINES
Each new line is simply marked by a "#[l]", it also needs to be in the first line to check when the article text starts.

The following text can then be written however you want to, inside the application will be automatically formatted to stay inside the article box.

Repeat this for each new line you add!
### IMAGES
To attach an image, simply write '##[image:' at the last line before the article ends, or anywhere really (but for keeping it organized its recommended to be put at the end.

Then, in quotations marks (""), you put in the name of the image inside this repo, with the file format at the end aswell (.png, .jpeg...) and after the second quotation mark add a closing bracket (])

FOR EXAMPLE: ##[image:"exampleImage.png"] (here, the quotes are mandatory, they also NEED to be double quotes in order to work
### MARKING THE ARTICLE END
To mark the end of one article, write "##ENTRY_END" after the last line/the image implementation.

To add another seperate article, start with a new ARTICLE HEADER and follow the order specified in the "newsMenu.txt" document.

# ON ANY FURTHER QUESTIONS JUST DM ME LOL!! - Yanni
