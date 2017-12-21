_Note: Redmat is no longer being maintained and may no longer be 100% compatible with the current Reddit._

# redmat #
Google's Material Design for Reddit. [View the demo](http://reddit.com/r/redmat) for
markup required to style the sidebar.


### Installation ###
1. Click on [redmat.css](https://raw.githubusercontent.com/leb2/redmat/master/redmat.css) and paste the code into your subreddit's stylesheet.
2. Upload the spritesheet in the images folder (but not the icons!) and hit save.


### Custom Build ###
If you know how to use the command line and want to build your own version of redmat, the modifiable variables are in `sass/_variables.scss`.

1. Clone the project.
2. Install [Node](https://nodejs.org/en/) and run `npm install` in the project's base directory.
3. Install gulp with `npm install --global gulp`.
4. Edit `sass/_variables.scss` or any of the other sass files and run `gulp build` to produce the output css file.
5. Copy and paste the css from redmat.css into your subreddit's stylesheet and upload the images.
