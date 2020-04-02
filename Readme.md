# Synology API HTTP request file

>  A collection of requests to a Synology NAS. 
>  Use this file directly in PHP-Storm editor to call the Synology API for testing purposes.

# Synology API coverage
Since this is a WIP, the list isn't very long. I'll keep you updated on the latest developments when they are done.

# Global API's
### INFO
Get a list of all available API's of your NAS. Response contains API name, API method, API path,and API version, and so on.

### AUTHENTICATION
Login (for further calls) and logout actions.

# Calendar API
### Create a new calendar
Creates a new calendar with given parameters. The request automatically uses the credentials from previous call.

### Create event in calendar
Creates a new event in previously created calendar.

...

TBC
...

# Help and Doc's
[Synology Calendar API guide][df1]

[df1]: <https://global.download.synology.com/download/Document/Software/DeveloperGuide/Package/Calendar/2.4/enu/Synology_Calendar_API_Guide_enu.pdf>
