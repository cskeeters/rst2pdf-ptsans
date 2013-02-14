# rst2pdf PT Sans

This is a stylesheet for using the PT Sans and PT Sans Narrow fonts to make pdf files from [reStructuredText](http://docutils.sourceforge.net/rst.html) and [rst2pdf](http://rst2pdf.ralsina.com.ar/).

You can put these files in the same directory as your documentation and then use this command to include the style.

  rst2pdf -s ptsans doc.txt && o doc.pdf

I used:

  rst2pdf -s ptsans,letter,friendly doc.txt && o doc.pdf

Many thanks to [ReportLab](http://www.reportlab.com/) for their release of the [ReportLab Toolkit](http://www.reportlab.com/software/opensource/rl-toolkit/).  This enables beautiful PDF files to be created quickly without LaTeX.
