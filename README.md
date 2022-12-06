# awesome-boox

A list of awesome 🤞 resources for users of the Onyx Boox family of e-ink digital notebooks and ereaders (similar to other e-ink devices like Amazon Kindle, Kobo, Supernote, Remarkable 2, each with their own nuances and conventions)

Onyx produces a range of tablet devices with [e-ink](https://www.eink.com/) displays. Users of these devices use them for many activities other tablet devices and computers can do, but generally they are purchased and used as a reader for ebooks, and for hand-written, typed, or voice notes. These e-ink tablets are built to provide a digital experience that is more like using a paper notebook or tree-pulp-book than an iPad or Kindle Fire. I'm starting to feel like I'm trying to convince you that they're awesome instead of the awesome things you can do, so if it needs more explanation, we can go all `-vvv` on it.

There are many options for e-ink tablet devices but one thing that influenced many purchasers is that the Boox runs Android, not necessarily the Android we'd want, but it's the Android we've got. There are compute and display limitations that.

## todo

- [ ] I have to adopt a code of conduct for this project and documentation to make it really clear that contributors and users should be treated with respect. #todo #writing #code-of-conduct #awesome-boox

We're all in this together so I don't think this will be a problem for anyone. This will be prioritized if I start getting PRs or otherwise end up collaborating with other people that don't understand the expectations to keep this documentation relevant and free of tumbleweeds.

## Organization of this document

I don't know yet, maybe starting by use-case.

## Transfering Files, Books, Notes, Annotations

Calibre can attach itself to a Boox and manage books on the device. 

Boox has a slick service called Boox Drop, that opens an http listener with a simple UI for browser-based drag and drop navigation. Recent versions of the Boox Android distribution have included a background service for 'drop (does impact battery) and the old fashioned way of using Android File Transfer tools from the Android SDK or similar can work as well. 

On macOS at least, you may want to take care to not allow Android File Transfer intercept the device when you plug it in or Calibre can't see it. I disabled the launchdaemon and launchagents associated with the SDK to stop it from constantly butting in when I was trying to copy more books over.

### Reading: Books, documents, web

The Boox ereaders are excellent book readers and support epub and PDF well through the built-in software, Neoreader. The device runs Android though, so you can install other reader software or the Kindle app for example on your Boox. You probably want to enable Google Play Store on your device to browse and explore what the broader Android community has made available.

Optimizing for eink displays and slow refresh rates and monochrome views is a whole topic of its own, the device has some accomodations it can do that attempt to make some software less clumsy or more legible. e.g. OneNote runs on a Boox but there's an awful lot of black pixels to draw over and over again. 

There are some benefits to Neoreader though, including easy access to highlights, annotations and side-by-side freehand notes or thoughts split screen in a Notebook you've created for a project.

#### Neoreader

Neoreader is Boox's built-in default ebook reader. It can also read other formats like PDF, and is able to use hyperlinked digital planners. 

### Capture: Notetaking and handwriting

These aren't just ereaders, they're digital notebooks. Or, they can be if you wish. The built-in Notebook app is quite good for creating notebooks of all kinds, and it's easy to create a notebook and make every page follow a template as stationary like (my favorite) dot-grid backgrounds that will apply to every new page you create in a notebook.

Your Boox can even do a pretty good job of turning your handwriting into text, or speech recognition like the dictate feature on an iPhone, iPad, or Android device. 

#### Boox Notebooks & Templates

- How to use templates in notebooks
- Getting notes out of the Boox

#### Creating or getting free templates for notebooks

- [PaperKit](http://paperkit.net/) starts with grid layouts, but has a great widget to create templates like [dotgrid](http://paperkit.net/dottedpaper) (best-in-slot imo) and [ruled](http://paperkit.net/linedpaper)
  - The color options aren't irrelevant — the e-ink display of my Note Air 2 doesn't show colors but they're still there and the PDF sync output that ends up in my Dropbox account are all in living color. [^color-eink-wishlist] 
  - Jason Blevins has published a [post](https://jblevins.org/log/dot-grid-paper) with pointers to a [dot-grid-paper GitHub repository](https://github.com/jrblevin/dot-grid-paper) and while at the time of that post he was using GoodNotes, any software that allows you to set a background image or template of notebooks can use these sorts of templates and in the case of Mr. Blevins 

### Other apps 

You may want to enable the Google Play Store on your Boox to install other software like Raindrop, OneNote, Obsidian, and other ebook readers users prefer. 

Boox has documentation on [permitting Google Play Store](https://help.boox.com/hc/en-us/articles/8569260963732-Google-Play-Store) and you should probably familiarize yourself with the optimization and performance/display improvements for third-party apps like this [guide for optimizing OneNote, Evernote, WPS](https://shop.boox.com/blogs/news/optimize-onenote-evernote-wps).


#### Alternative ebook (epub, mobi, pdf, az3) readers and annotators

- 
#### Stylus

The eink displays try to recreate familiar concepts and use electromagnetic resonanace (EMR) technology, and it's a patented technology by Wacom, which is obviously the most well-known name in graphics tablets used by creative professionals for decades. They use EMR styluses, so the e-ink displays Boox uses also can use an EMR stylus, and Boox makes and sells a few but some fan favorites worth looking at would include:

- [LAMY EMR technology](https://www.lamy.com/en/emr/) for the fans of LAMY pens for pen-and-paper feel, erasing with a button hold
- [Noris digital](https://www.staedtler.com/intl/en/discover/noris-digital/#) for a pencil-and-paper feel on the digital jumbo, erasing with the other end (!)
- [Supernote's metal series](https://goodereader.com/blog/product/supernote-heart-of-metal-series) has a ceramic nib and while the pen probably feels amazing in the hand it may damage the surface of a Boox (confirmation requested)


## Templates and Digital Planners 


### Free Templates and Planners

dotgrid or gtfo

### Paid Templates and Planners


### Communities and discussions 

- the Boox subreddit [/r/Onyx_Boox](https://www.reddit.com/r/Onyx_Boox/)
  - there are some others, [/r/remarkableTablet](https://www.reddit.com/r/RemarkableTablet/), [/r/eink/](https://www.reddit.com/r/eink/)
- [mobileread Boox forum](https://www.mobileread.com/forums/forumdisplay.php?s=b513430272605ce79aac2790c5a1f1d9&f=220) is usually lively, their forum for Kobo devices is good too if you have have a Kobo (they have custom firmware guides for Kobo readers like the Aura HD)
- [Boox forum at ePaper Hub](https://community.epaperhub.com/c/onyx-boox/5) is tumbleweeds, but may have some inspiration for you
- 
- 

***
initial commits and organization by [emory](https://incumbent.org/), you may contact me via email, [Apple Messages](messages://emory@hellyeah.com) (that should work on Apple devices?), [keybase](https://keybase.io/emory) and for now twitter and facebook `@incumbent` but i'm also on mastodon at [@emory@soc.kvet.ch](https://soc.kvet.ch/@emory) 

### footnotes

[^color-eink-wishlist]: Someday an A5/A6 sized color eink display with fast enough refresh to not hobble the usefulness of the device will be available and I can't wait. //@emory