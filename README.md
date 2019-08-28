# PDF to Excel Converter
Based on https://github.com/eadgyo/Extract-PDF-Excel
Convert pdf to excel. Only the text will be extracted.

## 1) Usage - io.github.perplexhub.pdf2excel.Pdf2Excel

String pdfPassword = <......>;<br>
InputStream pdfInputStream = <......>;<br>
ByteArrayOutputStream excelOutputStream ;<br>

// Convert PDF without password protected<br>
excelOutputStream = Pdf2Excel.convert(pdfInputStream);

// Convert PDF with password protected<br>
excelOutputStream = Pdf2Excel.convert(pdfInputStream, pdfPassword);

## 2) Maven

https://oss.sonatype.org/#nexus-search;gav~io.github.perplexhub~pdf-to-excel~~~
