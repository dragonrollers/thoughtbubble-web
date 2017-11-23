# thoughtbubble-web
Website for our product ThoughtBubble

## Team Members
* Grace Hong
* Jenny Kim
* Bonnie Nortz
* Po Tsui

## Development
I develop locally then transfer via SCP.
Setting up:
* You can add this alias to your shell setup (so for me, `vim ~/.bash_profile`) for convenience. Type this into the setup file (replace `<>` with your own setup): `alias transfercs147='scp -r <source path>/thoughtbubble-web/{index.html,css,images,files,bootstrap} <sunet id>@myth.stanford.edu:/afs/ir/class/cs147/WWW/projects/education/thoughtbubble`
** *Note: This will need to be updated if any new top-level files/directories are added.*
* After you've saved, you can type `source ~/.bash_profile` once to ensure your shell's been updated (or just open up a new window).

Developing:
* Open the project in your favorite text editor (for me, that's [Brackets](http://brackets.io/); for most others that's [Sublime](https://www.sublimetext.com/)).
* Make changes
* Track your changes with git and push to remote so the rest of us can see :)
* Any time you want to transfer your work to the live website, just type in the alias you made above: `transfercs147`
* You can also log into myth and do magic there. The project lives in `/afs/ir/class/cs147/WWW/projects/education/thoughtbubble`
* View live: https://web.stanford.edu/class/cs147/projects/education/thoughtbubble/
* Yay!
