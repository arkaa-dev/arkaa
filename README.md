# arkaa<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
  <h1>Selamat Datang di Website Saya</h1>
</p>
</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Demo Kode & Preview</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #1e1e1e;
            color: #dcdcdc;
            padding: 20px;
        }

        h1, h2 {
            text-align: center;
            color: #61dafb;
        }

        pre {
            background-color: #2d2d2d;
            padding: 15px;
            border-radius: 8px;
            overflow-x: auto;
            white-space: pre-wrap;
            word-wrap: break-word;
            box-shadow: 0 4px 8px rgba(0,0,0,0.5);
        }

        code {
            font-family: 'Courier New', Courier, monospace;
            color: #f8f8f2;
        }

        .tag { color: #ff79c6; }
        .attr { color: #50fa7b; }
        .value { color: #f1fa8c; }
        .comment { color: #6272a4; font-style: italic; }

        button {
            display: block;
            margin: 10px auto 20px auto;
            padding: 10px 20px;
            font-size: 16px;
            background-color: #61dafb;
            border: none;
            border-radius: 5px;
            color: #1e1e1e;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #21a1f1;
        }

        iframe {
            display: block;
            width: 100%;
            height: 400px;
            border: 2px solid #61dafb;
            border-radius: 8px;
            margin-top: 20px;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.9em;
            color: #888;
        }
    </style>
</head>
<body>
    <h1>Demo: Kode HTML + CSS + Preview</h1>
    <h2>Kode:</h2>
    <pre><code id="codeBlock">
<span class="comment">&lt;!-- Contoh Website Portofolio --&gt;</span>
<span class="tag">&lt;!DOCTYPE html&gt;</span>
<span class="tag">&lt;html</span> <span class="attr">lang=</span><span class="value">"id"</span><span class="tag">&gt;</span>
<span class="tag">&lt;head&gt;</span>
    <span class="tag">&lt;meta</span> <span class="attr">charset=</span><span class="value">"UTF-8"</span><span class="tag">&gt;</span>
    <span class="tag">&lt;title&gt;</span>Portofolio Saya<span class="tag">&lt;/title&gt;</span>
    <span class="tag">&lt;style&gt;</span>
        body {
            background: <span class="value">linear-gradient(135deg, #00c6ff, #0072ff)</span>;
            color: <span class="value">#fff</span>;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 50px;
        }
        h1 {
            font-size: 3em;
        }
        p {
            font-size: 1.2em;
        }
    <span class="tag">&lt;/style&gt;</span>
<span class="tag">&lt;/head&gt;</span>
<span class="tag">&lt;body&gt;</span>
    <span class="tag">&lt;h1&gt;</span>Halo, Saya Arkan<span class="tag">&lt;/h1&gt;</span>
    <span class="tag">&lt;p&gt;</span>Ini adalah website portofolio saya di GitHub Pages<span class="tag">&lt;/p&gt;</span>
<span class="tag">&lt;/body&gt;</span>
<span class="tag">&lt;/html&gt;</span>
    </code></pre>
    <button onclick="copyCode()">📋 Copy Code</button>

    <h2>Preview Website:</h2>
    <iframe srcdoc="
        <!DOCTYPE html>
        <html lang='id'>
        <head>
            <meta charset='UTF-8'>
            <meta name='viewport' content='width=device-width, initial-scale=1.0'>
            <title>Portofolio Saya</title>
            <style>
                body {
                    background: linear-gradient(135deg, #00c6ff, #0072ff);
                    color: #fff;
                    font-family: Arial, sans-serif;
                    text-align: center;
                    margin: 0;
                    padding: 50px;
                }
                h1 {
                    font-size: 3em;
                }
                p {
                    font-size: 1.2em;
                }
            </style>
        </head>
        <body>
            <h1>Halo, Saya Arkan</h1>
            <p>Ini adalah website portofolio saya di GitHub Pages</p>
        </body>
        </html>
    "></iframe>

    <footer>&copy; 2025 Arkan. Dibuat dengan ❤️ dan GitHub Pages</footer>

    <script>
        function copyCode() {
            const code = document.getElementById('codeBlock').innerText;
            navigator.clipboard.writeText(code).then(() => {
                alert('✅ Kode berhasil disalin!');
            }, () => {
                alert('❌ Gagal menyalin kode.');
            });
        }
    </script>
</body>
</html>
