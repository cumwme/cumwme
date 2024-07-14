<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เว็บไซต์ตัวอย่าง</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>โดจินแปลไทย</h1>
    </header>
    <main>
        <section>
            <h2>ใหม่ล่าสุด</h2>
            <div class="gallery">
                <div class="item">
                    <img src="path/to/image1.jpg" alt="Image 1">
                    <p>Description 1</p>
                </div>
                <div class="item">
                    <img src="path/to/image2.jpg" alt="Image 2">
                    <p>Description 2</p>
                </div>
                <!-- เพิ่มไอเท็มตามที่ต้องการ -->
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 เว็บไซต์ตัวอย่าง</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}

.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 1em;
}

.item {
    margin: 1em;
    background-color: #fff;
    padding: 1em;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.item img {
    max-width: 100%;
    height: auto;
}

footer {
    text-align: center;
    padding: 1em 0;
    background-color: #333;
    color: #fff;
}

