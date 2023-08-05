# Spaceteam Lexicons

> A repository for various lexicons for the mobile game [Spaceteam](http://www.sleepingbeastgames.com/spaceteam/).

Current project is creating a custom lexicon for use at Pendo.

## Forked Repository

Attribution for the original idea of a Git repo containing Spaceteam lexicons goes to [Stuart Thomson](https://github.com/s-thom). His [original repository](https://github.com/s-thom/Spaceteam-Lexicons) is now a public archive.

## Adding your own lexicon to the game

You must know your member ID for the Admiral's Club. If you don't have an ID, contact the developer of Spaceteam.

1. Log in to the lexicogulator

   To do this, go to `https://lexicogulator.herokuapp.com/editor/:ID` where `:ID` is your Admiral's Club member ID.

2. Click the New Lexicon button

   This should be a green button on the left side.

3. Copy the contents of each text file (from a directory in this repository) into the appropriate fields in the Lexicogulator.

## Contributing

- Each directory is named after the keyword given to public lexicons in the Lexicogulator. (There is no reason not to make the lexicon public, since the contents of the lexicon are hosted in a public repository.) Click the "make public" checkbox in the Lexicogulator to get the public keyword.

- There are blank files in the `.blank` folder, and the originals are in `.default`. You can also find the defaults on the lexicogulator page itself.

- Follow the standard Github fork/pull-request workflow.

- There is no automation tying the contents of this repository to the Lexicogulator. Don't forget to apply any merged changes to the Lexicogulator page yourself.
