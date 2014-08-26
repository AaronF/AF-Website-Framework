#Sass Skeleton CSS Framework

I created a Sass version of the Skeleton CSS framework ([http://www.getskeleton.com/](http://www.getskeleton.com/)).

##Setup
Watch the stylsheets folder
```
sass --watch stylesheets/style.scss:stylesheets/style.css
```

##Structure
```
stylesheets
+style.scss
+style.css (compiled)
|--skeleton
	+base
	+layout
	+skeleton
	+variables
|--ui
	+header
	+etc
```

All of the main Skeleton CSS files are found in the skeleton folder. You can add your own UI files into the UI folder and import them into the style.scss file found in the main stylesheets folder.
