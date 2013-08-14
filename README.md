If you want to easily and regularly upvote every post in a Reddit thread, follow the instructions below.

Chrome
======

Creating the "UPVOTE ALL THE THINGS" bookmark icon
--------------------------------------------------

* Open Chrome
* Make sure that you have your Bookmarks Bar showing
* If you don't have a Bookmarks Bar displayed, do the following:
  * Right-click an empty spot in your browser
  * Click "Show Bookmarks Bar"
* Right cick an empty spot in the Bookmarks Bar and click "Add Page..."
* In the "Name:" textbox, type "UPVOTE ALL THE THINGS!" (or something shorter, if you into that whole brevity thing)
* In the "URL:" textbox, type the following:

```
javascript:(function f(){var u=$(".up");if(u.length-1) {setTimeout(f,1000);u[1].onclick()} })()
```
* Click "Save" to save the bookmark

Testing the bookmark
--------------------

* Open the browser to your favorite Reddit page
* Open a post that you want to want to shower with upvotes
* Click the "UPVOTE ALL THE THINGS" Bookmark link
* Applause as you see the comments get automatically upvoted one at a time!

That's it!
