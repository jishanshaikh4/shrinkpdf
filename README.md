## Shrinkpdf
[![CodeFactor](https://www.codefactor.io/repository/github/jishanshaikh4/shrinkpdf/badge)](https://www.codefactor.io/repository/github/jishanshaikh4/shrinkpdf)

Reduce size of PDF (compress) using Ghostscript at terminal.

### Execution

Move the shrinkpdf.sh to your system execution folder (e.g. /bin/ in Linux distro). Give it permissions to execute

  ``chmod +x ~/bin/shrinkpdf.sh``
  
**First parameter (`input.pdf`):** filename of the PDF that is to be converted

**Second parameter (`output.pdf`):** filename of the converted PDF

**Third parameter:** The DPI (resolution) for the output PDF. Default value: 72. For more compression, lower DPI is better but the quality will be worse.

Run it as follows:

    ~/bin/shrinkpdf.sh input.pdf output.pdf
  
    ~/bin/shrinkpdf.sh input.pdf output.pdf 100

    ~/bin/shrinkpdf.sh input.pdf output.pdf 120
  
If you don't want to install shrinkpdf in the system, just run

    bash shrinkpdf.sh input.pdf output.pdf 72

#### Credits

https://bash.cyberciti.biz/file-management/linux-shell-script-to-reduce-pdf-file-size/
