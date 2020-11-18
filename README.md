# googolplex
launch a google.com search result from the command line in any web browser

### Usage
(requires the command line) Linux or BSD?    
`$ google keyword1 keyword2`    
or    
`$ google '"required keywords"' keyword2` 

This script launches the browser in the background, with the browser specified in the `BROWSER` environment variable.  It should give an error if no arguments.

Should handle characters like `" +="` properly.    
The main purpose of the script is convenience.  It should allow the user to search for any search term in google.com.   Other scripts don't quite handle spaces or quotes correctly. :) 

The rxft script is included for launching terminal browsers.  It should work with kitty or rxvt, it's a work in progress. 
