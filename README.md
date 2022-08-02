# Beamer-latex-


\documentclass[aspectratio=169]{beamer}
\usepackage[utf8]{inputenc}

\usetheme[progressbar=frametitle]{metropolis}
\setbeamertemplate{frame numbering}[fraction]
\metroset{background=dark}

\definecolor{primary}{RGB}{245, 10, 10}

\setbeamercolor{palette primary}{bg=white, fg=black}
\setbeamercolor{background canvas}{parent=palette primary}
\setbeamercolor{normal text}{fg=black}
\setbeamercolor{progress bar}{use=palette primary,fg=primary}


% title page
\title{Example presentation}
\subtitle{This is our subtitle}
\author[Tartarini, Doe]
{F.~Tartarini\inst{1} \and J.~Doe\inst{2}}
\institute{
\inst{1}
Faculty of Engineering, University 1
\and
\inst{2}
Faculty of Science, University 2
}
\date{2020}

\begin{document}

\begin{frame}{}
\titlepage
\end{frame}

\begin{frame}{Table of Contents}
    \tableofcontents
\end{frame}

\section{Introduction and Background}

\subsection{Background}

\begin{frame}{Background}
This is the text of our first slide
\end{frame}

\begin{frame}{Background}
This is the the second slide in this subsection.
\end{frame}

\subsection{Introduction}

\begin{frame}{Introduction}
This is the text of our second slide
\end{frame}

\section{Methodology}

\begin{frame}{Methodology slide}
This is the text of our second slide
\end{frame}

\begin{frame}{}
Thank you for listening
\end{frame}

\end{document}
