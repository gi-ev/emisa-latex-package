# emisa-latex-package
```
----------------------------------------------------------------------------
emisa --    A LaTeX package for preparing manuscripts for the journal EMISA
            Enterprise Modelling and Information Systems Architectures -
            An International Journal (EMISA)
(c) 2015, 2016
Version:    2.1.1        
Maintainer: Stefan Strecker and Martin Sievers
Email:      stefan.strecker@fernuni-hagen.de
            martin.sievers@schoenerpublizieren.de
License:    Released under the LaTeX Project Public License v1.3c or later
See:        http://www.latex-project.org/lppl.txt
----------------------------------------------------------------------------

Developing and documenting the “official” LaTeX package for preparing 
manuscripts for the journal EMISA (Enterprise Modelling and Information 
Systems Architectures): https://emisa-journal.org

Each release of the EMISA LaTeX package will be available on Github 
(https://github.com/sstrecker/emisa-latex-package) and shortly afterwards on 
CTAN (https://www.ctan.org/pkg/emisa). From there it will make its way to 
package managers of recent TeX distributions (e.g. “tlmgr” of the 
TeX Live distribution).

Read emisa.pdf for author instructions and style guidelines.
```

## Changelog
### 2.1.1 to 2.1

* Fixed a bug introduced with version 2.1. Undefined macro \ifempty was changed to \ifdefvoid

### 2.1  to 2.0.1

* Fixed a bug introduced by incompatible changes of latest biblatex packages (>3.3)

### 2.0.1 to 2.0

* Set uniquelist option to false in order to change the cite output
* Changed maxcitenames=3 to maxcitenames=2
* Added \FloatBarrier from the placeins package at the end of the appendix
* Added tracking (5%) for smallcaps
* Moved special issue title below title in page header
* Modified insertion of license text

### 2.0

* Initial release of the completely reworked bundle

