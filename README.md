# Remove Cookie

**Custom Tag Template for Server-Side Google Tag Manager**

Delete a cookie by name, path and domain via server response.

![Template Status](https://img.shields.io/badge/Community%20Template%20Gallery%20Status-submitted-orange) ![Repo Size](https://img.shields.io/github/repo-size/mbaersch/cookie-killer) ![License](https://img.shields.io/github/license/mbaersch/cookie-killer)

the template that should not be neccessary: delete cookies in the ssGTM response. Example use case: delete id cookies if consent was changed and a service got deactivated.

## Usage 
Add a tag and enter a cookie name (and optional domain and path). Trigger if a cookie is present in the request and consent indicates that it should not exist to delete the cookie with the response.
