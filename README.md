# PDFextract
Extract source code urls from a PDF file.
# Demo
![alt text][logo]

[logo]: https://github.com/mlatsjsu/PDFextract/blob/master/demo.gif

# Setup
- The application uses xpdf-tools so make sure to download the command line tools before getting started from here: http://www.xpdfreader.com/download.html
- The application requires that you have a pdfs/ directory in the app. The app also automatically creates the folder for you.

# Quickstart
- Clone the repo and run go build.
- To run: ./PDFExtract -url https://arxiv.org/pdf/2005.14187v1.pdf -download true or go run main.go ...

# For people who don't want to install Go or don't want build from scratch.
- Run the binary in the repo (./PDFExtract with the appropriate command line args)
- Make sure to install xpdfreader command tools.

# Future Direction
- To add recommendation support.
- Ability to download code
- Web interface
- Docker support
