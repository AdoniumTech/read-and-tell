We do not specify the file but say that we 
are putting the vite files in this directory we have already made
I think for this let us use Javascript instead of typescript.
Both could work really but i prefer javascript

Assuming you have nodejs install these should continue as normal

the other terminal has our project running. We can check it out. I put auto save, but usually react updates the DOM (the browser image in very simple terms) automatically as you change

So we have installed vite, it is running on port 5173, and we have installed tailwindcss also for vite

So you have added it to the config files

Import tailwind to the main css file of the project

And you are done!!!

I will try change the page we load

React files use jsx

Lets change some of the styling with tailwind. So we will change the color of the text for mobile screens and for laptop screens

You want to have a base style and then specify for the screens. So if you want a bit more of a guide you can check the tailwind docs

Another thing is to avoid styles clashing remove the css from the css files. In the index just have the tailwind import.

So it is way easier with tailwind to design screens for different sizes and have the design look good like with CSS. It is the same principle but shorter syntax. in the classname property you put your values.

e.g. for background => bg-white or bg-red-500. The numbers are the intensity of the color. it goes 50, 100, 200, ... 800, 900. The bigger the number the more intense it is. Only black and white doesn't have the intensity.

Now let us make a branch to push it to (You should have already moved to your own branch when making any changes)

You can use git checkout -b <branch-name> or git switch -c <branch-name>

-b is for a new branch
-c is to create new branch

push -u is only used on the first time you are pushing a branch. After that you don't need to

Lastly I will show you the pull request
in this case there isn't any comparison but there are points where there is e.g