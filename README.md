# ReadMe Dev Portfolio 

This repo contains an easy-to-customize personal dev portfolio template that was created with Sass and JavaScript. It is lightweight and fully responsive, as well as comes with the Bootstrap grid system and loaded with Font Awesome. The site is static and comes production ready if you just want to add your information and go. Alternatively, you can edit styles, colours, and scripts fairly easily. The site was built as modular as possible to make it easy to shift around styles and content.

# Features
- Gulp ready (compiles Sass and minifies JS)
- Sass ready with lots of commenting
- Fully responsive
- Comes with Bootstrap grid system
- Easy colour changes can be done through simple variable edits

# Images
By default, the template comes with a number of images, some of which can be kept and others which act simply as placeholders and should be switched. The template contains the following:

- Main background (images/lead-bg.jpg) - this is the main background image provided via Unsplash. This can be kept or changed easily by replacing images/lead-bg.jpg with your new background (recommended size of at least 1920x1080).
- Favicon (/favicon.ico) - this is the favicon used for the page. Similar to the main bg, this can kept or changed easily by replacing the favicon.ico with your new one.
- Project image - these are the images associated with the projects under the project section. These are simply placeholders and should either be replaced or removed.

# Header Section
The header section can be found within the <header> tag and simply contains an unordered list of anchors to different sections of the page. If you add a new section and want to be able to quickly navigate to it from the top, simply add another list element with an anchor that has the href of the ID of the section. Conversely, if you remove a section, don't forget to remove the associated navigation element.

# Lead Section
The Lead section is pretty straightforward, it contains an h1 for your name and an h2 for your title. It also contains a link that can be used to link to your resume should you wish to add it as well.

If you want your resume to automatically download when the button is clicked instead of opening up in another tab (the default behaviour), add the following code (Thanks to jkfran for the suggestion) in the lead:
<a href="path/to/resume.pdf" download="resume.pdf" class="btn-rounded-white">Download Resume</a>

# License
Completely free (MIT)