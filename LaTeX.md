# LaTeX Commands and Styling for Documents

## Document Structure

\documentclass{article} <!--  % Defines the document type (e.g., article, report, book)-->
\begin{document}        <!--  % Start of the document-->
...                     <!--  % Your content goes here-->
\end{document}          <!--  % End of the document-->

----------

## Common Sections

\section{Section Title}        <!-- % Creates a numbered section-->
\subsection{Subsection Title}  <!-- % Creates a numbered subsection-->
\subsubsection{Subsubsection}  <!-- % Creates a numbered sub-subsection-->
\paragraph{Paragraph Title}    <!-- % Paragraph with a title-->
\subparagraph{Subparagraph}    <!-- % Subparagraph with a title-->

----------

## Text Styling

\textbf{Bold Text}        <!--  % Bold text-->
\textit{Italic Text}      <!--  % Italic text-->
\underline{Underlined}    <!--  % Underlined text-->
\texttt{Typewriter Font}  <!--  % Monospaced font-->
\emph{Emphasized Text}    <!--  % Italicized or styled text for emphasis-->

----------

## Lists (Unordered list)

\begin{itemize}
    \item First item
    \item Second item
    \item Third item
\end{itemize}

----------

## Lists (Ordered list)

\begin{enumerate}
    \item First item
    \item Second item
    \item Third item
\end{enumerate}

----------

## Mathematical Equations

***Inline Math***
$E=mc^2$ % Inline equation

----------

***Display Math***
\[
E = mc^2
\]

----------

## Equation Environment (with Numbering)

\begin{equation}
E = mc^2
\end{equation}

----------

## Tables

\begin{tabular}{|c|c|c|}
\hline
Header 1 & Header 2 & Header 3 \\ \hline
Row 1    & Value 1  & Value 2  \\ \hline
Row 2    & Value 3  & Value 4  \\ \hline
\end{tabular}

----------

## Adding Images

\usepackage{graphicx} <!--  % Include this in the preamble-->
\begin{figure}[h]
    \centering
    \includegraphics[width=\textwidth]{image.jpg}
    \caption{Caption for the image}
    \label{fig:image_label}
\end{figure}

----------

## Customizing the Document

***Title, Author, and Date***
\title{Your Document Title}
\author{Your Name}
\date{\today} <!--  % Automatic current date-->
\maketitle <!--  % Display the title, author, and date-->

## References

***Adding a Bibliography***
\begin{thebibliography}{99}
    \bibitem{ref1} Author, Title, Year.
    \bibitem{ref2} Another Author, Another Title, Year.
\end{thebibliography}

----------

***Citing References***
As stated in \cite{ref1}, ...

----------

## Comments

% any comment <!--  % symbol is used to make a comment in LaTeX-->
