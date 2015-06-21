# XBoard #

XBoard is a graphical user interface for chess in all its major forms, including international chess, xiangqi (Chinese chess), shogi (Japanese chess) and Makruk, in addition to many minor variants such as Losers Chess, Crazy-house, Chess960 and Capablanca Chess. It displays a chessboard on the screen, accepts moves made with the mouse, and loads and saves games in Portable Game Notation (PGN). It serves as a front-end for many different chess services, including:

Chess engines that will run on your machine and play a game against you or help you analyze, such as GNU Chess, Crafty, or many others.

Chess servers on the Internet, where you can connect to play chess with people from all over the world, watch other users play, or just hang out and chat.

Correspondence chess played by electronic mail. The CMail program automates the tasks of parsing email from your opponent, playing his moves out on your board, and mailing your reply move after you've chosen it.

XBoard runs on Unix and Unix-like systems that use the X Window System.

# WinBoard #

The project also includes a port to Microsoft Windows systems called WinBoard.

You can find the downloads for binaries and pre-configured installer packages of WinBoard at the [WinBoard Forum](http://www.open-aurec.com/wbforum/viewforum.php?f=19), where you can also report problems, get help from other WinBoard users or discuss feature requests. Windows builds of development versions or installers for special configurations can be found at [HGM's web page](http://hgm.nubati.net/).

## Background ##

This is a baseline snapshot of the [XBoard - GNU Project](http://www.gnu.org/software/xboard).  I wanted a github repo that I could use for saving snapshots of work in progress.

### Steps used to create repo

First added the repo on GitHub xboard

Now cloned savannah:

		git clone http://git.savannah.gnu.org/r/xboard.git
		git remote rename origin savannah

update github:

		git remote add github https://github.com/zbrad/xboard.git
		git pull github master
		git merge github/master
		git push github master
		git remote rename github origin



