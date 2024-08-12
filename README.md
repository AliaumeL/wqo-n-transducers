# Well-Quasi-Ordered Approach to N-Polyregular Functions

This repository contains the code and data for the paper 
"Well-quasi-ordered N-polyregular functions".

## How to build

You will need a working [LaTeX] installation to build the paper. The paper is
written in [LaTeX] and uses [BibTeX] for the bibliography. Furthermore,
a [Makefile] is provided to automate the build process. To build the paper,
you can run the following command:

```bash
make wpreg.pdf
```

This will generate the file `wpreg.pdf` in the current directory.

If you want to publish to [the arXiv] you can generate a self-contained
version of the paper by running the following command:[^arxiv]

```bash
make wpreg.arxiv.tar.gz
```

[^arxiv]: This uses the [tar] command, which should be available on most Unix-like systems.

## How to contribute

The paper is written in [LaTeX] and the source files are located in the `src`
directory. Custom macros and environments are located in the `lib` directory.
Bibliography entries are all located in the single file `papers.bib`.

This paper uses the [knowledge] package which uses the file `knowledges.kl` to
store the knowledge base. We refer to the official documentation of the
[knowledge] package on the CTAN for more information.

The metadata of the paper (authors, title, abstract, doi ...) are stored in a
separate `paper-meta.yaml` file, with the hope that it will be useful for
future automation.


[LaTeX]: https://www.latex-project.org/
[BibTeX]: http://www.bibtex.org/
[Makefile]: https://www.gnu.org/software/make/
[the arXiv]: https://arxiv.org/
[tar]: https://www.gnu.org/software/tar/
[knowledge]: https://ctan.org/pkg/knowledge
[CTAN]: https://ctan.org/
