# Venturer Camp 2023 Documents
*A repository to store external documents produced for Venturer Camp 2023 which have been typeset using LaTeX and the Venturer Camp 2023 Template.*

## Folder Structure
Each document should have a folder made within the root of the repository for it to live in. This folder should be named the document ID. Document IDs should be short names for the document, which should not contain spaces. For example `village-handbook` or `info-pack-v0`.   
Within each of the folders, any additional resources for the document as well as the `.tex` can be stored. The final `.pdf` file should also be left in here.

## Template
The template below should be used for all documents produced. The `\section{Introduction}` and line below should be replaced with the contents of the document.
```tex
\documentclass[a4paper, 11pt]{report}

\input{../global-preamble.tex}

\begin{document}
    \bookTitle{Template Document}{Subtitle}{6th December 2022}{template}
    \tableofcontents
    \chapter{Introduction}
    ...

\end{document}
```
