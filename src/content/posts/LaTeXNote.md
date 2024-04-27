---
title: My LaTeX Note 
published: 2024-04-28
description: My LaTeX Note. 
tags: [Markdown, Blogging, Demo]
category: Examples
draft: false
---
## My LaTeX Note Today 
Just started learning LaTeX today from a book and also typing code in a compiler. It is very interesting. I hope to continue learning untill I master it.
It looks complicated, but it makes me feel in control of everything. It's much more difficult than markdown, but still easier than a real programming language like python. So I think I can manage it soon.
This is my code for today:
```
\documentclass[12pt]{scrartcl}
\usepackage[short,nodayofweek,level,12hr]{datetime}
\usepackage{booktabs} 
\begin{document}

This is a simple document. Here is the first paragraph.

Here is the second paragraph. As you can see it's
a rather short paragraph, but not as short as the previous one.

This is a simple \LaTeX\ document. Here is the first paragraph.

Here is the second paragraph \footnote{with a footnote}. As you can see it's rather short paragraph, but not as short as the previous one. This document was created on: \today at \currenttime.


It's na\"ive to think that eating moudy p\^at\'e won't result in food poisoning.

\begin{itemize}
\item Animal
\item[{[X]}] Vegetable
\item Mineral
\end{itemize}

\begin{itemize}
	\item Animal
	\begin{itemize}
		\item Mammals
		\item Birds
		\item Reptiles. For example:
		\begin{itemize}
			\item dinosaurs
			\item crocodiles
		\end{itemize}
	\end{itemize}
	\item Vegetable
	\begin{itemize}
		\item Cultivated
		\item Wild
	\end{itemize}
\item Mineral

\end{itemize}

\begin{enumerate}
	\item Animal
	\item Vegetable
	\item[{[X]}] Vegetable
	\item Mineral
\end{enumerate}

\begin{description}
	\item[Animal] Living being
	
	\item[Vegetable] Plant
	
	\item[Mineral] Natural inorganic substance

\end{description}

In the code below, the first instance of "repeated" does not 
have an italic correction but the second does:
{\itshape repeated}ly {\itshape repeated\/}ly

Some \emph{emphasized} text.

{\itshape Some \emph{emphasized} text.}

{\sffamily Some \emph{emphasized} text.}

\begin{itshape}Some italic text.
\begin{Large}This text is large. 
\end{Large}
\end{itshape}
Back to normal. 

\begin{tabular}{lr}
	Video & 8.99\\
	CD & 9.11\\
	DVD & 15.00\\
	\bfseries Total & 33.10
\end{tabular}

Let's add an extra column and a header row:

\begin{tabular}{lrr}
	Item & ex VAT & inc VAT\\
	Video & 8.99 & 10.56\\
	CD & 9.11 & 10.70\\
	DVD & 15.00 & 17.63\\
	\bfseries Total & 33.10 & 30.89
\end{tabular}

Aligning on a Decimal Point

\begin{tabular}{lr@{.}l}
	Video & 8 &99\\
	CD & 9 & 11\\
	DVD & 15 & 00\\
	\bfseries Total & 33 & 10
\end{tabular}

Spanning Columns

\begin{tabular}{lrr}
	& \multicolumn{2}{c}{Price (\pounds)}\\
Item & ex VAT & inc VAT\\
Video & 8.99 & 10.56\\
CD & 9.11 & 10.70\\
DVD & 15.00 & 17.63\\
\bfseries Total & 33.10 & 39.89
\end{tabular}

"Year1\&Year2" in center but number in right:

\begin{tabular}{lrr}
	& \multicolumn{1}{c}{Year1}
	& \multicolumn{1}{c}{Year2}\\
Travel	& 100,000 & 110,000\\
Equipment & 50,000 & 60,000
\end{tabular}

Three-Line Rules:

% add \usepackage{booktabs}  to environment at top.
\begin{tabular}{lrr}
\toprule
	& \multicolumn{1}{c}{Year1}
	& \multicolumn{1}{c}{Year2}\\
\midrule
Travel	& 100,000 & 110,000\\
Equipment & 50,000 & 60,000\\
\bottomrule
\end{tabular}

Here is some text. 
\begin{tabular}{cc}
A & B\\
C & D
\end{tabular}
The rest of the line.

Here is some text.
\begin{tabular}[b]{cc}
A & B\\
C & D
\end{tabular}
The rest of the line.

Box making comparison:

\raggedright Some text at the beginning of paragraph. Some text in the middle of the paragraph. Some text in the middle of the paragraph. Some more text. \par

\raggedright Some text at the beginning of a paragraph.
\mbox{Some text in the middle of the paragraph. Some text in the middle of the paragraph.} Some more text.
\par


\end{document}
```

Apr 28, 2024
