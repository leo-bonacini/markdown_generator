# Markdown Generator

A browser-based Markdown editor with live preview, equation rendering, diagram support, and export options. No installation required — open `index.html` and start writing.

![Preview](https://raw.githubusercontent.com/leo-bonacini/markdown_generator/main/images/placeholder.svg)

## Features

* Live split-pane preview as you type
* Math equations via KaTeX (inline and block)
* Mermaid diagrams (flowchart, sequence, Gantt)
* Syntax-highlighted code blocks
* Table support
* Resizable editor and preview panes
* Download as Markdown or PDF
* One-click snippet insertion from the toolbar

## Usage

1. Open `index.html` in any modern browser
2. Write Markdown in the left pane
3. See the rendered output in the right pane in real time
4. Use the toolbar buttons to insert equations, diagrams, code blocks, or tables
5. Click **Download** and choose Markdown (.md) or PDF (.pdf) to export

## Toolbar Reference

| Button | What it inserts |
|---|---|
| Inline eq | KaTeX inline equation |
| Block eq | KaTeX display equation |
| Flowchart | Mermaid flowchart diagram |
| Sequence | Mermaid sequence diagram |
| Gantt | Mermaid Gantt chart |
| Code | Fenced code block |
| Table | Markdown table |

## Technologies

* Marked.js for Markdown parsing
* KaTeX for math rendering
* Mermaid for diagrams
* Highlight.js for code syntax highlighting
* html2pdf.js for PDF export
