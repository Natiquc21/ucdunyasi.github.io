<!DOCTYPE html>
<html lang="az">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PUBG Mobile UC Satışı</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0e1a2b;
            color: #fff;
        }
        header {
            background: linear-gradient(90deg, #1a73e8, #ff5722);
            color: white;
            text-align: center;
            padding: 2rem 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }
        header h1 {
            margin: 0;
            font-size: 3rem;
            letter-spacing: 1px;
        }
        header p {
            margin-top: 0.5rem;
            font-size: 1.2rem;
            color: #ffecd1;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }
        .product {
            background: #1e2a3a;
            border: 1px solid #3b4a5c;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
            max-width: 300px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .product:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.6);
        }
        .product img {
            width: 100%;
            height: auto;
            border-bottom: 1px solid #3b4a5c;
        }
        .product h3 {
            margin: 1rem 0 0.5rem;
            font-size: 1.5rem;
        }
        .product p {
            font-size: 1.1rem;
            color: #cfd8dc;
        }
        .product button {
            background: linear-gradient(90deg, #1a73e8, #ff5722);
            color: white;
            border: none;
            padding: 0.75rem 1.5rem;
            margin: 1rem 0;
            border-radius: 20px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: bold;
            transition: background 0.3s;
        }
        .product button:hover {
            background: linear-gradient(90deg, #ff5722, #1a73e8);
        }
        .contact {
            text-align: center;
            margin: 2rem 0;
            padding: 1rem;
            background: #1e2a3a;
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
        }
        .contact h2 {
            margin-bottom: 1rem;
        }
        .contact p {
            font-size: 1.2rem;
            margin: 0.5rem 0;
        }
        .contact a {
            color: #1a73e8;
            text-decoration: none;
            font-size: 1.2rem;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background: #1a1a1a;
            color: #cfd8dc;
            margin-top: 2rem;
        }
        .modal {
            display: none;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: #1e2a3a;
            color: white;
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
            z-index: 1000;
        }
        .modal.active {
            display: block;
        }
        .modal h2 {
            margin-top: 0;
        }
        .modal button {
            background: linear-gradient(90deg, #1a73e8, #ff5722);
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 12px;
            cursor: pointer;
        }
    </style>
    <script>
        function showModal(productName) {
            const modal = document.getElementById('modal');
            const productInfo = document.getElementById('product-info');
            productInfo.textContent = productName + ' üçün seçilmiş kart kodu: 4169 7388 3047 9519';
            modal.classList.add('active');
        }

        function closeModal() {
            const modal = document.getElementById('modal');
            modal.classList.remove('active');
        }

        function proceedToWhatsApp() {
            const whatsappUrl = "https://wa.me/994504556067?text=Ödənişin ekran görüntüsünü göndərin";
            window.open(whatsappUrl, '_blank');
        }
    </script>
</head>
<body>
    <header>
        <h1>PUBG Mobile UC Satışı</h1>
        <p>Saytımıza xoş gəlmisiniz! PUBG dünyasında özünüzü fərqləndirin və oyununuzu növbəti səviyyəyə daşıyın.</p>
        <p>Burada ən sərfəli qiymətlərlə UC əldə edə bilərsiniz və biz sizə sürətli və etibarlı xidmət təqdim edirik.</p>
    </header>
    <div class="container">
        <!-- Məhsul 1 -->
        <div class="product">
            <img src="https://via.placeholder.com/300x150" alt="UC Paketi">
            <h3>60 UC</h3>
            <p>Qiymət: 1.50 AZN</p>
            <button onclick="showModal('60 UC')">Al</button>
        </div>
        <!-- Məhsul 2 -->
        <div class="product">
            <img src="https://via.placeholder.com/300x150" alt="UC Paketi">
            <h3>300 UC</h3>
            <p>Qiymət: 7.50 AZN</p>
            <button onclick="showModal('300 UC')">Al</button>
        </div>
        <!-- Məhsul 3 -->
        <div class="product">
            <img src="https://via.placeholder.com/300x150" alt="UC Paketi">
            <h3>600 UC</h3>
            <p>Qiymət: 15.00 AZN</p>
            <button onclick="showModal('600 UC')">Al</button>
        </div>
    </div>
    <div class="contact">
        <h2>Əlaqə Saxlayın</h2>
        <p>Bizə hər zaman WhatsApp üzərindən yazaraq suallarınızı verə bilərsiniz:</p>
        <p><a href="https://wa.me/994504556067">+994 50 455 60 67</a></p>
        <p>Həmçinin xüsusi sifarişlər və endirim təkliflərimiz barədə məlumat almaq üçün bizimlə əlaqə saxlayın.</p>
    </div>
    <div id="modal" class="modal">
        <h2>Sifariş məlumatları</h2>
        <p id="product-info"></p>
        <button onclick="closeModal()">Bağla</button>
        <button onclick="proceedToWhatsApp()">WhatsApp ilə davam et</button>
    </div>
    <footer>
        <p>&copy; 2025 PUBG Mobile UC Satışı. Sayt düzəldi: Natiq. Keyfiyyət və məmnuniyyət zəmanəti ilə xidmətinizdəyik. Bizimlə oyun təcrübənizi daha maraqlı edin!</p>
    </footer>
</body>
</html>
