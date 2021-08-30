# resume-markdown

Current resume in markdown format with optional output to HTML, PDF and Word formats using Pandoc.

For simple conversion from Markdown to PDF:
```bash
pandoc -s -o resume.pdf resume.md
```

For merging multiple Markdown files into a signle PDF:
```bash
pandoc -s -o resume.pdf part01.md part02.md ...
```

For increasing page margins in the output PDF:
```bash
pandoc -s -V geometry:margin=1in -o resume.pdf resume.md
```

For output to other formats, simply change the extension of output file:
```bash
pandoc -s -o resume.html resume.md
pandoc -s -o resume.docx resume.md
```
