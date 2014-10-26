#Nudist: Operating Manual

####Table of contents:

1. **FAQ**
2. **Quick Start:** Intro
3. **Quick Start:** Pre-Install
4. **Quick Start:** Theme Installation


##FAQ:

#####Q: How can I get started in the shortest amount of time possible?

A: Only read the Quick Start steps and skim dense material using the TL;DRs

#####Q: What is a TL;DR?

A: TL;DR stands for "too long, didn't read". It makes skimming easier if you just want the surface information first.

#####Q: Who is this theme for?

A: Anyone who plans to put any content, media, or products on their website. Especially if you want people who aren't programmers to be able to add their own posts– employees or users. Something like a blog, an commerce store, or even a social media website that enables users to post their own content.


#####Q: Who is this theme *not* for?

A: If you have millions of dollars to build something like Facebook or Twitter, you'll probably want to build something custom. But that's not to say that Wordpress isn't capable of Facebook or Twitter's basic functionality.


#####Q: What if I don't know anything about Wordpress, PHP, CSS, LESS, Javascript, or HTML?

A: You'll do fine. All you need to know is that they're like a happy family. PHP is Wordpress's divorced mother. CSS and HTML are Wordpress's cool aunt and uncle, and LESS and Javascript are their kids– Wordpress's badass cousins.

Wordpress has been on some really bad family vacations in his life, but Nudist is like going on a family cruise with all the coolest relatives. The divorced mother might be a little bit of a mess, but luckily she remarried a wealthy man name MySQL. This enabled her to pay for the cruise, so you damn well better put up with her. Mother PHP has a handful of other children, but she only invited Wordpress because he's her favorite child.


##Quick Start- Intro:

This quick start will get you up and running with no previous experience required.


This book isn't necessarily intended to be read all the way through. You don't need mastery to get use out of this theme, you can pick up the pieces as we go along. I personally like getting my hands dirty as soon as possible, and then along the way I usually end up realizing the context of why I should learn more. You're welcome to choose your own adventure.

### TL;DR: Don't feel guilty skimming through the book's TL;DRs. That's what they're here for.



###Online Resources:

Nudist is built to be timeless which is why we've built a static operating manual for it, but that doesn't mean we don't want to take advantage of the fluidity of the web. All of our documents and video tutorials will be updated when needed. (Would be cool to build a diff generator to show them what's been updated since it's been printed).

**[Diff Generator:](http://www.jackalope.io/updates/)** http://www.jackalope.io/updates/

*Select your theme and which version of your manual you own, and the diff generator will automatically show you what's changed since your book was printed. *

**[Documents:](http://www.jackalope.io/docs/)** http://www.jackalope.io/docs/

*Online versions of our books that are updated often.*

**[Tutorials:](http://www.jackalope.io/tutorials/)** http://www.jackalope.io/tutorials/

*Online video tutorials that go along with this book.*

**[Blog:](http://www.jackalope.io/blog/)** http://www.jackalope.io/blog/

*Our blog gives you marketing and growth hacking strategies for once you have your website created.*

**[Podcast:](http://www.jackalope.io/podcast/)** http://www.jackalope.io/podcast/

*On our podcast, we bring on some of the creators and users of the technology behind our themes to give us and our customers a better understanding of how everything ties together.*

**[Services:](http://www.jackalopemedia.com/)** http://www.jackalopemedia.com/

*Need design services? We do a lot of designs for companies looking to have their websites professionally designed.*

##Quick Start: Pre-Install

###Tools Needed: [Video Walkthru](https://jackalope.io)
* [Github.com Account](https://github.com/)
* Github Desktop App ([Mac](https://mac.github.com/) / [Win](https://windows.github.com/))
* Text editor of choice ([Atom](https://atom.io/) / [Sublime Text](http://www.sublimetext.com/3) / [Coda](http://panic.com/coda/))
* Terminal/Command Prompt
* [MAMP](http://www.mamp.info/en/) / [WAMP](http://www.wampserver.com/en/)
* [Node.js](http://nodejs.org/)
* [Grunt.js](http://gruntjs.com/)

###Before You Install: [Video Walkthru](https://jackalope.io)
1. Install Wordpress Locally
2. Install Node and Grunt
3. Setup Github

####1. Install Wordpress Locally:

1. Install MAMP
2. Launch MAMP, Start Servers
3. [Download Wordpress](https://wordpress.org/), unzip it, and rename it as your website
4. Drop folder in ../MAMP/ht-docs/
5. Open MAMP's start page, click on tools>phpMyAdmin, then click the Databases tab
6. Create a DB name and click 'create'
7. Go to http://localhost:8888/ and click on your project folder
8. Click 'Let's go!', fill in database name
9. username: root, password: root
10. Run install, create admin account, and login

####2. Install Grunt:

1. Go to: http://nodejs.org/
2. Download and install node.js
3. Open Terminal
4. Run: ```npm install -g grunt-cli
```(*If you get an error, try ```sudo npm install -g grunt-cli``` )

####3. Setup Github

1. If you don't have a Github, go to http://github.com/ and setup an account
2. Go to https://mac.github.com/, download the desktop app, then install it
3. Once it's opened, login and link it to your Github account


## Quick Start: Theme Installation: [Video Walkthru](https://jackalope.io)

1. [Download theme on Github](https://github.com/masoninthesis/nudist)
2. Unzip it, rename it, then drop in ..MAMP/ht-docs/*SiteName*/wp-content/themes/
3. Drag and drop into Github (desktop app) sidebar. Commit and publish.
4. Right click on new repo and select 'open in Terminal'.
5. Run ```npm install```
6. Run ```grunt build```
7. Activate theme in Wordpress Dashboard > Appearance > Themes













