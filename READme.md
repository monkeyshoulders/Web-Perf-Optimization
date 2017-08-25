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
- Open a window in your Terminal orcommand line tool for your computer & navigate to the folder where this project was saved
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

- All images were compressed using Compressjpeg.com
- All CSS, JS, and HTML files were minified
- Files were copied into **DIST** and **SRC** folders for future modification purposes and web serving for optimal performance
- Inling of CSS properties to speed page loads
- Moved style and link tags associated with CSS and JS to bottom of body in HTML to reduce reder blocking
- JS files were changed to load asynchronusly
- Modified main.js to fix forced sychronus layout issues on lines
        - *main.js* line 549 asdkjbsadhsaoifjknsdf
        - *main.js* line 463 lkjasdlfkhasdkjhfkjhsdf


#### Resources used to complete this project ####

Along with the the course material provided by Udacity in the Website Performance Optimization course and the webcast associated with it, I also used the following articles and sites:

- https://developers.google.com/speed/docs/insights/rules
- dillenger.io a tool for writing markdown
- https://ngrok.com/
- http://compressjpeg.com/ JPEG compression
- https://www.youtube.com/watch?v=oy13mDsXC4s Ngrok tutorial
- https://www.youtube.com/watch?v=pNKnhBIVj4w Getting your pagespeed up - Google
- http://www.minifier.org/ Minify JS and CSS files
- http://minifycode.com/html-minifier/ HTML minifier
