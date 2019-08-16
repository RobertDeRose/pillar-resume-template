<a
href="https://themes.3rdwavemedia.com/bootstrap-templates/all/free-bootstrap4-resume-cv-template-for-developers-pillar/"
target="_blank"><img
src="https://themes.3rdwavemedia.com/wp-content/uploads/2018/05/Bootstrap-Resume-CV-Template-Pillar-Pormo.jpg"
alt="Bootstrap 4 Resume/CV Template for Developers" /></a>

## The Pillar Resume Template as a Jekyll site

This is a modification to the Pillar Bootstrap 4 Theme. It has been converted to
use the [Jekyll](http://jekyllrb.com) static site builder. This allows you to
host your Résumé on Github.com or other static hosting services.

Located in the `_data` directory is a `yml` file that is broken into sections.

* bio
    - Top section with your contact information
* summary
    - A full-column section to decribe yourself
* history
    - Your work history
* skills
    - The different skills, languages, and technolody you use
    - Broken down into Frontend, Backend, and Other
        - If you exclude any of these sections, the heading will not be
          displayed
* education
    - Where you went to college, if you did
* awards
    - Any rewards you received for your work
* languages
    - The languages you speak or write
* interests
    - Things that interest you
* organizations
    - Different organizations you are in volved with
    - Could be volunteer or professional groups

The nice thing about this theme is that is looks pretty good printed right out
of the boxes. However, you might be tempted to add a lot of detail on your work
history since you have infinite vertical scrolling. To combat the printer
fatigue, you can use pure HTML in your descriptions and use Bootstrap 4's media
queries to exclude some content when your resume is printed.

You can see some example of this in the data for my Resume. I include sections
of HTML with the tag:

```html
<div class="d-print-none" markdown="1">
    .
    .
    .
</div>
```
These sections are then excluded when my Resume is printed. You can also force a
page break for printing if you want to ensure a new history section starts on a
new page when printed. This can be done by including `page_break: true` as one
of the properies for your `role`

## Theme Color

To set the theme primary color you can set inside the `_config.yml` file the
variable `theme_color`. It can be one of the following values:

* cello
* curious_blue
* eucalyptus
* scooter
* governor_bay
* cosmi

This uses YAML anchors, so ensure you include the `*` infront of the variable
name.

## Modification from Original Theme

To support better printing, `@media` queries have been added to the Pillar theme
to remove the `box-shadow` from the `resume-wrapper-inner` class and set the
`background` of the `boyd` to `white`.

## Favicon Generator

I really like this website for helping to generate favicons:

https://realfavicongenerator.net

Dump the contents in the root of this template for them to automatically be used.

The device specific icons that use color, will use the primary color you select for your theme.

<hr>

* *The rest of this readme comes from the author of the bootstrap theme with a few modification to make it make sense with the changes made for Jekyll*

## [Demo](https://themes.3rdwavemedia.com/demo/pillar/)


Pillar is a **free Bootstrap 4 resume/CV template** made for developers by
[Xiaoying Riley](http://themes.3rdwavemedia.com). Built on **Bootstrap 4 and
SASS**, it's quick and easy to change the template styling. This template is
designed to **help you with your job hunting** and **boost your chances of
getting the web development job you want**!

**There is a printable version as well** Released as a [free Sketch
template](https://themes.3rdwavemedia.com/resources/sketch-template/pillar-sketch-sketch-resume-template-for-developers/)
for this theme. [Download
Now](https://themes.3rdwavemedia.com/resources/sketch-template/pillar-sketch-sketch-resume-template-for-developers/)

<a
href="https://themes.3rdwavemedia.com/resources/sketch-template/pillar-sketch-sketch-resume-template-for-developers/"
target="_blank"><img
src="https://themes.3rdwavemedia.com/wp-content/uploads/2018/12/pillar-theme-sketch-template-promo.png"
alt="Pillar Sketch - Sketch Resume/CV Template for Developers" /></a>

## Author & License

This Bootstrap template is made by UX/UI designer [Xiaoying
Riley](https://twitter.com/3rdwave_themes) for developers and is 100% FREE as
long as you **keep the footer attribution link**. You do not have the rights to
resell, sublicense or redistribute (even for free) the template on its own or as
a separate attachment from any of your work.

If you'd like to **use the template without the footer attribution**, you can
[buy the **commercial license** via the theme
website](https://themes.3rdwavemedia.com/bootstrap-templates/all/free-bootstrap4-resume-cv-template-for-developers-pillar/)

#### Follow Xiaoying

[Twitter](https://twitter.com/3rdwave_themes)

[Facebook](https://www.facebook.com/3rdwavethemes/)

[Dribbble](https://dribbble.com/Xiaoying)

[Medium](https://medium.com/@3rdwave_themes)

[Linkedin](https://uk.linkedin.com/in/xiaoying)


## Latest Version
**v1.0.1** - 23 July 2018

[Changelog](https://themes.3rdwavemedia.com/bootstrap-templates/all/free-bootstrap4-resume-cv-template-for-developers-pillar/?target=changelog)

## Colour Schemes

#### Colour 1 (cello)
<img
src="https://themes.3rdwavemedia.com/wp-content/uploads/2018/07/pillar-theme-1.jpg"
width="400" alt="Pillar color 1" />

#### Colour 2 (curious_blue)
<img
src="https://themes.3rdwavemedia.com/wp-content/uploads/2018/07/pillar-theme-2.jpg"
width="400" alt="Pillar color 2" />

#### Colour 3 (eucalyptus)
<img
src="https://themes.3rdwavemedia.com/wp-content/uploads/2018/07/pillar-theme-3.jpg"
width="400" alt="Pillar color 3" />

#### Colour 4 (scooter)
<img
src="https://themes.3rdwavemedia.com/wp-content/uploads/2018/07/pillar-theme-4.jpg"
width="400" alt="Pillar color 4" />

#### Colour 5 (governor_bay)
<img
src="https://themes.3rdwavemedia.com/wp-content/uploads/2018/07/pillar-theme-5.jpg"
width="400" alt="Pillar color 5" />

#### Colour 6 (cosmic)
<img
src="https://themes.3rdwavemedia.com/wp-content/uploads/2018/07/pillar-theme-6.jpg"
width="400" alt="Pillar color 6" />

## Features

-  Fully Responsive
-  HTML5 + CSS3
-  Built on Bootstrap 4
-  **SCSS** source files included
-  6 Colour Schemes
-  1000+ FontAwesome 5 icons
-  Compatible with all modern browsers

## Credits
- [Bootstrap](http://getbootstrap.com/)
- [FontAwesome](http://fortawesome.github.io/Font-Awesome/)
