# opendigerati-theme
The wordpress child theme for OpenDigerati.com 

The Open Digerati site child theme is a fork of the wonderful Understap theme https://github.com/holger1411/understrap - specifically the BASE - Child Theme.

Our current implementation is pure CSS, though we may utilize SCSS and gulp compiling goodness in the future.

This theme is dependent on the following plugins:
- ACF - https://www.advancedcustomfields.com/
- Custom Post Type UI - https://github.com/WebDevStudios/custom-post-type-ui/
- Our forked version of "Display Medium Posts" (included in this repo) - we replaced some of the formatting to output bootstrap cards vs the owl carousel formatting.

This theme includes some custom functions:
- The ability to grab Github info based on the repo url (in the single project template)
