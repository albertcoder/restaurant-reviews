# Restaurant Reviews App Stage 1 | Udacity FEND | 2018

Project five of seven for Udacity's Front End Web Developer Nanodegree; completed as part of the Grow with Google Scholarship program, 2018.

## Authors

The starter code for the project was provided by Udacity; the original repository can be accessed [here](https://github.com/udacity/mws-restaurant-stage-1).

In accordance with instructions and a rubric provided by Udacity, I -- Udacity student Albert -- edited the files `index.html`, `restaurant-info.html`, `styles.css`, `main.js`, `restaurant_info.js` and `README.md`, all provided with the starter code, and also added the files `styles-428plus.css`, `styles-498plus.css` and `sw.js`, and added files to the `img` folder, to implement the following: mobile-first responsive design, updates to the app's styling, enhanced accessibility features focusing on tab index, semantic markup and ARIA, and a service worker enabling offline functionality. 

In addition to signifigant edits made to portions of the starter code, I added some features seen in this project in their entirety, including in particular: a shrinking navigation bar on scroll down, a radio-group pattern that allows users to navigate through and interact with elements inside the map when it comes in to focus and a scroll-to-top button, all intended to enhance accessibility and overall user experience.

## Instructions

1. Create a local directory on your machine and clone the repository to it. For help with this step, see [this tutorial from GitHub](https://help.github.com/articles/cloning-a-repository/ "GitHub Help — Clone a Repository").

2. You will need to start up an HTTP server to run the site from your local machine. Complete the following steps, which were were adapted from instructions included in the README of the starter code provided by Udacity for this project, in the section "What Do I Do From Here?".

    * Check if Python is installed on your computer by typing the command `$ python -V` in to a terminal window. If Python is installed, the terminal should return information about what version of python you are running.
    
      * Apple computers running MAC OS X come with Python out of the box.

    * If Python is not installed, download and install the software [from the Python web site](https://www.python.org/ "Python Home Page").

    * If you are using GitBash in Windows, you may need to tell the operating system where to find Python. Do this with the command `PATH="$PATH:/<yourPythonLocation>`. For example: `$ PATH="$PATH:/c/Python37`. 
    
    * For more instructions on getting Python up and running, you may wish to check out [this tutorial](http://interactivepython.org/runestone/static/pip2/Installation/pythonInstall.html "'Intall and Configure Python' by Interactive Python") from Interactive Python.

    * Make your cloned respository the current directory in your terminal window, and then enter the command `python -m SimpleHTTPServer 8000` if you are running Python version 2.X, or the command `python -m http.server 8000` or `python3 -m http.server 8000` if you are running Python 3.X.

    * Navigate to `https://localhost:8000` — you should now see the app up and running in your browser!'

3. Narrow and expand the width of your browser's display window, or open up your browser's developer tools panel and inspect the app's pages appearance on different-sized devices, to explore the app's responsive design features.

4. Explore some of the accesibility features of the app by pressing tab to move the focus between elements.
  
5. When the map has focus, you can use the arrow keys to navigate through the functional elements inside the map. Press enter to interact with any of these elements when it has focus. 
  
    * You can zoom in and out on the map, navigate to details about a restuarant via its marker on the map, and check out links about the map API.

    * The implementation of keyboard-accesibility on elements inside the map — which also helps make the app more accessible using additional technologies — essentially follows a radio-group design pattern, and utilizes a [roving tabindex](https://developer.mozilla.org/en-US/docs/Web/Accessibility/Keyboard-navigable_JavaScript_widgets#Managing_focus_inside_groups "Overview of roving tabindex technique for managing focus inside groups on MDN") technique. Thus, when you use tab to move focus away from the map and then later move the focus back to the map and use the arrow keys to start navigating through elements inside the map again, the last element to have focus when the map was tabbed away from will be the first element to receive focus again.


6. Scroll up and down the page to see the shrinking navbar feature. This feature is intended to improve user experience and the site's usability for users accessing the site's content visually.


7. Select a restaurant's marker on the map, or select the "Details" button in a restaurant's card on the main page to navigate to a page providing futher details about the restaurant, including hours of operation and reviews of the restaurant.


8. Use a screen reader to explore and evaluate more of the app's accessibility features. If you don't have a screen reader installed, adding the [Chrome Vox extension](https://chrome.google.com/webstore/detail/chromevox/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en "Chrome Vox Extension") to the [Google Chrome browser](https://www.google.com/chrome/browser/ "Google 
Chrome") is one option to get up and running quickly.

9. If you tab or scroll all the way to the bottom of the page, you should eventually reach a scroll to top button in the footer. This feature was included to enhance accessibilty for users navigating the app using a keyboard and other technologies, and to improve overall user experience.



## Acknowledgements

* Udacity provided the starter code for this project, and included a spec sheet with instructions for "taking a static design that lacks accessibility and [converting] the design to be responsive on different sized displays and accessible for screen reader use." Students were also instructed to "add a service worker to begin the process of creating a seamless offline experience for ... users." The starter code is available [here](https://github.com/udacity/mws-restaurant-stage-1).

* As provided in the starter code, the map included in the application uses [leaflet.js](https://leafletjs.com/) in conjunction with [Mapbox](https://www.mapbox.com/).

* The lessons in sections 1 through 4 of Udacity's Front-End Web Developer Nanodegree program as accessed in 2018 were indesensible in helping me learn the skills and gain the knowledge I needed to apply to succesfully complete this project.

* Fellow Udacity students esp. Jacob Olson and the wider programming community provided a crucial and inspiring source of knowledge, support, resources and encouragment.

* Fellow Udacity scholar Matthew Cranford's [series of "Walkthrough" posts](https://www.matthewcranford.com) for this project were consulted, helping inform the approach and logic I used in completing my version.

* Funding for my participation in the Front-End Web Devloper Nanodegree program comes courtesy of the Grow with Google Scholarship program.

* Edits and additions I made to `main.js`, `restaurant_info.js`, the applcation's CSS files, to `index.html`, to `restaurant.html` and to `sw.js` relied on the following sources, which are also referenced in the project's files immediately preceeding each relevant section or line of code:


        Thank you for checking my project and feel free to collaborate.
  
        -Albert
    