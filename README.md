# A generic latex manuscript template

Here is a basic manuscript template with basic settings which can help with preparing a general document.
It includes sets of basic packages and configuration to produce an attractive document, hopefully without too many modifications.

A few general notes:

- We use biblatex for references so the metadata in the `refs.bib` file should be in the biblatex format.
- Acronyms are handled using the `glossaries` package.

## Auto formatting

You can modify the `.latexindent.yaml` to configure file formatting using `latexindent.pl`.
Add flag `latexindent -l` to ensure this local configuration is used.
