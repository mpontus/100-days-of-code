# 100 Days Of Code - Log

### Day 1: July 17, 2017

**Today's Progress**: Submitted a PR to introduce Docker into development process for the app our study group is developing.

**Thoughts:** Will need revisiting once build process has been put in place.

**Link(s) to work:**
1. [Feature/docker by mpontus · Pull Request #1 · moscow-freecodecamp/fluffy-spoon](https://github.com/mpontus/100-days-of-code/blob/master/rules.md)
2. [Compose file version 3 reference | Docker Documentation](https://docs.docker.com/compose/compose-file/)
3. [library/postgres - Docker Hub](https://hub.docker.com/_/postgres/)
4. [library/node - Docker Hub](https://hub.docker.com/_/node/)

### Day 2: July 18, 2017

**Today's Progress**: Resumed decoupling my external dev server for create-react-app from react-scripts.

**Thoughts:** Not satisfied with how decoupling is going. I should probably try looking less at react-scripts and try to find a better approach, if I want to avoid reliance on their tooling. Automated testing is an interesting thought. Might spend an hour another day trying it out.

**Link(s) to work:**
1. [How Dev Server is bootstrapped by Webpack itself](https://github.com/webpack/webpack-dev-server/blob/master/bin/webpack-dev-server.js)
2. [How React Scripts bootstraps their Dev Server](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/scripts/start.js)

### Day 3: July 19, 2017

**Today's Progress**: Published [Atom](https://atom.io/) package which enables tab rotation mechanism I've been missing.

**Thoughts:** This mechanism has been essential to my web browsing experience, and by this day I haven't been able to apply it anywhere else but [Pentadactyl](https://github.com/5digits/dactyl). Authoring in Atom is nice. I'd love to put out a simliar CLI tool for emacs at some point.

**Link(s) to work:**
1. [Atom Package: Active Tab In Front](https://atom.io/packages/active-tab-in-front)
2. [Building your first Atom plugin](https://github.com/blog/2231-building-your-first-atom-plugin)
3. [Atom API](https://atom.io/docs/api/v1.18.0/AtomEnvironment)

### Day 4: July 20, 2017

**Today's Progress**: Fixed a bug in my Atom package which happens when you rearrange tabs during removal process.

**Thoughts:** setTimeout is probably a hack. You could probably accomplish the same by keeping track of the activeness of the removal process. It's going to be important if those events happen to become asynchronous.

**Link(s) to work:**
1. [Fixed a bug with removing an item · mpontus/atom-active-tab-in-front@ae490a2](https://github.com/mpontus/atom-active-tab-in-front/commit/ae490a2834d23377f476f6d95eb481f514dbdff8)

### Day 5: July 21, 2017

**Today's Progress**: Working on prettier-install. CLI installer for [prettier](https://github.com/prettier/prettier).

**Thoughts:** Command line tools are an interesting subject. Many opportunities for refactoring.

### Day 5: July 22, 2017

**Today's Progress:**: Testing prettier-install with cucumber-js.

**Thoughts:** Not much code was written that day. I learned cucumber, and a bit of node.js process management.
