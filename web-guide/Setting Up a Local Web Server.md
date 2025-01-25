Title:  Setting Up a Local Web Server

Seq:    6.2

Level:  3

Class:  detail

Body:

Even though macOS no longer offers a convenient "Web Sharing" option, you can still implement web sharing on your Mac.

The exact instructions for doing so vary a bit for each major release of macOS. 

Here's the [link to the instructions for Sequoia](https://discussions.apple.com/docs/DOC-250008906).  

Note that I personally use BBEdit to make the necessary configuration edits, rather than a Unix app such as vi or nano. 

And it's helpful to remember the keyboard shortcut for showing hidden folders and files on your Mac: __shift+command+period__.

All of these configuration changes to enable Apache will typically need to be reapplied once a year, for each major new upgrade to macOS. 

Once you have successfully made these configuration changes, you will then be able to access your local website(s) with Safari (or another web browser) using the [localhost](https://en.wikipedia.org/wiki/Localhost) address.

For example, here's the URL displayed when I access my local copy of the Notenik.app website:

```
http://localhost/~hbowie/notenik-web/
```
