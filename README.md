<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PDF Viewer Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
        }
        .container {
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            max-width: 800px;
            margin: auto;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
        }
        iframe {
            width: 100%;
            height: 500px;
            border: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>View Your PDFs</h2>
        <p>Read the PDF files directly below.</p>
        <iframe src="your-file1.pdf"></iframe>
        <iframe src="your-file2.pdf"></iframe>
    </div>
</body>
</html>
