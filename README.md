# TextMate bundle for Liquid development

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/andrew/liquid-tmbundle.git "Liquid.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'


To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/andrew/liquid-tmbundle/tarball/master
    tar zxf andrew-liquid-tmbundle*.tar.gz
    rm andrew-liquid-tmbundle*.tar.gz
    mv andrew-liquid-tmbundle* "Liquid.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

This bundle contains additional Snippets and Grammar used in internal projects.