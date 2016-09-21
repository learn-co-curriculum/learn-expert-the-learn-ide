# The Learn IDE

<video loop data-source="[{"src":"https://dotcom-v2.s3.amazonaws.com/online-campus-index/ide.mp4","type":"video/mp4"}]">

## What is It?

The Learn IDE is a cross-platform application (OS X, Windows) that allows Learn users to (1) write code in a modern text editor (Atom) and (2) use a fully-configured Terminal, in a way that feels like local development but is, in fact, virtualized behind the scenes. The application is our own custom fork of GitHub's Atom text editor, that adds to it a virtualized Terminal.

Note: The Windows version must be installed on an administrator account.

## How Does It Work?

The Learn IDE app runs against a Learn IDE server in our cloud, to which all users connect. The file system that is exposed to the user in the Learn IDE (in their `code` directory, seen in the file browser) is synchronized to the Learn IDE server. All commands the user types into the terminal window are relayed to the Learn IDE server and the response is echoed from that server.

## Why do we use the IDE

Because the Learn IDE server has been configured to have all packages required to develop on Learn, there is effectively zero probability of a development environment configuration issue (e.g. the correct version of ruby will always be installed and by default made available to the user) complete with the learn gem already installed for them. The only class of error that should crop up will be (1) installation issues with the Learn IDE itself or (2) user account management issues, both of which this track and the reference guide should help troubleshoot.


<p class='util--hide'>View <a href='https://learn.co/lessons/learn-expert-the-learn-ide'>Learn Expert The Learn IDE </a> on Learn.co and start learning to code for free.</p>
