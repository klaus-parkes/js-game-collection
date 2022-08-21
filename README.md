## js-game-collection
A repo for learning to code simple javascript games.

### Origin Credits

Many of these games originally came from these locations:
  * https://www.ansoriweb.com/2020/03/javascript-game.html
  * https://github.com/CodeExplainedRepo

### Publication Notes

This repository uses GitHub Pages functionality.  The `main` branch should always be published to https://klaus-parkes.github.io/js-game-collection

This URL should be accessible from most internet browsers, but will likely be blocked from places like a school controlled device.

### Editing notes

These are some simplistic instructions for using `git`.  More complex/complete instructions are available widely across the internet.

  * Once per machine, you'll need to clone this repo.  To setup SSH keys please work with an adult for now.
    * `git clone git@github.com:klaus-parkes/js-game-collection`
  * Each editing session:
    * Make changes directly on your machine (i.e. edit the files directly)
    * Test changes directly on your machine by opening the `.html` files in a local web browser
      * For more advanced games you might need to run a local web server, but no current game included here requires that.
    * Use `git status` and/or `git diff` to understand what has been changed locally.
    * Stage the changes you want to commit:
      * `git add .` would stage all changes
      * `git add mygame/index.html` would stage only a single file
    * Make the local commit: `git commit -m "A short message explaining what you did"`
    * Push the commit to GitHub (and make it live on the internet): `git push`
