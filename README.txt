== MadCoder.tv

This is the repository for the website http://madcoder.tv and the Roku Channel MadCoder.tv

The madcoder.tv demonstrates a hierarchical,
category based video playback application. The
application allows the playback of a selection 
of Development videos which are organized by category.
  
The application uses a category based XML feed 
to drive the application. The XML describes all
of the categories used, artwork required and
videos to be played. The hierarchy of categories 
is described in the file categories.xml.  
The actual XML request/response uses our servers, 
but the XML is all included for reference.

Each category branch node, ultimately terminates at a 
leaf node that lists details for all of the videos 
included in that category. The XML for the leaf 
nodes is also included and named in the format 
<category>.xml.

Contents of the application directories are:

In the gh-pages branch:
xml      - Categories and Episodes of videos
           available for playback.
images   - Screenshots and Logos for the categories
           and episodes described in the xml directory.

In the master branch:
images   - Artwork that is embedded as part of 
           the application. 
source   - The complete BrightScript source code 
           for the application
artwork  - Photoshop versions of the images.  
manifest - This file describes the application 
           package and is used on the main menu 
           prior to the start of execution for the 
           application.
Makefile - Optional method of building the application 
           using "make". This has been provided for 
           convenience and tested on OSX and linux.


      **************************************************

This channel uses videos streamed directly from Confreaks ( http://confreaks.com ) 
and RailsCasts ( http://railscasts.com ). Please visit their websites to see the latest
available videos and premium features and services. 

Please see the following for license details:
http://creativecommons.org/licenses/by-nc-nd/3.0/

