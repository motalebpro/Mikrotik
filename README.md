# MikroTik Hotspot: Randomized MAC Address Detection & Warning

This solution helps MikroTik Hotspot administrators identify devices using Randomized MAC Addresses and prompt users to disable this feature for improved network experience and accurate user tracking.

## * Create the Warning Page

* Create a new HTML file (warning.html) to explain the issue and provide instructions for users.

```bash
Download warning.html page with image.
```
## Modify the Hotspot Login Page (login.html)
* Edit your existing login.html file. Add a JavaScript snippet that:

* If detected Randomized MAC, redirects the user to warning.html page

## Upload Files to MikroTik
* Upload both the modified login.html and the new warning.html to your MikroTik router's hotspot directory (Files > hotspot>YourTheme).
