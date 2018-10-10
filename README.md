## sass-intro
This is an introduction to "Sass" which is a precomputing scripting language used to make css more efficient


## Pre-Requisites : SASS and Ruby

/** If you do not have SASS or Ruby then download and install Ruby from the links below **/

# Ruby : https://rubyinstaller.org/downloads/

# SASS: https://sass-lang.com/ruby-sass (How to install)

to verify the installation type "ruby -v" and "sass -v"


## /* Github and The process I followed: */


```
        Step 1 : I created my repository "sass-intro" for the introduction of the scripting language called SASS and intialized it with this README file. 

        Step 2 : I then made the folder live by going into the repository and going into "settings" > "Github Pages" > "Source" click on "None" and change it to "Master Branch" (The first option). Your page will refresh and you'll need to scroll down to the Github pages section again and copy that link that has just appeared. 

        Step 3: Copy that link and add it into your description as well as the website, but don't forget to add in "/index.html" without the "" to the end of your link.

        Step 4 :  I created the base folders as well as the index.html file for the project.
```

```
            ###Open your command line of preference

            clone your folder to your desktop by adding in this commands:

            -step 1: cd desktop [Enter]
            
            -step 2: git clone {and your live link goes here/index.html} (*NB*: remove the {}) [Enter]

            -step 3: once cloned you could then navigate to that folder by typing "cd sass.." and press TAB and it will populate the folder name for you. and press [Enter]

            -step 4: type "mkdir css images scss" without the "" and press [Enter] this will create your base folders.

            -step 5: now type "touch index.html" and press [Enter] and it will create your index.html file.

            -step 6: navigate to the scss folder by typing "cd scss" and hit [Enter], then within that folder type the command "sass --watch scss:css" without the ""
```

# Step 5 : Open your text-editor of preference and watch what happens when you make changes in your scss file. It will update the css automatically because of the watch command that is running within your command-line.

## **NB** - importing using "partials" :
    - you create a sub-folder within the "scss" folder.
    - create the following files in your text editor within the scss folder > _base.scss,   _components.scss,  _responsive.scss,  _variables.scss,
    -to link these styles to your site you need to use the @import

You can access the link to my site here: https://reaganbeck8.github.io/sass-intro/index.html 

