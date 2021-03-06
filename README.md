## News

 - September 2013: Solarized color theme [added](https://github.com/chmllr/NoteHub/pull/4) (thanks Brandon!) ([Demo](http://notehub.org/2012/6/16/how-notehub-is-built?theme=solarized))

## About

[NoteHub](http://notehub.org) is a free and hassle-free anonymous hosting for markdown pages. It can be used for publishing of markdown-formatted texts.

NoteHub was an one-app-one-language [experiment](http://notehub.org/2012/6/16/how-notehub-is-built) and is implemented entirely in [Clojure](http://clojure.org) (ClojureScript).
The [source code](https://github.com/chmllr/NoteHub) can be found on GitHub.
NoteHub's persistence layer is based on the key-value store [redis](http://redis.io).
Currently, NoteHub is hosted for free on [Heroku](http://heroku.com).
Send your feedback and comments directly to [@gravitydenier](http://twitter.com/gravitydenier) or open an [issue](https://github.com/gravitydenier/NoteHub/issues) on GitHub.

## Why?
Not every person, who occasionally wants to express some thoughts, needs a blog.
Blogs are __tedious__ for writers and for readers.
As readers we are not interested in every thought of other random people.
As writers, we know, that everything rotates nowadays around social networks and not individual blogs.
It's easier to publish something somewhere and to share the link with the audience on the community or social network of choice, than to maintain a blog trying to keep the readers interested.

__NoteHub__ should be the place, where you can publish your thoughts without hassle.

## How to Use?
First, create [a new page](http://notehub.org/new) using the [Markdown syntax](http://daringfireball.net/projects/markdown/).
When the note is published, you'll see a subtle panel at the bottom of the screen.
From this panel you can go to a rudimentary statistics of the article, or you can export the original markdown, or copy the short url of the note.
Besides this, you also can invert the color scheme by appending to the note url ([example](http://notehub.org/2012/6/16/how-notehub-is-built?theme=dark)):
    
    notehub.org/.../title?theme=dark
    
The same way you can specify a [Google Web Font](http://www.google.com/webfonts/) for headers by appending to the note url:

    notehub.org/.../title?header-font=FONT-NAME
    
and for the text itself:

    notehub.org/.../title?header-font=FONT-NAME&text-font=FONT-NAME2

See an example of the font formatting [here](http://notehub.org/2012/6/16/how-notehub-is-built?header-font=Berkshire+Swash&text-font=Swanky+and+Moo+Moo).

After you've specified this in the url, you can copy the corresponding short url of the article and share it.

## After Publishing

During the note publishing a password can be set.
This password unlocks the note for editing.
The edit mode can be entered by appending of `/edit`to the note url.
By appending of `/stats` to any note url, everyone can see a rudimentary statistics (currently, the number of note views only).
By appending of `/export`, the original markdown content will be displayed in plain text format.
