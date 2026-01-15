![BARN ETA](../ref/BARN-ETA-Header.png)
<link href = "../ref/_barn.css" rel="stylesheet" type="text/css" />

# Read Me

This GitHub repository is for information about the Tech Lab's equipment and procedures. 
## NOTE 
_This page has  references to the Electronic and Technical Arts Studio - the earlier name for what is now called Tech Lab. They need to be updated appropriately._

## General References

### Using GitHub

- [GitHub: "Hello World" Getting started with GitHub](https://guides.github.com/activities/hello-world/)
- [GitHub: Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [MarkDown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Marpit: Markdown slide deck framework](https://marpit.marp.app)

### Studio Info
- [BARN Tech Lab](https://bainbridgebarn.org/studios/techlab/)


### 3D Printer Usage and Troubleshooting
- [Filaments for 3D Printing](./Filaments%20for%203D%20Printing.md)
- [Prusa Knowledgebase - Tips and Techniques](https://help.prusa3d.com/l/en/category/cO74WGHTlH-printing)
- [Visual Guide to 3D printer problems](https://support.3dverkstan.se/article/23-a-visual-ultimaker-troubleshooting-guide)
- [3D Printing Orientation Links](https://rgordon.github.io/3d-printing-orientation/)

# Converting files to PDF
There are several ways to convert the files to PDF depending upon the host. (TODO build a GitHub Action that automates this.)

## For whole files, not slide decks:

### on MacOS CLI:
- brew install pandoc
- brew install --cask mactex
- pandoc "3d-printing/<filename>>.md" -o "3d-printing/<filename>.pdf" --pdf-engine=xelatex -V geometry:margin=1in -V fontsize=11pt

### in VSCode:
- install Markdown - PDF extension
- Cmd-Shift-P -> Markdown PDF: Export (pdf)

## For slide decks:
### on MacOS CLI:
- brew install marp
- marp --pdf <filename> 

### in VSCode:
- install Marp Extension
- Cmd-Shift-P -> Marp : Export Slide Deck ...
