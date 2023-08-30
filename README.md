## Motocross & Enduro

This is README for my first Portfolio Project.

I will build a website that has some basic information about motorcross and enduro. What's the different. And me riding. The website will also contain a gallery with images related to the website's content.

The site will be developed with the concept of "mobile first" to be able to fit small screens and then be responsive for bigger screens.

The idea is to have one index.html and two sub pages. One with pictures and one with information about me as a rider and information about motocross and enduro riding.

The basic idea is to have it simple with some small 3d effects.<br>
<img src="readmefiles/idea.jpg" width="200" alt="First idea drawn on paper.">

## Features
---

Existing Features
Navigation Bar

Featured on all pages, the full responsive navigation bar should be centered with equal space between to follow the different sceen widths. Three links to Home, an image libaray and to an about page. This should look the same on all pages.
The navigation liks should always be visible to minimize the amount of clicking but also big enough to be able to use with a finger on a cell phone.
This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the browser's ‘back’ button.

The first basic structure looks like this:<br>
![First structure.](readmefiles/structure.jpg)<br>
This will be the main theme for all pages and will be added with contents.

I wanted my logo as a hero image:
![Robstar Racing logo](assets/images/robstar-racing.jpg)<br>
I made sure it has the width of 1920 pixels to cover most of the screens.

I really liked the idea of the footer from the Love Runing project. So I used that knowledge from that and made it fit my design.<br>
![Image of the footer](readmefiles/footer-image.jpg)<br>
I made the links work to my Facebook page, YouTube and Instagram. I made them open in new windows. But beware, the pages are in Swedish.

Also the gallery idea from the Love running project was a nice feature. Especially the feature that made the image sort up in more columns 
the wider the screen gets.
![Example of some images from the image page](readmefiles/images-image.jpg)

In the about page I wanted the visitor to be able to read some about me and what's the different between motocross and enduro. 
I can write a lot about but I think the content is enough for now.

Finally after some time I started to feel satisfied with a good site:<br>
![Final design of index page](readmefiles/index-view.jpg)![Final design of image page](readmefiles/image-view.jpg)![Final design of about page](readmefiles/about-view.jpg)


## Testing
---
I first tested the code when the first structure was made.<br>
![First test](readmefiles/first-test.jpg)<br>
I got some info about "Trailing slash on void elements" but corrected it to get a nice ok.

When I felt that I was starting to be done. I tested all the code again.
All the info about "Trailing slash on void elements" was back. And I noticed that Codeanywhere add this automatically. So this time I decided just to filter that so it doesn't show everytime.
But I got some warnings that I should add a header. Which I did with a class to hide it.



You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Codeanywhere and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **July 26th, 2023**

## Codeanywhere Reminders

To run a frontend (HTML, CSS, Javascript only) application in Codeanywhere, in the terminal, type:

`python3 -m http.server`

A button should appear to click: _Open Preview_ or _Open Browser_.

To run a frontend (HTML, CSS, Javascript only) application in Codeanywhere with no-cache, you can use this alias for `python3 -m http.server`.

`http_server`

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A button should appear to click: _Open Preview_ or _Open Browser_.

In Codeanywhere you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to _Account Settings_ in the menu under your avatar.
2. Scroll down to the _API Key_ and click _Reveal_
3. Copy the key
4. In Codeanywhere, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

---

Happy coding!
