# chrome-apartheid
Multiple Google Chrome instances under Mac OS X. Seperate dock icons, each associated with a different user profile. "Window" menu shows only windows associated with the instance.

Here is my solution, which gives you multiple instances, a dock launch menu for the instances, and different icons for each instance. When you run the script it'll automatically go through all your profiles, and then tell you what to do next.

For icons, you can use any PNG (or probably many other formats).

The chrome avatars which you may already be used to are located under "~/Library/Application Support/Google/Chrome/Avatars" - avatar_ninja.png etc.

Or make your own, or use one of the numerous icon sites - I like Easyicon.

Also this looks possibly useful - How to Get Back Avatars in Chrome to Switch User Profiles More Easily - to make the open windows easier to quickly identify (untested).

One thing that isn't working yet is the ability to assign different user profile chrome instances to specific desktops. This is because if the attribute used to do this is changed, the browser is no longer able to automatically log in to that profile when the browser starts up. I've made a forum post and bug report on this issue; it is also a problem for site-specific browsers, so the chrome-ssb-osx project may get this working at some point. I don't have the 10 reputation points needed to include more than 2 links in posts here (help! :-), so you'll have to look at the links to these things in the script above ("This section disabled" section).

http://www.easyicon.net/

http://digiwonk.wonderhowto.com/how-to/get-back-avatars-chrome-switch-user-profiles-more-easily-0159605/
