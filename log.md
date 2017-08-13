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

### Day 19: August 5, 2017

**Today's Progress**: Continuing to manipulate AST using esprima and ramda.

**Thoughts:** Functional programming is hard.

### Day 20: August 6, 2017

**Today's Progress**: Working on AST's again.

**Thoughts:** I need to spend a full day worth of work on this to make any progress.

### Day 21: August 7, 2017

**Today's Progress**: More AST work.

**Thoughts:** I need to spend a full day worth of work on this to make any progress.

### Day 22: August 8, 2017

**Today's Progress**: Finished with AST processing using Ramda. 

**Thoughts:** To be honest it's hardly finished until we handle edge cases. Right now I'm not even sure what would happen. I'm going to delay the merge until I can test the functionality in real environment in a reproducible manner.

**Link(s) to work:**

1. [Finished with AST processing. · mpontus/prettier-install@cc8d7a3](https://github.com/mpontus/prettier-install/commit/cc8d7a3caf018267b5c83f6d98bf4c1bc4f534ea)

### Day 23: August 9, 2017

**Today's Progress**: Working on yaml processing for installing prettier extras into .eslintrc.

**Thoughts:** There is a couple of issues which are begging to slow me down:

1. Client's responsibility is unclear. It was introduced as an injectible dependecy to allow mocking real system in functional tests. It's responsiblities should be limited to disk I/O and command execution.
2. Should look into modularity some more. Eslint integration asks to be made a module. But how far do the modules go? What would be considered the core functionality?
3. I need to find a way to test the executable for real in a reproducible environment. There was no good sandboxing solution for NodeJS last time I looked. It would probably require entirely different testing framework, something like introducing Selenium testing into frontend project.

### Day 24: August 10, 2017

**Today's Progress**: Injecting eslint extras is almost working. 

**Thoughts:** Cucumber tests seem almost pointless. I need to find a way to run the binary in a reproducible environment.

**Link(s) to work:**

1. [Injecting eslint extras should now work for json, yaml, and js. · mpontus/prettier-install@1983a54](https://github.com/mpontus/prettier-install/commit/1983a54a7c66cae2dae157f15928e077336a4ee7)

### Day 25: August 11, 2017

**Today's Progress**: More work on eslint integration.

**Thoughts:** Apparently i missed a lot.

### Day 26: August 12, 2017

**Today's Progress**: Fixed eslint injection for objects, ASTs to go.

**Thoughts:**

1. There should be some interface to allow for modifications using 3 adapters: json, js, yaml.
2. Docker seems fine for automatic manual tests. As long as hitting real npm registry is acceptable.
3. I'm not positive about how eslint works. Should verify the order in which config files are searched, whether adding plugin without config resolves conflicts, and if prettier plugin makes `eslint --fix` is enough to replace prettier command.

### Day 27: August 13, 2017

**Today's Progress**: Eslint integration should be working now. Going to perform manual test before merging.
