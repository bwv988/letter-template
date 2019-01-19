# letter-template

This is my formal letter template which is based on `RMarkdown`, the fantastic `komaletter` package in R, and some *very* minor style modifications to the LCO (Letter Class Options) file shipped with the aforementioned package, in order to allow placing a logo.

An example PDF can be viewed here: [example/letter_template.pdf](other_file.md)

## Prerequisites

The komaletter package is available from CRAN, so a simple install will suffice:

```r
install.packages("komaletter")
```

After this, the new KOMAletter template can be selected in R.

## Usage

Simply modify the contents and then "knit"" the document in R, as usual.


## References

* `komaletter` R package: https://github.com/rnuske/komaletter
* Learn more about KOMA script: https://www.komascript.de
