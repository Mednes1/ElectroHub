# ElectroHub
Powerful, lightweight vacuum for spotless floors and air
/* إعدادات عامة */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f9;
}

header {
    text-align: center;
    background: #0074d9;
    color: white;
    padding: 20px;
}

header .logo img {
    width: 100px;
    margin-bottom: 10px;
}

header h1 {
    font-size: 2rem;
}

header p {
    font-size: 1.2rem;
    margin-top: 10px;
}

/* قسم المنتج */
.product-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    padding: 20px;
}

.product-section .product-image {
    max-width: 300px;
    margin: 20px;
    border-radius: 10px;
}

.product-section .features {
    max-width: 400px;
    margin: 20px;
}

.product-section .features h2 {
    font-size: 1.8rem;
    color: #0074d9;
}

.product-section .features ul {
    list-style: none;
    padding: 0;
}

.product-section .features ul li {
    background: url('check-icon.png') no-repeat left center;
    background-size: 20px;
    padding-left: 30px;
    margin-bottom: 10px;
}

/* قسم الحث على الشراء */
.cta-section {
    text-align: center;
    padding: 20px;
    background: #ff851b;
    color: white;
}

.cta-section h2 {
    font-size: 1.8rem;
}

.cta-section p {
    font-size: 1.2rem;
    margin: 10px 0;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background: #0074d9;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.2rem;
    margin-top: 10px;
}

.cta-button:hover {
    background: #005bb5;
}

/* الفوتر */
footer {
    text-align: center;
    padding: 10px;
    background: #333;
    color: white;
    margin-top: 20px;
}
