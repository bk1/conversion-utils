# conversion-utils
some tools for converting text files

bin contains useful tools

iso2html and html2iso have been written 20 years ago, but are still valid.
html2utf8 converts HTML entities to UTF-8 characters, excluding &amp; &gt; &lt; &nbsp; and &quot;
html2utf8 -o utf-16 converts them to UTF-16 instead of UTF-8.
There is not utf82html, because these HTML-entities are not needed any more and we should migrate away from them to UTF-8

legacy-bin contains historically useful tools that still exist for the sake of amusement