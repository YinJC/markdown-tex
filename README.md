# markdown-tex

markdown processor in TeX.

```tex
\documentclass[uplatex]{jsarticle}
\usepackage{md}

\begin{document}
\begin{markdown}

# markdown-tex

markdown processor in TeX.

## supported syntax

So far, you can write normal paragraph, codelist, quoatatio, itemize list, and enumerate list. 

As inline styles, `tt`, *italic*, and **bold** are available.

## example

Inshort, you can write something like below.
Below is a `codeline` block.

    codeline
      another codenline

Here is a enumerate list.

1. enumerate
1. in 
1. the markdown way

## subsection

This is an itemize list. 

* this block
* will
* turn 
* into an 
* itemize

And a quotation. 

> Quote Somethin
> Really **Awesome**!

Here is the end of markdown text.


\end{markdown}
\end{document}

```

## restriction

You can not use \, {, and } in the markdown environment. (awuful)


