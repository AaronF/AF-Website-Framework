#Website Framework 1.0

This is my website framework that I base most of my new projects from, it includes pretty much everything I need to get starte. Some of the CSS is based from Inuit, Bootstrap and Skeleton CSS.

##Setup
Watch the stylsheets folder
```
sass --watch stylesheets/style.scss:stylesheets/style.css
```

##Structure
```
bower_components
+jquery
stylesheets
+style.scss
+style.css (compiled)
|--skeleton
	+base
	+layout
	+skeleton
	+variables
	+mixins
	+elements
|--ui
	+header
	+etc
```

All of the main Skeleton CSS files are found in the skeleton folder. You can add your own UI files into the UI folder and import them into the style.scss file found in the main stylesheets folder.
