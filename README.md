# Book: Mobile First Web Technologies

## The usage of index.html

The `index.html` file are used as example demonstration.

## Post-process the writing in Github and Markdown

The markdown files in this repository serve for both Github browsing and LeanPub book rendering. So we have to post-process the markdown files for different destinations.

For example, each chapter is a folder. Inside each chatper folder, the README.md is the default file to render in Github. But during post-process, these README.md files are renamed to the chapter-N.md and are further included into the Book.txt for LeanPub book rendering process.

