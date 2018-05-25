\documentclass[a4paper]{amsart}

\usepackage{graphicx}

\title{\LaTeX note}
\author{Yun Zhang}



\begin{document}
\maketitle
\section{Introduction of \LaTeXe }
overleaf commands: https://www.youtube.com/watch?v=RIEIYJEmatE

inline math formula: surrounded by dollar sign:

the recursion formula is:$T(n) = 2T(n/2)+cn$ if $n = 2^{k}$ then $k = \lg{n}$ is the recurse times

you can type fraction by $\frac{-b\pm\sqrt[2]{b^2-4ac}}{2}$ and binom by ${\binom {n+1} k}$

you can also make a equation in the center of text by:
\begin{equation}
\frac{-b\pm\sqrt[2]{b^2-4ac}}{2}
\end{equation}


you can upload pics by: add package at begining, and:
\begin{figure}
\includegraphics[width=0.5\linewidth]{makeChange.png}
\caption{make change code}
\end{figure}

you can create table by:
\begin{center}
\begin{tabular}{|c|c|c|}
\hline