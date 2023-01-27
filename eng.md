amuthesis.tex:

zakomentuj:

\usepackage{polski}
\renewcommand{\figurename}{Rycina}
\renewcommand{\tablename}{Tabela}

amuthesis.cls

edytuj:

\def\titlepage{{\sf
    \thispagestyle{empty}%
    % \null\vskip1cm%
    \vspace*{-2cm}
    \centerline{\includegraphics[width=19cm]{figures/uam-logo-EN}}
    \begin{center}
    \textbf{Field of studies: \major{}}\\
    \textbf{Album ID: \albumid{}}
    \end{center}
    \vfill
    \begin{center}
        \textbf{\Large{\@author}}\\
        \vspace{10mm}
        \LARGE\textbf{\expandafter{\@title}}\\
        \vspace{10mm}
        \LARGE\textit{\expandafter{\titleeng{}}}
    \end{center}
    \vfill
    \begin{flushright}
        \degreetitle{} written\\
        in the Institute of Geoecology and Geoinformation\\
        under the supervision of\\
        dr hab. Jakub Nowosad
    \end{flushright}
    \vfill
    \begin{center}
        Poznań, \thesisyear{}
    \end{center}
    %\hrulefill
    \newpage\mbox{}\thispagestyle{empty}\newpage}}
