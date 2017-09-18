# Hello World

## Overview

We're going to make a file that will print ["Hello World!"](http://en.wikipedia.org/wiki/%22Hello,_World!%22_program) to your terminal.

## Objectives

1. Create a new Ruby file.
2. Write syntactically valid code to produce "Hello World!"
3. Run a Ruby file.
4. Install the `rspec` gem.
5. Run `rspec`.
6. Submit a lab via Pull Request.

## Instructions

Get started by forking and cloning this lab into `00-intro` (don't forget to `cd` into it!). 

### Creating a File

You will need to create a text file called `hello_world.rb` within the lab's directory. The `.rb` file extension is a common convention for specifying the language of the file - in this case, Ruby. To create this, in the terminal type `touch hello_world.rb`. If that worked as expected, you should now see the file appear in the file browser. You can open this file by double clicking on it in the file browser or by typing `c9 hello_world.rb`. You should now see an empty file open in your text editor, ready to be edited. 

### Writing Code

In the file `hello_world.rb` that you created, you need to write a single line of code that prints the string Hello World! to your terminal. To print in Ruby, you need to use the method `puts` which is short for "out**put s**tring." And because Hello World! is a string, you need to surround your text with `""`.

File: `hello_world.rb`
```ruby
puts "Hello World!"
```

Anytime you make changes to a file, such as the one you've just made, you need to save it so these changes are preserved. If you forget to save it before you run your tests, it will be tested against an empty document! Always remember to save it every time you make changes by selecting Save from the File menu.  **In cloud9, auto-save works 99% of the time.  But if your code and/or test isn't working the way you expect, double-check that your file is saved by manually saving it (cmd+s).** As a worst-case-scenario, select & copy the code, close the file, re-open it, and replace (paste) the code back in.

### Executing Your File

Execute this file by typing `ruby hello_world.rb` into your terminal and pressing `enter`. The `ruby` part of that command tells your computer to use the Ruby interpreter when reading and executing the code in your file. The second part of the command, `hello_world.rb` is the path to the file you want to run.

Note: be sure to save your file before trying to print, otherwise it will not work.

You should see:

```bash
$ ruby hello_world.rb
Hello World!
```

### Installing the `rspec` gem

In order to check that we've written our code correctly, we can use a test suite called **rspec**.  To install it, type `gem install rspec` into your terminal.

### Running `rspec`

Confirm everything is working by simply typing `rspec` into your terminal. You should see that all tests are passing (e.g. all green, no red error text). 

Note: When you write code, the case (uppercase/lowercase) of characters matters, and so your test will not pass unless you print "Hello World!" exactly (and include the exclamation mark). 

### Submitting your lab

Remember that only YOU can see that your tests passed when you ran `rspec`.  But there is a way to submit your code to Mr. Mueller:

For many (but not all) labs, you will be asked to submit via a Pull Request.  As long as you got the green light from `rspec`, go ahead and `add`/`commit`/`push` your changes (`hello_world.rb`).  Go visit your repo on Github and refresh the page.  Above the list of folders/files, you should see your latest commit.  Above that, you should see a button for a **New pull request**. Follow the directions to create the pull request. You may see a yellow dot (the `rspec` tests are running server-side) that eventually turns into a green check mark (the `rspec` tests passed!).

### You're all done!

In nearly every programming language you learn, printing `Hello World!` is always your first task. Your adventure in Ruby has only just begun.

### Hello World History

A small piece of coding history—a handwritten version of Hello World in C (an early programming language). 

![Hello World! Art](https://d32dm0rphc51dk.cloudfront.net/b6JQ66-0nHij79irJT-Pdg/large.jpg)

_[Hello World! by Brian Kernighan, from Artsy's Algorythm Auction](https://www.artsy.net/artwork/brian-kernighan-hello-world) based on a 1974 Bell Laboratories internal memorandum by Brian Kernighan, Programming in C: A Tutorial, which contains the first known version._