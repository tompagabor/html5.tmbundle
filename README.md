# HTML5 Bundle for TextMate

## Install

The quickest way to install the bundle is via the command line. If you have Git installed, you'll probably want to install with Git. With or without, you can simply copy and paste each line one by one into the Terminal instructions ( lifted from [kswedberg](http://github.com/kswedberg/jquery-tmbundle) ):

### Install with Git

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com:svnlto/html5.tmbundle.git "html5.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

### Install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/svnlto/html5.tmbundle/tarball/master
    tar zxf svnlto-html5.tmbundle*.tar.gz
    rm svnlto-html5.tmbundle*.tar.gz
    mv svnlto-html5.tmbundle* "html5.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

## Download

If you'd like to avoid the command line altogether, you can download the bundle and install it:

1. download the zip from [http://github.com/svnlto/html5.tmbundle/zipball/master](http://github.com/svnlto/html5.tmbundle/zipball/master)
2. find the zip file on your local machine and double-click to unzip it
3. change the file name from *svnlto-html5-tmbundle-really_long_alpha_numeric_sequence* to *html5.tmbundle* (with a dot rather than a hyphen).
4. double-click the *html5.tmbundle* file
5. open TextMate and select the following menu item: *Bundles > Bundle Editor > Reload Bundles*
6. show the Bundle Editor (*Bundles > Bundle Editor > Show Bundle Editor*)
7. scroll through the list of bundles to confirm that the bundle has been properly installed
