# The Learn IDE

![learn ide](http://i.giphy.com/ZHlGzvZb130nm.gif)

## What is It?

The Learn IDE is a cross-platform application (OS X, Windows) that allows Learn users to (1) write code in a modern text editor (Atom) and (2) use a fully-configured Terminal, in a way that feels like local development but is, in fact, virtualized behind the scenes. The application is our own custom fork of GitHub's Atom text editor, that adds to it a virtualized Terminal.

Note: The Windows version must be installed on an administrator account.

## How Does It Work?

The Learn IDE (client) runs against a Learn IDE server in our cloud, to which all users connect. The file system that is exposed to the user in the Learn IDE (in their `code` directory, seen in the file browser) is synchronized to the Learn IDE server. All commands the user types into the terminal window are relayed to the Learn IDE server and the response is echoed from that server.

The file tree on the left and the text editor window on the top are on the users local machine. The command line on the button (and all the files you can see through the command line) are actually on the Learn server! Every time you save a file, it syncs between the students local machine and the Learn server.

To get a better understand of _how_ the Learn IDE works, check out this short video. 

<iframe width="100%" height="720" src="https://www.youtube.com/embed/j7rvsCXXjug?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

## Why do we use the IDE

Because the Learn IDE server has been configured to have all packages required to develop on Learn, there is effectively zero probability of a development environment configuration issue (e.g. the correct version of ruby will always be installed and by default made available to the user) complete with the `learn` gem already installed for them. The only class of error that should crop up will be (1) installation issues with the Learn IDE itself or (2) user account management issues, both of which this track and the reference guide should help troubleshoot.

## Get the Learn IDE

As a Learn Expert, you will need to have the Learn IDE installed so that you can trouble shoot issues. When trying to reproduce a student's issue when they're on the Learn IDE, what better place than in your own Learn IDE! This way you will be using the exact same environment setup.

If you don't already have the Learn IDE, select the [correct download link](https://github.com/flatiron-labs/learn-support/blob/master/learn-ide.md#reference-links) for your OS and please install it!
