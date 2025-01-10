# privacy-redirect-ring

Redirects requests to youtube.com and x.com to the appropriate invidious or nitter instance,
then allows the user to cycle through a customizable list of instances to find one that is working.

## Testing instructions

- Clone this git repository
- Go to about:debugging in a Firefox web browser
- Select "This Firefox" and then "Load Temporary Add-on..." under "Temporary Extensions"
- Select manifest.json from this repo
- The extension will run until it is removed or the browser is closed

## To Do:

- DONE - redirect x.com requests to nitter.poast.org
- DONE - redirect youtube.com requests to yewtu.be
- DONE - handle shortened Youtube URLs
- create a list of instances for each and popup with buttons to cycle through them
- allow user to customize lists in the popup
