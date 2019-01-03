# API on Rails

Update & translation of the [API on Rails (EN)](http://apionrails.icalialabs.com/book) book.

Traduction française  et MàJ de l'excellent livre [API on Rails (EN)](http://apionrails.icalialabs.com/book)

<noscript><a href="https://liberapay.com/alexandre_rousseau/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>

## Export as PDF

You should install all dependencies. This example with a Debian Linux distribution

~~~bash
$ sudo apt install tex-common texlive-lang-french texlive-latex-recommended texlive-latex-extra texlive-publishers latexmk
~~~

Also you need to install [Pygments](http://pygments.org/) to install

There are so many way to build a PDF from LaTeX but this is a common using `pdflatex`

~~~bash
$ pdflatex --shell-escape api-on-rails.tex
~~~

## License

This book is under [MIT license](https://opensource.org/licenses/MIT) and [Creative Common BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
