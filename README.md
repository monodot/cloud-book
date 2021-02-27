# cloud-book

This is the source of my _DevOps for Busy Developers_ ebook that you can download for free at <https://tomd.xyz/products>

This is a bit of an experiment to see how easy it is to create a nice-looking ebook with _Lyx_.

## Building

First install [LyX][lyx], the document processor, and additional _texlive_ dependencies:

    dnf install lyx texlive-sectsty texlive-cancel texlive-wrapfig texlive-greek-fontenc

(Hopefully this command works, I forgot to write down exactly what I installed to get up and running 🤡)

To build the PDF, open the book file `cloud-book.lyx` in LyX, and export it to PDF using File &rarr; Export &rarr; Export PDF (XeTeX).

## Issues/resolved

Images are randomly positioned on the page - e.g. at the very top. Not sure why this happens.

(c) 2020 Tom Donohue.

[lyx]: https://www.lyx.org/

