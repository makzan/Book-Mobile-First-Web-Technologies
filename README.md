# Book: Mobile First Web Technologies

## Table of Content

1. [Introduction to mobile web](./chapter-1/)
2. [Content-first strategy](./chapter-2/)
3. [Mobile-first approach](./chapter-3/)
4. [Navigation strategy in mobile](./chapter-4/)
5. [Mobile-first layout with media queries](./chapter-5/)
6. [Responsive typography](./chapter-6/)
7. [Form inputs and handling touches](./chapter-7/)
8. [Web vs. App and single-page applications](./chapter-8/)
9. [Taking the web offline](./chapter-9/)
10. [Summary](./chapter-10/)

## The usage of index.html

The `index.html` file are used as example demonstration.

## Post-process the writing in Github and Markdown

The markdown files in this repository serve for both Github browsing and LeanPub book rendering. So we have to post-process the markdown files for different destinations.

For example, each chapter is a folder. Inside each chatper folder, the README.md is the default file to render in Github. But during post-process, these README.md files are renamed to the chapter-N.md and are further included into the Book.txt for LeanPub book rendering process.

## Heading levels generation

By default, each file begins with `h1` as the document title. When we compile the markdown files into a book with chapters. Those heading levels are decreased into the cooresponding levels.