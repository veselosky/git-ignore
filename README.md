# git-ignore
A convenience command to edit a .gitignore file.

I created this because I have literally typed this command a dozen times, and
then remembered, oh yeah, I have to edit the .gitignore file, there's not a
built-in command for that.

# How does it work?

Drop the `git-ignore` file in your path. Then you can:

  git ignore junk.txt

This will add "junk.txt" to your project's .gitignore.

# Opportunities for improvement

There are tons! Because I literally just threw this together while multi-tasking
in a meeting. Suggested improvements:

* [ ] Add a USAGE statement
* [ ] Add a useful error message if no argument is given
* [ ] Prevent adding duplicate lines to the .gitignore file
* [ ] Support deleting entries from .gitignore using -d
