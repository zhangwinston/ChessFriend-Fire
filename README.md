# ChessFriend-Fire
[![Build Status](https://travis-ci.org/SFBrand1981/ChessFriend-Fire.svg?branch=master)](https://travis-ci.org/SFBrand1981/ChessFriend-Fire)
[![Twitter Follow](https://img.shields.io/twitter/follow/SFBrand81.svg?style=social)](https://twitter.com/SFBrand81)


Use ChessFriend-Fire to create a chess database and analyze all your games.
Try it out and visit us at [www.schachfreunde-brand.de](https://www.schachfreunde-brand.de)!


<div style="text-align: center;">
     <img src="https://github.com/SFBrand1981/ChessFriend-Fire/blob/master/docs/ChessFriend-Fire_collage.png"/>
</div>


## Installation

   1. Download the files from the latest ChessFriend-Fire [release][release].
   On a Windows machine, you can use the tool [7zip][7zip] to unzip the `release_win.tar.gz` archive.
      
   2. Change into the directory where you have unzipped your files.
   
      1. On a Windows machine, double-click on the file:

      ```
      chessfriendfire.bat
      ```


      2. On macOS, run the following in terminal:

      ```bash
      $ ./node_modules/nw/bin/nw ./src/
      ```

      3. On Linux, you need to compile a recent version of [node.js][nodejs] for yourself. The following commands can be used to install
      ChessFriend-Fire using node version 10.15.0 (tested with Ubuntu 18.04.2 LTS):

      ```bash
      $ sudo apt-get install nodejs
      $ npm install
      $ npm run linux
      ```

## Features

### Ships with Stockfish 10


<img align="left" src="https://github.com/SFBrand1981/ChessFriend-Fire/blob/master/docs/ChessFriend-Fire_engine.png" width="40%"/>

By default, ChessFriend-Fire includes the binaries of Stockfish 10, one of the strongest chess engines available. Start the engine by clicking
on the 'play' button underneath the chess board. With a right-click on the displayed engine lines, you can open the engine settings menu,
where you can specify the path to the engine (can be any UCI-compatible chess engine installed on your system) and basic settings
like multiPV (number of variations which the engine calculates simultaneously) and the number of CPU threads that the engine
is allowed to use (default: 1).



<br clear="both"/>



### One-click annotations

<img style="float:left;" src="https://github.com/SFBrand1981/ChessFriend-Fire/blob/master/docs/ChessFriend-Fire_menu.png" width="40%"/>

A right-click into the notation panel opens a context menu with shortcuts to commonly used numeric annotation glyphs (NAGs) which upon
selection will be automatically inserted after the currently highlighted move.


### Open your games in tabs

<div style="text-align: center;">
     <img src="https://github.com/SFBrand1981/ChessFriend-Fire/blob/master/docs/ChessFriend-Fire_tabs.png" width="40%"/>
</div>

ChessFriend-Fire opens all your games in tabs. It has never been easier to switch between all your favorite games!


### Fast database search

<div style="text-align: center;">
     <img src="https://github.com/SFBrand1981/ChessFriend-Fire/blob/master/docs/ChessFriend-Fire_search.png" width="40%"/>
</div>

With ChessFriend-Fires's powerful search functionality, you can browse through any database with lightning speed.
ChessFriend-Fire also allows you to tag your games with custom labels, which makes it super easy to find them later again.


### Analyse any position

<div style="text-align: center;">
     <img src="https://github.com/SFBrand1981/ChessFriend-Fire/blob/master/docs/ChessFriend-Fire_setup.png" width="40%"/>
</div>

A click on 'Setup position' enables you to setup an arbitrary position on a chessboard and search for it in the database
or add it as the starting point of a new game. Move the pieces around with a click from your mouse.


### LaTeX export

<div style="text-align: center;">
     <img src="https://github.com/SFBrand1981/ChessFriend-Fire/blob/master/docs/ChessFriend-Fire_latex.png" width="40%"/>
</div>


ChessFriend-Fire allows you to export your game as a LaTeX-file and helps you to produce publication-ready documents
in the twinkling of an eye. For example, any comment of the form `\diagram` will automatically be converted into
a chess diagram, without any further user action necessary. In order to convert the LaTeX file into a pdf-document,
you need to have a LaTeX processor like [xelatex][xelatex] installed 


### Keyboard shortcuts

  
[7zip]: https://www.7-zip.org/download.html
[nodejs]: https://nodejs.org/en/
[release]: https://github.com/SFBrand1981/ChessFriend-Fire/releases
[stockfish]: https://github.com/SFBrand1981/ChessFriend-Fire/tree/master/src/bin
[xelatex]: https://en.wikipedia.org/wiki/XeTeX
