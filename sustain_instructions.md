### Sustain Template Customozing Instructions 

Use the instructions in the tutorial to fork biomadeira's sustain repository, however **DO NOT** rename as USERNAME.github.io in the repository settings.

**1. RENDERING WEBSITE AND EDITING HOMEPAGE LINKOUTS**

Edit config.yml

lines 13-26

**2. UPDATING HOMEPAGE CONTENT**

Edit index.html file

lines 10-12

**3. UPDATING PHOTO**

static/img folder

delete file (this will also delete the folder as you cannot have empty folders in Github)

You can make a new `img/` folder in your repository. To do this, we will need to create a dummy file, because git requires a file in a new folder. Click on the "Add a New File" button in the root directory and type in `img/dummyFile`. Commit this dummy file into the repo and you should now see that the `img/` folder has been created. Now you can upload images into to that directory using the `Upload Files` button. 

upload a replacement image, named “profile.png” (you may remove the dummy file in the folder if you like)

**4. REMOVING “FORK ME” BANNER**

_layouts/layouts.html

Delete line 51 

**5. EDITING “PROJECTS**

_includes folder/projects.html

edit line 8 onward, keeping the line above with the text for each project “Project 2</a></strong>”

**6. CREATING “BLOG POSTS**

_posts folder (blog posts)

Post 1: Introduction using mid form bio

Raw, Select All, Copy from post1

Create new file with today’s date

Paste text into new file

Edit Title on Line 3: Hello World – Introduction 

Remove/Replace everything after line 9

*delete the file that you copied

**7. ENTER YOUR CV/RESUME**


Fork biomadeira's [CV template](https://biomadeira.github.io/vitae/) 

Edit _config.yml file (lines 10-32)

Edit _includes folder (all files, lines 5-end)

**OPTIONAL – updating homepage link text (Resume -> CV)** 

_includes/header.html

Replace “Resume” with CV on line 10

**OPTIONAL – remove stack overflow link on homepage**

_includes folder

social.html file

Delete lines 16-18

**OPTIONAL – change green color**

static folder/css/main.css

Replace #27A822 with 3498cc on lines 9 and 177 (header/footer border)

Replace #27A822 with 3498cc on lines 99 and 102 (text)
