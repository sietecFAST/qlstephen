# NEW Fork!!

sietecFAST™ has forked this repository to continue the excellent work of those working on this project before us.  We make no claims as to the intellectual property (if existing) or ownership of this source code prior to the date and time (2014-16-November @ ~0540GMT or ~ 0040CST) of our fork.  Additionally, we will be keeping this project Open source and will add a BSD or similar EULA sometime soon.

**Original Authors:**  Please see the text below the indicator that says "Unmodified text begin here -->" This signifies that anything under this line is part of the original contents of the repository at the time we forked it and has NOT been modified in any way.  Above this line, we have made changes.

	Entry added:             16 November 2014 @ 0052CST
	Entry author:            zws.SIETEC.sysADMIN
	Entry Revision ID:       1.0.0
	sietecFAST Tracking ID:  0052.16112014.evid_1.0.0-1.zws (internal use only)
	Blame:                   SIETEC

### End modified text by sietecFAST™
### Unmodified text begin here -->

## !! UPDATE !!

Hi all. I'm afriad I don't have time to maintain this project any more. I see the issues mounting but I don't have time to answer them. This was a pet project some time ago and I still use the plugin daily and it works just fine for me in it's current form. If anyone would like to step forward and be added a contributor to move it forward, please send me a message.

Duncan


# QuicklookStephen

QLStephen is a QuickLook plugin that lets you view plain text files without a file extension. Files like:

    README
    INSTALL
    Capfile
    CHANGELOG
    etc...

## Installation


### Pre-compiled

* [Download the latest version of QuickLookStephen](https://github.com/whomwah/qlstephen/releases)
* Unzip
* Copy the file into `/Library/QuickLook` or `~/Library/QuickLook`
  (You can create the `QuickLook` folder if it doesn’t exist)


### Manually Compiled

Compliling the project yourself? Just copy the generated `QLStephen.qlgenerator`
file into the relevant `QuickLook` folder (as above).


## Trouble?

If you’ve installed the plugin, but don’t see any changes:

- Make sure you are editing (a) the correct plist of (b) the correct bundle.
  (For example, you might have two `QLStephen` plugins. It’s possible the plugin in
   another directory—perhaps `/Library/QuickLook/`—is what is being read.)
- Run `qlmanage -r` in the Terminal. (This will restart QuickLook, which reloads all plugins.)


## Why “QLStephen”?

Because I was listening to [Adam and Joe](http://www.bbc.co.uk/blogs/adamandjoe/2009/06/test-1.shtml) when I first wrote it.


## Authors

**Original author:** Duncan Robertson

Special thanks to the following people for submitting patches over the years:

* [Guillermo Ignacio Enriquez Gutierrez](https://github.com/nacho4d)
* [Rob Lourens](https://github.com/roblourens)
* [Avi Flax](https://github.com/aviflax)
* [Tony](https://github.com/Zearin)
* [Nicholas Hutchinson](https://github.com/nickhutchinson)


## Contributing

* Fork the project
* Send a pull request
* Don’t change the build number (I’ll do that when I release a new version)
