# unity webgl builds
## about
* for inclusion as a submodule in the [website repo](https://github.com/corbeau217/corbeau217.github.io)
## notes
* builds can be included in this as submodules
* then we make the template file in here ready for the parent repo
* will need some token strings to be swapped out with the relative path or just hard code it to where we put it
## TO DO
- [ ] include as submodule to main site
- [ ] uncommited copypasta a project's build files to this project to experiment with how it works
- [ ] make rough draft of the project specific index pages that allow the project to be run through the webgl player
- [ ] revisit design plans depending on how it interacts
- [ ] expand on the project player pages
    - [ ] full screen option
    - [ ] focus option
    - [ ] investigate other things that may need to be added
- [ ] add the project build repos as submodules with copies of the template project page
- [ ] add in tokens at `data/tokens.js`
    * use similar layout to the global tokens
## ideas
### structure of builds
* have the folder per project
* in a project's folder there is: 
    - the player stub page
    - the included submodule of the build
