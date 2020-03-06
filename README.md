# Moodle Multitopic Format ⭐

Note by Brad Nielsen who has forked this repository and edited it significantly. My edits are prefaced by the name BRAD.

This is by far the best format on Moodle for using sections within sections and the work of James Calder in developing this format should be admired. I cant wait to try it on the College in which I work. I have made a few edits though - mainly to go with the Lambda theme that my College is using. So the Course Format CSS has changed significantly which might make it ugly for others. I have then added some things which I have always wanted with a theme as well.

1. Labels can be added more easily
2. The Announcements Forum now appears on Page 1 as opposed to being hidden in a link.
3. More config options..


> Shows multiple topics per page, with tabbed navigation between pages.  Topics are collapsible, and can optionally be timed.

### 🏠 [Otago Polytechnic](https://op.ac.nz)


## Install

1. Copy files to moodle/course/format/multitopic
2. Log in as an admin, and visit moodle/admin/index.php, to update plugin data
3. Site administration > Appearance > Additional HTML > Within HEAD (or other location appropriate for CSS): Copy and paste styles from README_styles.css (customising appropriately)
4. Site administration > Appearance > Themes > Theme settings > Allow category themes: Yes (if you want categories to have custom CSS)


## Features

* Tabbed pages (like Onetopic format)
* Multiple topics per page (a bit like Flexible Sections format)
* Collapsible topics (like Collapsed Topics format)
* Optionally timed topics (like Weekly format)
* Course banner image (like Snap theme)
* Section images (a bit like Grid format)


## Author

👤 **James Calder**

* Github: [@james-cnz](https://github.com/james-cnz)


## Docs

🚀 [Roadmap](docs/roadmap.md)
📄 [Contributing](docs/contributing.md)


## Acknowledgements

The Multitopic format is based on ideas from several other course formats, and notably includes code copied from:

* Onetopic format by David Herney Bernal García (including code for displaying tabs, disabling asychronous editing, and managing settings)
* Periods format by Marina Glancy (code for managing settings)
