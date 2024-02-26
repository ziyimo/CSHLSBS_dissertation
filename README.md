### Scalable and robust deep-learning methods power evolutionary-genetic studies of biobank-scale population genomic data

#### Summary

This is a dissertation submitted to the Cold Spring Harbor Laboratory School of Biological Sciences for my Ph.D. degree in Computational Biology. The thesis consists of

* A general introductory chapter 1 that touches upon many technical and methodolgical topics related to my graduate work, primarily evolutionary modeling and AI/ML. Reviews cited in this chapter provide much more in-depth discussion on these topics.

* Three stand-alone chapters, each presenting the entirety of a research project. These chapters are all peer-reviewed and published in academic journals.

* A concluding chapter 5 that discusses my graduate work as a whole and raises several promising avenues for future work. I am most excited about this chapter, __which outlines several ideas that occurred to me in light of the rise of generative AI as I wrapped up my graduate work__, and I look forward to seeing these ideas come to fruition.

<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

#### Credits

The format of this dissertation is adapted from a [template](https://www.overleaf.com/latex/templates/stony-brook-physics-phd-thesis-template/mbvckkwhfntf) in the Overleaf gallery originally created by Benjamin Hornberger, Mike Stewart and Olof Salberger, under a [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).

#### Template details

The template package consists of the following files:

* `usbthesis.cls`
General document class file. Keep in the same directory as
everything else, or in the TeX search path. You shouldn't have to
make any changes to it, unless you want to change the appearance of
the front matter or you find further bugs beyond the ones I found.
To produce the extra abstract printout with the advisor's name on it (see the grad school's guidelines), you can uncomment line 179.

* `thesis.tex`
This is your thesis "root" file. It loads all the packages which I
needed / found useful -- edit to your heart's content. In the
bibliography section, there are some "%input" directives which help
WinEdt find your BiBTeX files for automatic completion of \cite{}
commands. This only works with the WinEdt editor. To the TeX system, this is just a comment.

* `mathdefs.tex`
This file defines a number of special commands for easier and more
consistent math typesetting (like units etc.). Most are taken from
the article which is mentioned at the top of the file. Note that
also the \vec{} command is redefined to use a boldface letter rather
than an arrow; if you don't like it, comments out that part. I also
recommend using the amsmath package for nicer and easier math
typesetting; have a look at its documentation (the Kopka / Daly book
also has a section about it).

* `hyperref.cfg`
This file contains the setup for the hyperref package which produces
a nicely hyperlinked PDF file (you could also include the hypersetup
in the root file, but that makes it kind of messy). Have a look at
the documentation of the hyperref package. You definitely have to
adjust the driver name (dvipdfm, pdftex, dvips, etc.) to the method
you want to use to produce the PDF. I found it useful to use
"hypertex" while editing the document with MiKTeX and DVI preview
(in which case there are working links in the DVI file when viewed
with the Yap program) and switching to "dvipdfm" for the final
version from which the PDF was produced (in which case the links
work fine in the PDF).