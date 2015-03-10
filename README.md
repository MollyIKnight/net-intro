Introduction to Internet Technology
===================================

This is my under-development book on introduction to network
technology.  To make the book, install *pandoc* and run

    pandoc --default-image-extension=svg --epub-stylesheet=epub.css *.mkd -o x.epub

    pandoc --default-image-extension=svg *.mkd -o x.html

    pandoc -s -N --toc --default-image-extension=eps -V fontsize:11pt -V documentclass:book --template=template.latex *.mkd -o x.pdf 

Or some similar pandoc command.

You can also run the pdf through LaTeX using 

	sh book.sh

Since the index requires two passes.

You can also generate audio readings of all of the chapters in the audio folder
using 

	sh audio.sh

If you are on a Mac.

