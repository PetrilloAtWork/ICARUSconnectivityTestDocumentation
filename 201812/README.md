ICARUS connectivity test technical note - December 2018
========================================================

This note describes the ICARUS connectivity test performed at Fermilab on December 2018.
See `sections/abstract.tex` for the full abstract.


Structure of the repository
----------------------------

The repository is structured in few subdirectories:
    
    201812/        main file (`ConnectivityTestTechnicalNote.tex`), skeleton of the document
        sections/  content of the note, one file per section, and abstract
        fig/       all images


Rendering of the note
----------------------

This repository is connected with the Overleaf service. The Overleaf project is not shared by URL, but you can ask for inclusion to its "owner", currently [Gianluca](petrillo@slac.stanford.edu).

It can also be compiled locally, by cloning the repository as per GitHub instructions, and compiling it from the main directory:
    
    latexmk
    
will build a Portable Document Format (PDF) rendering of the document.
To clean LaTeX temporary files, execute `latexmk -c`.

