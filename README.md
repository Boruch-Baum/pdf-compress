# pdf-compress
A command-line ghostrscipt wrapper for PDF compression, written in
python.

## Usage
```
pdf-compress TYPE INPUT-FILE OUTPUT-FILE
pdf-compress [help|version]
```
where TYPE may be:
```
  screen    - lowest-resolution
  ebook     - medium-resolution
  printer   - print optimized
  prepress  - prepress optimized
  default   - least compressed
```
## Requirements
* python version 3.10 or newer
* ghostscript

## Installation
The program is a single executable python script.

## Screencast
![screencast](screencast.gif)
