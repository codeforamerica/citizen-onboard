# Citizen Onboard
Citizen onboard is a collaborative project to document and describe how our own government services work (and don't work). It's all hosted on Github pages: http://lippytak.github.io/citizen-onboard/. Inspired by the endlessly awesome [@UserOnboard](http://www.twitter.com/useronboard).

If you have an idea for a government service to look at, just [open an issue](https://github.com/lippytak/citizen-onboard/issues) and include a bit of preliminary research. If you're feeling ambitious, take some screenshots and throw them in a public dropbox folder for everyone to peruse. If you want to do a new one from scratch, then you are awesome and should take a look at the [contribute](#contribute) section below. If you do one, I'll send you a present (no joke!).

Questions? Get in touch [@lippytak](http://twitter.com/lippytak)!

# Contribute
1. [Install Node and NPM](https://gist.github.com/isaacs/579814#file-node-and-npm-in-30-seconds-sh)
2. Install [Cleaver](https://github.com/jdan/cleaver/): `npm install -g cleaver` (Cleaver generates slideshows from markdown)
3. [Fork this repo](fork) and create a new branch for your service
4. Rename the `sample` directory and `sample.md` file to the name of your service
5. Now for the fun part: Go take a bunch of screenshots/pictures/whatever else you can imagine to document the process of using/enrolling in the service. Be exhaustive. Be creative. Use whatever tools are at your disposal. So far I've had a good experience with:
    - [Awesome screenshot](https://chrome.google.com/webstore/detail/awesome-screenshot-captur/alelhddbbhepgpmgidjdcjakblofbmce?hl=en) for full page screenshots,
    - and [Skitch](http://evernote.com/skitch/) for annotations.
6. Edit the markdown (`.md`) slideshow. Just add an intro slide, lots of image slides, and a stats/author slide at the end. It should be pretty self-explanatory but feel free to [reach out](http://www.twitter.com/lippytak) with questions.
7. Run `cleaver servicename.md` to generate the slideshow as `index.html` in the same directory.
8. Ådd a link to your new service in the root `index.md` and run `cleaver index.md` to update the index page.
9. And you're done! Open `servicename/index.html` in any browser. Once everything looks right, send a pull request!