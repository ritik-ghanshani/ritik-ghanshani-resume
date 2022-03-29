# ritik-ghanshani-resume

A dev-container based Latex environment for my resume. 

**Note to self**

Add this to settings.json to ensure error free compilation into PDF:


```
"latex-workshop.latex.tools": [
        {
            "name": "latexmk",
            "command": "latexmk",
            "args": [
                "-xelatex",
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "%DOC%"
            ]
        },
],
```