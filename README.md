<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Graphiluxe - Free PNGs, Fonts, Vectors & More</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #ffffff, #800000);
    }.header {
  text-align: center;
  padding: 50px 20px;
  color: white;
  background: #2d2d2d;
}

.header h1 {
  font-size: 42px;
  margin-bottom: 10px;
  letter-spacing: 2px;
}

.header p {
  font-size: 18px;
  color: #ccc;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  padding: 30px;
}

.item {
  background: white;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  overflow: hidden;
  transition: transform 0.2s ease;
}

.item:hover {
  transform: scale(1.03);
}

.item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.item .desc {
  padding: 15px;
  font-size: 16px;
  font-weight: 500;
}

.download-btn {

