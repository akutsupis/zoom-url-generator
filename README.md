# zoom-url-generator

[https://akutsupis.github.io/zoom-url-generator/](url)

I could not find an an easy-to-use, functional generator to create Zoom URLs when you have the username and password but not the hashed link. Because hashing the link ourselves would be impossible, we cannot generate the web URL (```https://zoom.us/j/...```) but we can generate the protocol URL that directly triggers the Zoom client to launch a meeting (```zoommtg://```). For many users who just want the convenience of clicking a link and use a Zoom client app, the distinction may not matter at all.

Note: You cannot use this URL to launch a meeting in your browser. You will need a Zoom client installed. 
Be careful whom you share this link to - it contains the username and password in plaintext.
Unfortunately, it does matter whether you use the mobile or desktop URL - in my testing, the mobile ```zoomus://``` url worked on both mobile and desktop, while the desktop ```zoommtg://``` only worked on desktop.
