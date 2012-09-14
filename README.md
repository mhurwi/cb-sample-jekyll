## Cloned from [Jekyll Bootstrap](http://jekyllbootstrap.com/)

## Version

0.2.13 - stable and versioned using [semantic versioning](http://semver.org/).



###Theme layouts are in ./_includes/themes/twitter
(switching themes will overwrite files in ./_layouts)

###Order of how layouts are applied:
default.html (main layout, with CSS and JS links, body, etc) -->  
Page/Post/Custom (layout specified in ./file.md YAML front matter)-->  
./file.md (actual content)

Add template to _layouts to customize blog

Static assets name-spaced for theme in ./assets/themes/twitter


Base Jekyll App
===============
_config.yml
Stores configuration data.

_includes
This folder is for partial views.

_layouts 
This folder is for the main templates your content will be inserted into. You can have different layouts for different pages or page sections.

_posts
This folder contains your dynamic content/posts. the naming format is required to be @YEAR-MONTH-DATE-title.MARKUP@.

_site
This is where the generated site will be placed once Jekyll is done transforming it.

assets
This folder is not part of the standard jekyll structure. The assets folder represents any generic folder you happen to create in your root directory. Directories and files not properly formatted for jekyll will be left untouched for you to serve normally.

index.html and Other HTML/Markdown/Textile Files
Provided that the file has a YAML Front Matter section, it will be transformed by Jekyll. The same will happen for any .html, .markdown, .md, or .textile file in your site's root directory or directories not listed above.

Other Files/Folders
Every other directory and file except for those listed above will be transferred over as expected. For example, you could have a css folder, a favicon.ico, etc, etc. There's plenty of sites already using Jekyll if you're curious as to how they're laid out.

Any files in these directories will be parsed and transformed, according to the same rules mentioned previously for files in the root directory