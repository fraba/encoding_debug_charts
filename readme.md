# UTF-8 Encoding Debugging Chart

## Debugging Chart Mapping Windows-1252 Characters to UTF-8 Bytes to Latin-1 Characters

> The following chart shows the characters in Windows-1252 from 128 to 255 (hex 80 to FF). The Unicode code point for each character is listed and the hex values for each of the bytes in the UTF-8 encoding for the same characters. These UTF-8 bytes are also displayed as if they were Windows-1252 characters. You can use this chart to debug problems where these sequences of Latin characters occur, where only one character was expected. If you match the sequence that occurs to the sequence in the chart, and the expected value in the chart matches the value that you expected to see, then the problem is being caused by UTF-8 bytes being interpreted as Windows-1252 (or ISO 8859-1) bytes.

source: http://www.i18nqa.com/debug/utf8-debug.html
