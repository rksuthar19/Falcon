###Information



- Required: [R](http://cran.rstudio.com/) (v3.1.1)
- Required: [Shiny](http://www.rstudio.com/shiny/) (v0.10.1)
- Required: A modern browser (e.g., Chrome*, Firefox, or Safari). *Recommeded

Unzip the file and then startby running the following code in the R console (change file path if not unzipped to the desktop).

	
	#-------------
 	#Load Directly from GitHub
 	#-------------
 	library(shiny)
 	runGitHub("user/repo")
	
	#-------------
	#Windows
	#-------------
	library(shiny)
	
	#Stable version
	shiny::runApp('~/../Desktop/)
	
	# Development version
	library(shiny)
	shiny::runApp('~/../Desktop/')