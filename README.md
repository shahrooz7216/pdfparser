# PdfParser #

This Fork of Smalot PdfParser is used for those who just use this package to parse a pdf and get its pages count,
I have made this fork because some pds throw a memory leak error and stops the whole process, so I have commented the problematic part of code(/src/Font.php lines 140~231) that is saving every unicode character of pdf in a array named table,
Also remember that I am just using this package to parse my pdf for its integrity and getting the page count of my pdf files.

Pdf Parser, a standalone PHP library, provides various tools to extract data from a PDF file.

[![Build Status](https://travis-ci.org/smalot/pdfparser.png?branch=master)](https://travis-ci.org/smalot/pdfparser)
[![Current Version](https://poser.pugx.org/smalot/pdfparser/v/stable.png)](https://packagist.org/packages/smalot/pdfparser)
[![composer.lock](https://poser.pugx.org/smalot/pdfparser/composerlock)](https://packagist.org/packages/smalot/pdfparser)

[![Total Downloads](https://poser.pugx.org/smalot/pdfparser/downloads.png)](https://packagist.org/packages/smalot/pdfparser)
[![Monthly Downloads](https://poser.pugx.org/smalot/pdfparser/d/monthly)](https://packagist.org/packages/smalot/pdfparser)
[![Daily Downloads](https://poser.pugx.org/smalot/pdfparser/d/daily)](https://packagist.org/packages/smalot/pdfparser)

Website : [http://www.pdfparser.org](http://www.pdfparser.org/?utm_source=GitHub&utm_medium=website&utm_campaign=GitHub)

Test the API on our [demo page](http://www.pdfparser.org/demo).

This project is supported by [Actualys](http://www.actualys.com).

## Features ##

Features included :

- Load/parse objects and headers
- Extract meta data (author, description, ...)
- Extract text from ordered pages
- Support of compressed pdf
- Support of MAC OS Roman charset encoding
- Handling of hexa and octal encoding in text sections
- PSR-0 compliant ([autoloader](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md))
- PSR-1 compliant ([code styling](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md))

Currently, secured documents are not supported.

This Library is still under active development.
As a result, users must expect BC breaks when using the master version.

## Documentation ##

[Read the documentation on website](http://www.pdfparser.org/documentation?utm_source=GitHub&utm_medium=documentation&utm_campaign=GitHub).

Original PDF References files can be downloaded from this url : http://www.adobe.com/devnet/pdf/pdf_reference_archive.html


## License ##

This library is under the [LGPLv3 license](https://github.com/smalot/pdfparser/blob/master/LICENSE.txt).

