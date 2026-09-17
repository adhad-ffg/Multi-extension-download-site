This is a simple page where you can download sample files with various extensions.  
Clicking each button downloads a file in the corresponding format (containing the text "sample").

## How to Use
Click any button to download the file in that format.


```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
</head>
<body style="background-color: #ffffff; color: #000000; font-family: 'Courier New', Courier, monospace; text-align: center; margin-top: 50px;">

    <h1>Multi extension download site</h1>
    <hr style="width: 50%; border: 1px solid #000000;">
    <br>

    <!-- HTML -->
    <a href="data:text/html;charset=utf-8,sample" download="sample.html">
        <button style="background-color: #ffffff; color: #000000; border: 2px solid #000000; padding: 10px 20px; margin: 5px; cursor: pointer; font-family: monospace;">.html download</button>
    </a>
    <br>

    <!-- CSS -->
    <a href="data:text/css;charset=utf-8,sample" download="sample.css">
        <button style="background-color: #ffffff; color: #000000; border: 2px solid #000000; padding: 10px 20px; margin: 5px; cursor: pointer; font-family: monospace;">.css download</button>
    </a>
    <br>

    <!-- JS -->
    <a href="data:text/javascript;charset=utf-8,sample" download="sample.js">
        <button style="background-color: #ffffff; color: #000000; border: 2px solid #000000; padding: 10px 20px; margin: 5px; cursor: pointer; font-family: monospace;">.js ダウンロード</button>
    </a>
    <br>

    <!-- TXT -->
    <a href="data:text/plain;charset=utf-8,sample" download="sample.txt">
        <button style="background-color: #ffffff; color: #000000; border: 2px solid #000000; padding: 10px 20px; margin: 5px; cursor: pointer; font-family: monospace;">.txt download</button>
    </a>
    <br>

    <!-- JSON -->
    <a href="data:application/json;charset=utf-8,sample" download="sample.json">
        <button style="background-color: #ffffff; color: #000000; border: 2px solid #000000; padding: 10px 20px; margin: 5px; cursor: pointer; font-family: monospace;">.json download</button>
    </a>
    <br>

    <!-- XML -->
    <a href="data:application/xml;charset=utf-8,sample" download="sample.xml">
        <button style="background-color: #ffffff; color: #000000; border: 2px solid #000000; padding: 10px 20px; margin: 5px; cursor: pointer; font-family: monospace;">.xml download</button>
    </a>
    <br>

    <!-- CSV -->
    <a href="data:text/csv;charset=utf-8,sample" download="sample.csv">
        <button style="background-color: #ffffff; color: #000000; border: 2px solid #000000; padding: 10px 20px; margin: 5px; cursor: pointer; font-family: monospace;">.csv download</button>
    </a>
    <br>

    <!-- MD -->
    <a href="data:text/markdown;charset=utf-8,sample" download="sample.md">
        <button style="background-color: #ffffff; color: #000000; border: 2px solid #000000; padding: 10px 20px; margin: 5px; cursor: pointer; font-family: monospace;">.md download</button>
    </a>
    <br>

</body>
</html>
