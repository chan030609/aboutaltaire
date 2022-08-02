---
layout: layouts/page.njk
title: Developer
permalink: /developer/index.html
socialImage: ""
---
This is a developer page for those who would like to contribute to this project. What languages, tools, frameworks, and libraries we are using are all detailed here.

![](/images/altaire-logo.png)

## Language

- The language of this entire app is built in JavaScript and TypeScript.

## Stack

- For Frontend/UI, we are using [React (v18)](https://en.reactjs.org/) and [Next.js](https://nextjs.org/). 
- For backend and authentification, we are using [Firebase](https://firebase.google.com/).
- Both frontend and backend are integrated into a single repository.

## Tools

- For the ease of UI development, we are using a UI library [Tailwind CSS](https://tailwindcss.com/), which enables in-line CSS expressions. 
- For WYSIWYG editor with a rich text formatting, we are using [Tiptap 2.0 beta](https://tiptap.dev/). 
- For Markdown editor, we are using [react-md-editor](https://github.com/uiwjs/react-md-editor). A conversion from Markdown to HTML and vice versa is processed through [Showdown](https://github.com/showdownjs/showdown) and [Turndown](https://github.com/mixmark-io/turndown). 
- For complex queries that Firestore does not support and full-text search, we are using [Typesense](https://typesense.org/).
- For the graph visualization of nodes, we are using [Cytoscape.js](https://js.cytoscape.org/).