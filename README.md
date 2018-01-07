# The Browser Learn IDE

![learn ide](http://i.giphy.com/ZHlGzvZb130nm.gif)

## What is It?

The Browser Learn IDE is a cross-platform application (OS X, Windows) that allows Learn users to (1) write code in a modern text editor (Atom) and (2) use a fully-configured Terminal, in a way that feels like local development but is, in fact, virtualized behind the scenes. The application is our own custom fork of GitHub's Atom text editor, that adds to it a virtualized Terminal.

## How Does It Work?

The Browser Learn IDE (client) runs against a Learn IDE server in our cloud, to which all users connect. The file system that is exposed to the user in the Learn IDE is synchronized to the Learn IDE server. All commands the user types into the terminal window are relayed to the Learn IDE server and the response is echoed from that server.

When the students click on the open button in order to open a lab. They browser ide will open in the lesson and will clone a fresh copy of their lab automatically.

The file tree on the left and the text editor window on the top are on the users local machine. The command line on the bottom (and all the files you can see through the command line) are actually on the Learn server! Every time you save a file, it syncs between the students local machine and the Learn server.

To get a better understand of _how_ the Browser Learn IDE works, check out this short video.

<iframe width="100%" height="720" src="https://www.youtube.com/embed/lfGZRD3wErk" frameborder="0" allowfullscreen></iframe>

<!-- <iframe width="100%" height="720" src="https://www.youtube.com/embed/j7rvsCXXjug?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe> -->

## Why do we use the IDE

Because the Browser Learn IDE server has been configured to have all packages required to develop on Learn, there is effectively zero probability of a development environment configuration issue (e.g. the correct version of ruby will always be installed and by default made available to the user) complete with the `learn-co` gem already installed for them. The only class of error that should crop up will be user account management issues, which this track and the reference guide should help troubleshoot.

## Get to know the Browser Learn IDE

As a Technical Coach, you will need to have used the Browser Learn IDE so that you can trouble shoot issues and see for yourself how it works! When trying to reproduce a student's issue when they're on the Browser Learn IDE, what better place than with the Browser Learn IDE! This way you will be using the exact same environment setup.

<p class='util--hide'>View <a href='https://learn.co/lessons/learn-expert-the-learn-ide'>The Learn IDE</a> on Learn.co and start learning to code for free.</p>
