# Metropolia Bachelor's Thesis 

# Instructions to compile

## Compiler

Use XeLaTeX as a compiler.

### Compilation

Usual compilation sequence

    $ xelatex thesis
    # If any change in the bibliography
    $ bibtex8 thesis
    # If any change with the abbreviation or acronym
    $ makeglossaries thesis
    #Then compile again
    $ xelatex thesis
    #And if still some citation or label warnings, compile once more
    $ xelatex thesis

### Using ShareLaTeX

1. Download this project as zip (or fork)
1. Create an account on [ShareLaTeX](https://www.sharelatex.com?r=2c9014ea&rm=d&rs=b) (if not already have one)
1. Once logged in ShareLaTeX: Open Project section. Then New Project &rarr; Upload Project &rarr; select the zip (otherwise with the paid version you could sync with github (your fork))
1. Once project opened: from the menu change "compiler" to XeLaTeX


## Editor

### Indentation

Use (2) spaces instead of tabs.


