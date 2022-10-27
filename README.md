# googolplex
launch a google.com search result from the command line in any web browser

### Usage
(requires the command line) Linux or BSD?    
`$ google keyword1 keyword2`    
or    
`$ google '"required keywords"' keyword2` 

This script launches the browser in the background, with the browser specified in the `BROWSER` environment variable.  It should give an error if no arguments.  `xdg-open` is used if no $BROWSSER environmental variable.

Should handle characters like `" +="` properly.    
The main purpose of the script is convenience.  It should allow the user to search for any search term in google.com.   Other scripts don't quite handle spaces or quotes correctly. :) 

`-l` adds the classic feature of duck duck go: "I'm feeling lucky" which is an instant redirect to the first search result.    
e.g. `$ google -l kanliot 8mbwebm`

`-e` adds the ability to open duckduckgo "lite" results in elinks, which is fast and useful.  The current terminal should be used.

The rxft script is included for launching terminal browsers.  It should work with kitty or rxvt, it's a work in progress. 
