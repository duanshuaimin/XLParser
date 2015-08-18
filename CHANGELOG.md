# Changelog

## 1.1.2

Reference implementation of the Excel grammar published in the upcoming paper "A Grammar for Spreadsheet Formulas Evaluated on Two Large Datasets" by E. Aivaloglou, D. Hoepelman and F. Hermans.

Fixed [#1](https://github.com/PerfectXL/XLParser/issues/1), [#2](https://github.com/PerfectXL/XLParser/issues/2), [#4](https://github.com/PerfectXL/XLParser/issues/4).

* Added a web demo in app/XLParser.Web which generates parse tree images
* All UDF's now use the same nonterminal
* Non-Prefixed UDFs can now be part of a reference expression
* IF and CHOOSE functions can now be part of a reference expression
* Reference functions INDEX,OFFSET and INDIRECT can no longer have a prefix
* Operator precedence for reference operators (: , and intersection) is now correct
* Fixed printing of reference operators

## 1.0.0

First public release.
Corresponds to pre-print/reviewer version of the paper