# Libertinus thesis template

LaTeX thesis template using the Libertinus font family.

This repository is a self-sufficient example that can be compiled into a PDF.

## Prerequisites
You need a TeX distribution (for example [TeX Live](https://tug.org/texlive/)) with the packages and fonts used in thesis.tex installed. The template uses XeLaTeX instead of pdfLaTeX and Biber instead of BibTeX. They will be enabled automatically by magic comments if you use [TeXstudio](https://www.texstudio.org/).

The template is based on the [Libertinus font family](https://github.com/libertinus-fonts/libertinus). You may want to manually download the current version from the GitHub repository to update the fonts supplied by the libertinus-otf package. Currently, the math font used is [STIX 2](https://github.com/stipub/stixfonts) instead of Libertinus Math.

## Usage

Download thesis.tex and use it as your root document file. Every modification is commented so that you can modify the style to suit your preference. Important comments are marked by `!!!`.

The title page is included as a separate PDF file. You may use the supplied SVG template to design your own title page in a vector graphics editor (for example [Inkscape](https://inkscape.org/)).

The template is intended for a Ph.D. thesis, but it can be used for any thesis type. I recommend going through the document and making changes that are appropriate for your thesis format.

## Questions and issues

I do not plan on actively developing this, but if you have any problems, questions or suggestions, feel free to open an issue or a pull request. The primary function of this repository is to publish the template I used to write [my thesis](http://theses.cz/id/6sc3bn/dissertation.pdf).
