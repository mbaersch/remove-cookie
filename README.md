# cookie-killer
delete cookies by name (Custom Tag Template for Server-Side Google Tag Manager)

the template that should not be neccessary: delete cookies in the ssGTM response. Example use case: delete id cookies if consent was changed and a service got deactivated.

## Usage ##
Add a tag and enter a cookie name (and optional domain). Trigger if a cookie is present in the request and consent indicates that it should not exist (any more).
