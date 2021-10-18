# SIE for Visual Studio Code
The [SIE extension](https://marketplace.visualstudio.com/items?itemName=SimonSegerblomRex.vscode-sie)
adds language support for [SIE](https://sie.se/in-english/)
to [Visual Studio Code](https://code.visualstudio.com/).

## Quick start
1. Install the [SIE extension](https://marketplace.visualstudio.com/items?itemName=SimonSegerblomRex.vscode-sie)
to [Visual Studio Code](https://code.visualstudio.com/).
2. Open or create a `*.se`, `*.si`, or `*.sie` file.

## Features
SIE is the standard file format for Swedish accounting data.
All proper Swedish accounting software support exporting and importing
SIE 4 files.

The primary focus of this extension is to provide proper settings
and syntax highlighting for SIE 4.

SIE 4 files (with extensions `*.si`, and `*.se`) will be
opened and saved with the correct encoding (CP437).
This will make sure that characters like `å`, `ä`, and `ö` get
decoded and encoded properly.

The only feature for SIE 5 at the moment is to identify `*.sie`
files as XML.

## Contribution
Contributions are welcome:
* Create an [issue](https://github.com/SimonSegerblomRex/vscode-sie/issues)
  for any bug or feature request.
* Fork the repo and create a pull request to make code contributions.

Use the [forum](https://github.com/SimonSegerblomRex/vscode-sie/discussions)
to discuss SIE related topics.

## References
* [SIE 4 specification in English](https://sie.se/wp-content/uploads/2020/05/SIE_filformat_ver_4B_ENGLISH.pdf)
* [SIE 4 specification in Swedish](https://sie.se/wp-content/uploads/2020/05/SIE_filformat_ver_4B_080930.pdf)
* [SIE 5 specification in Swedish](https://sie.se/wp-content/uploads/2020/08/SIE-5-rev-161209-konsoliderad.pdf)
