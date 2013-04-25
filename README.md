The chemstyle bundle - Schemes and style for chemistry
======================================================

The `chemstyle` bundle provides two packages: `chemstyle` and
`chemscheme`.  Both are intended to help chemists create floating
graphics and match published styles.

The `chemscheme` package consists of two parts, both related to
chemical schemes.  The package adds a `scheme` float type to the
LaTeX default types figure and table. The `scheme` float type
acts in the same way as those defined by the LaTeX kernel, but
is intended for chemical schemes.  The package also provides a
method for adding automatic chemical numbering to schemes.

The `chemstyle` package provides a "one-stop shop" for setting up
formatting of LaTeX documents following the editorial policies
of various chemical journals.  It provides a number of handy
chemistry-related commands, and loads several support packages
to aid the chemist.

Installation
------------

The package is supplied in `.dtx` format and as a pre-extracted
`.zip` file, `chemstyle.tds.zip`. The later is most convenient
for most users: simply unzip this in your local `texmf`
directory. If you want to unpack the `.dtx` yourself, running
`tex chemstyle.dtx` will extract the package whereas `latex
chemstyle.dtx` will extract it and also typeset the
documentation.

Typesetting the documentation requires a number of packages in
addition to those needed to use the package. This is mainly 
because of the number of demonstration items included in the 
text. To compile the documentation without error, you will 
need the packages:
 - `booktabs`
 - `helvet`
 - `mathpazo`
 - `mhchem`
 - `microtype`
 - `listings`
 - `lmodern`