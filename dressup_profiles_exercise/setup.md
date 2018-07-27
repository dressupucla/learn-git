## Set up instructions

For this exercise, DResSUP participants will add their own profiles to the [DResSUP website](http://dressup.library.ucla.edu/participants/). The goal of this exercise is to introduce participants to Git, GitHub, and Jekyll (a static site generator).

A couple of notes:
* We will be doing "pair programming," meaning two people will work together on a single computer.
* Jekyll does run on Windows, but can require a lot of tweaking to get it working. So we can focus on the task, we'll only use Macs for this exercise. If you have a Mac, please follow the setup instruction below **before coming to class**. If you do not have a Mac, you can partner with someone who does. We'll also have a few Mac laptops available for pairs that do not have a Mac.

#### For those with Macs, please do the following before class:

1. Install the command-line tools you'll need to compile native extensions. Open a terminal and run:

`xcode-select --install`

2. Check to see if Ruby is installed:

`ruby -v`

You should see something like `ruby 2.3.3`. If Ruby is not installed, then you will need to install Homebrew (in order to install Ruby)

**Homebrew**: this is a great package manager that all Macs should have! https://brew.sh 
To install, open Terminal and paste this into the prompt: 

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Once Homebrew is installed, you can easily install Ruby with the command:

`brew install ruby`

3. Install Jekyll:

`gem install bundler jekyll`

You can check that Jekyll was installed with `jekyll -v`

4. Install a good text editor. I recommend Atom (https://atom.io), but Sublime and Text Wrangler are also great.

That's it! Let Dawn know if you run into any issues or have questions. 

If you are a Windows user and know you want to create websites using Jekyll, you can find install instructions and tips here: https://jekyllrb.com/docs/windows/

