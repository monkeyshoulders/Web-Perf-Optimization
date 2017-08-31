# Website Performance Optimization Project
---

This project was optimize a website and it's linked sites to render under 60FPS and score over 90 on Google's Page Speed Insights. This project was designed as part of the Frontend Web Development Nanodegree and part of a final project for the course: [Website Performance Optimization](https://www.udacity.com/course/website-performance-optimization--ud884)

## How to Evaluate Page Speed
This page can be evaluated two ways using either Github.io or Ngrok. The first step is to download or clone this repository to your local machine.

##### To evaluate pages speed score using Gitub.io :

- Click the link to navigate to [Google's Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/)
- Paste the following URL into the search bar
```sh
https://monkeyshoulders.github.io/frontend-nanodegree-mobile-portfolio-master/
```
- Click the **Analyze** button

##### To evaluate pages Speed Score using [Ngrok:](https://ngrok.com/)
- Navigate to Ngrok.com and download the version for your operating system and follow the download instructions and the instructions for setting up a secure tunnel
- Open a window in your Terminal or command line tool for your computer & navigate to the folder where this project was saved
- Type in your terminal window
```
$ python -m SimpleHTTPServer 8080
```
- Now in a second window or tab in your terminal navigate to the folder where this project was saved and type:
```
$ ngrok http 8080
```
- Ngrok will change your terminal window and run as a command line program
- Open a browser window to [Google's Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/)
- Paste the second forwarding URL provided by Ngrok into the search bar
example:
```
https://123a45b6c.ngrok.io
```

- Click the **Analyze** button

## Changes I made to complete project ##

Changes had to made to be made to several files to obtain the parameters of the projects outline.

- All images were compressed and resized
- All CSS, JS, and HTML files were minified
- CSS file for index.html and project.html files were completely edited and inlined except for a few lines in the header
- Files were copied into **SRC** folder for original editable formats
- Moved script and link tags associated with CSS and JS to bottom of body in HTML to reduce render blocking
- JS files were changed to load asynchronously
- *main.js* querySelectorAll changed to querySelector, getElementsByClassName, and getElementById
- *main.js* see lines 431, 432, 439, 441, 458, 459, 490, 493, and 514 for changes comments

#### Resources used to complete this project ####

Along with the the course material provided by Udacity in the Website Performance Optimization course/webcasts and with 1:1 mentor appointments, I also used the following articles and sites:

- https://developers.google.com/speed/docs/insights/rules
- dillenger.io a tool for writing markdown
- https://ngrok.com/
- http://compressjpeg.com/ JPEG compression
- https://www.youtube.com/watch?v=oy13mDsXC4s Ngrok tutorial
- https://www.youtube.com/watch?v=pNKnhBIVj4w Getting your page speed up - Google
- http://www.minifier.org/ Minify JS and CSS files
- http://minifycode.com/html-minifier/ HTML minifier
- https://developer.mozilla.org/en-US/docs/Web/CSS/will-change
