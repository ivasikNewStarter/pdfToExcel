# PDF to Excel Converter
Based on https://github.com/eadgyo/Extract-PDF-Excel
Convert pdf to excel. Only the text will be extracted.

## 1) Usage

InputStream pdfFileInputStream = ......;
ByteArrayOutputStream excelFileByteArrayOutputStream out = io.github.perplexhub.pdf2excel.Pdf2Excel.convert(pdfFileInputStream);

String password = ......;
ByteArrayOutputStream excelFileByteArrayOutputStream out = io.github.perplexhub.pdf2excel.Pdf2Excel.convert(pdfFileInputStream, password);

## 2) Maven

https://oss.sonatype.org/#nexus-search;gav~io.github.perplexhub~pdf-to-excel~~~
