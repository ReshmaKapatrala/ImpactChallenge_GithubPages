### Sustain Template Customozing Instructions

Use the instructions in the tutorial to fork biomadeira's sustain repository and rename as USERNAME.github.io in the repository settings. 

**1. CREATE A MASTER BRANCH FOR THIS REPOSITORY**

At the main page for the repository, click on the "Branch: gh-pages" drop down arrow and type "master" to _create_ a master branch.

**2. UPDATE GITHUB PAGES SOURCE**

In the repository settings, select "master branch" as the source for your Github Pages site.

**3. RENDERING WEBSITE AND EDITING HOMEPAGE LINKOUTS**

Edit config.yml

lines 13-26

**4. UPDATING HOMEPAGE CONTENT**

Edit index.html file

lines 10-12

**5. UPDATING PHOTO**

static/img folder

delete file (this will also delete the folder as you cannot have empty folders in Github)

make a new folder called "img" in the static folder by clicking the "create new file" button, entering "img/" (the forward slash designates the folder), followed by "empty" or "placeholder" to add a dummy file to your new img folder

upload a replacement image, named “profile.png” (you may remove the dummy file in the folder if you like)

**6. REMOVING “FORK ME” BANNER**

_layouts/layouts.html

Delete line 51 

**7. EDITING “PROJECTS**

_includes folder/projects.html

edit line 8 onward, keeping the line above with the text for each project “Project 2</a></strong>”

**8. CREATING “BLOG POSTS**

_posts folder (blog posts)

Post 1: Introduction using mid form bio

Raw, Select All, Copy from post1

Create new file with today’s date

Paste text into new file

Edit Title on Line 3: Hello World – Introduction 

Remove/Replace everything after line 9

*delete the file that you copied

**9. ENTER YOUR CV/RESUME**


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
