css-for-print
=========

Example files for creating PDF books from print. CSS all works with Prince. Resources and more information about CSS and creating ebooks in a variety of formats can be found on my site [Book Toolkit](http://booktoolkit.com).

## Using these files

The file book.html contains excerpts from a public domain book - [Our Cats by Harrison Weir](http://www.gutenberg.org/ebooks/35450) - to demonstrate the use of CSS for print.

### Create a PDF

    > prince -s pdf-styles.css book.html builds/book.pdf
