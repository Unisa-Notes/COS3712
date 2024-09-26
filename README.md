# UNISA COS3712 Notes

This repo contains the LaTeX files needed to compile a set of notes for the course
**Computer Graphics** at the University of South Africa.

## Accessing the Notes
A PDF can be generated using [latexmk](https://ctan.org/pkg/latexmk).
If you want to access pre-generated PDFs,
please check the [Releases](https://github.com/Unisa-Notes/COS3712/releases) section on the sidebar.

## Contributing
Please fork this repo, make your changes, and then open a pull request.

## The Code
### Note
This repository depends on the packages defined in the
[tex-packages](https://github.com/Unisa-Notes/tex-packages) repo being added to your
texmf directory, or your LaTeX compiler having some knowledge about those packages.
Instructions for how to include it are available in that repo.

### The Structure
- The file [COS3712_Notes.tex](COS3712_Notes.tex) contains the general structure and order
  of the files.
  Building this file should build all the other `.tex` files, and include them in one `.pdf`
  called `COS3712_Notes.pdf`
- Each chapter has a separate `tex` file where the notes are written.
  These are contained in the [chapters](./chapters) folder.

---
