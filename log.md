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

### Day 6: July 23, 2017

**Today's Progress:**: Continuing to test prettier-install using sinon stubs.

**Thoughts:** I should read a book on programming patterns.

### Day 7: July 24, 2017

**Today's Progress:**: Introduced unit tests to prettier-install.

**Thoughts:** I should read a book on programming patterns.

### Day 8: July 25, 2017

**Today's Progress:**: Finished with backbone for the new prettier-install.

**Thoughts:** Still working not as fast as I would have liked. I should plan ahead more.

### Day 9: July 26, 2017

**Today's Progress:**: Manually tested prettier install, introduced feedback and rudimentary CLI options.

**Thoughts:** Planning ahead is great. I had a sense that I was fighting against a clock, which prevented me from being distracted with incidental problems. Split my goal for today in 3 parts, two of which I underestimated.

### Day 10: July 27, 2017

**Today's Progress:**: Changed feature tests in prettier install to make it possible to simulate failures.

**Thoughts:** Cucumber testing has its uses.

### Day 11: July 28, 2017

**Today's Progress**: Prettier-install, prettier options.

**Thoughts:** I'm probably spending way too much time on tests. But it's not trivial to test manually. And I design decisions forced on me will probably allow me to deliver something to show for the time spent.

**Link(s) to work:**
1. [NPMCompare.com - Comparing commander vs. minimist vs. nomnom vs. optimist vs. yargs](https://npmcompare.com/compare/commander,minimist,nomnom,optimist,yargs)

### Day 12: July 29, 2017

**Today's Progress**: Released prettier-install. Finished some critical functionality and put together a README.

**Thoughts:**
 * Currently requires git tree to be clean. This might cause problems to people who invoke `prettier-install` repeatedly to achieve the results they want. Need to add an option to bypass this check.
 * ESLint and Lint-Staged integrations will be very useful.

**Link(s) to work:**
1. [prettier-install on NPM](https://www.npmjs.com/package/prettier-install)
2. [GitHub Repo](https://github.com/mpontus/prettier-install)

### Day 13: July 30, 2017

**Today's Progress**: Prototyped active-tab-in-front extension for chrome.

**Thoughts:**
 * Preparing the release will probably take another day.
 * Should make similar extensions for Firefox and VSCode and consolidate 4 packages into a monorepo.

**Link(s) to work:**

1. [GitHub Repo](https://github.com/mpontus/chrome-active-tab-in-front)

### Day 14: July 30, 2017

**Today's Progress**: Implemented prompting support in feedback class

**Thoughts:** Should update this log daily

**Link(s) to work:**

1. [TTY | Node.js v8.2.1 Documentation](https://nodejs.org/api/tty.html)
2. [Stream | Node.js v8.2.1 Documentation](https://nodejs.org/api/stream.html)

### Day 15: August 1, 2017

**Today's Progress**: Introducing new feedback mechanics to cucumber test

**Thoughts:** Spent majority of the time learning to implement custom stream class for mocks.

### Day 16: August 2, 2017

**Today's Progress**: Added an ability to prettier install to bypass clean working tree verification.

**Thoughts:** Feedback is still ugly.

**Link(s) to work:**

1. [Feature/prompt (#1) · mpontus/prettier-install@1d25743](https://github.com/mpontus/prettier-install/commit/1d257430ae62087a9c75ddb0ab6f4b6792d9c0bb)

### Day 17: August 3, 2017

**Today's Progress**: Laid down some groundwork for automated integration with eslint using prettier-install.

**Thoughts:** Gonna need to handle .js, .json, .yaml, and package.json based configurations.

### Day 18: August 4, 2017

**Today's Progress**: Creating a function to add prettier extras to .eslintrc.js.

**Thoughts:** Manipulating AST is hard.
