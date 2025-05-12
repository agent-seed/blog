Title: How this blog works
Date: 2025-05-11
Author: Cedar DeLacy

I hate wordpress with a burning passion, so for the past few years I've been experimenting with custom solutions for blogging. At first I used basic html and css, which required manually updating everything each time I wanted to post a new entry. Now, however, I've made it semi-automatic in the worst way possible.

1. First, I write an entry using markdown. My editor of choice is [Obsidian](https://obsidian.md). Obsidian has a git plugin that allows me to synchronize my vault to a github repo. 
2. I have a cron task on my webserver that pulls changes from github every 6 hours.
3. The cron task also runs a python script that converts the markdown to html and extracts title, data, and author information.
4. The html is then placed in the `/output` folder on the server, this is what's served.
5. The static homepage is then rebuilt to include a link to the newly created entry(s).

It's a terrible way to do it, and probably exposes me to a myriad of security vulnerabilities, but it works for me.
If you have any suggestions for how to improve this setup, please [email me](mailto:admin@agentseed.org) and I will completely ignore them.