# randomrandom - a meta-random homepage

Your **New Tab** page isn't random enough. Let's make it more _inspirational_.

See, John Herrman made [this fantastic list of randomisers](http://www.theawl.com/2015/04/how-to-make-the-internet-seem-fun-again): you set your New Tab URL to one of the URLs from the list, and each time you spawn a new blank tab you'll see a random Wikipedia page, or street view, or huge GIF - whatever you choose.

But what if _you don't want to choose?_ Then you set your New Tab Page to `http://cdn.rawgit.com/yozlet/randomrandom/master/randomrandom.html`, and a randomiser will be picked from this list:

* [Wikipedia article](http://en.wikipedia.org/wiki/Special:Random)
* [WolframAlpha query](https://www.wolframalpha.com/input/random.jsp)
* [Fullscreen GIF](http://gifff.in/fullscreen/)
* [Ask MetaFilter](http://ask.metafilter.com/random)
* [Actor](http://www.imdb.com/random/name)
* [Website](http://www.randomwebsite.com/cgi-bin/random.pl)
* [WikiHow](http://www.wikihow.com/Special:Randomizer)
* [Urban Dictionary](http://www.urbandictionary.com/random.php)
* [Wikipedia GIF](http://www.wikigifs.org/)
* [Street View](http://randomstreetview.com/)
* [Esperanto Wikipedia article](http://eo.wikipedia.org/wiki/Speciala%C4%B5o:Hazarda_pa%C4%9Do)
* [Yahoo! Answers: Newest questions](https://answers.yahoo.com/answer) (this is not technically a randomiser, but serves the same purposes)

_(NOTE: I omitted the [random subreddit link](http://www.reddit.com/r/random) because I just couldn't face it. Feel free to fork and reinstate, but you do so at the risk to your own placidity.)_

## How to use this in your browser

In these instructions I suggest you point to the copy hosted on Github using this URL...
```
http://cdn.rawgit.com/yozlet/randomrandom/master/randomrandom.html
```
... but if you care about speed (and who doesn't?) it's faster to save a copy of the file locally (or clone this git repository) and use a file URL.

Anyway, once you have a URL:

### Chrome

You have to install the [New Tab Redirect extension](https://chrome.google.com/webstore/detail/new-tab-redirect/icpgjfneehieebagbmdbhnlpiopdcmna). (Yes, an extension is required. No, there's no easy way of doing this in Chrome by itself. Yes, that's odd.)

### Firefox

You have to install the [New Tab Homepage extension](https://addons.mozilla.org/en-US/firefox/addon/new-tab-homepage/). (Yes, just like Chrome. I know.)

### Internet Explorer

The easiest way is:
* set the URL as your homepage in **Tools -> Internet Options**
* find the **Tabs** settings
* open the **Tabbed Browsing Settings** dialog box
* in the **When a new tab is opened, open** list, choose `Your First Home Page`
* click **OK** twice

### Safari

Similar to Internet Explorer (though not entirely):
* Open **Preferences**, go to the **General** tab
* For **New tabs open with**, choose `Homepage`
* In the **Homepage** field, enter the URL
