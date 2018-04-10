# Description
A simple LaTeX template for bachelor thesis (ITMO University).  
Forked from [vedyakov/bachelor](https://github.com/vedyakov/bachelor). Remade for XeLaTex.

# Notes:

If you are using a ``xelatex`` compiler, there are some stamps appear in your document after compilation. Overwise (for ``pdflatex``) they are not.

Also, for a stamp generation you have to install fonts from the ``fonts`` folder into your system and use one of the _cache command_ according to your tex distro. For example, for TexLive it will be 
<pre>
fc-cache -f
</pre>

# Templates:
* ``diplom.tex`` &mdash; main file, including other tex-files,
* ``conclusion.tex``, ``introduction.tex``, ``overview.tex`` &mdash; templates for conclusion, introduction and overview;
* ``bibliography.tex`` &mdash; all bibliography stuff here;
* ``environment.tex`` &mdash; some environment definitions.

# Settings files
``settings`` folder:
* ``setup.tex`` &mdash; all settings and packages.

# Style files:
``styles`` folder:
* ``diplom.sty`` &mdash; main style file,
* ``frames-G2-104-68.sty``, ``styles-G2-105-95.sty`` &mdash; GOST style files,
* ``makevar.sty`` &mdash; handmade package for using local scoped counters

# TODO:
* [x] make text in frames with variable width, depends on box width;
* [x] make font size in frames like GOST says;
* [x] make GOST headings (section, subsection, etc.);
* [x] make bibliography;
* [x] make partly pdflatex support;
* [ ] clean styles;
* [ ] make full pdflatex support;
* [ ] all other stuff.
