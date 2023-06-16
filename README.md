# yun-hw.github.io
#<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Company</title>
 
    <!-- 반응형 웹 만들기 -->
    <!-- 1. 모바일용 css -->
    <link rel="stylesheet" href="./company_mobile.css" media="(max-width:600px)">
 
    <!-- 2. 데스크탑용 외부 스타일시트 적용 -->
    <link rel="stylesheet" href="./company.css" media="(min-width:600px)">
</head>
<body>
    
    <div id="page">
 
        <header>
            <div id="logo">
                <img src="./imgs_company/logo.png" alt="Logo">
            </div>
 
            <div id="top_menu">
                <a href="#">HOME</a> | 
                <a href="#">NOTICE</a> |
                <a href="#">LOGIN</a> |
                <a href="#">JOIN</a>
            </div>
 
            <nav>
                <ul>
                    <li><a href="#">COMPANY</a></li>
                    <li><a href="#">PRODUCT</a></li>
                    <li><a href="#">CUSTOMER</a></li>
                    <li><a href="#">SERVICE</a></li>
                    <li><a href="#">RECRUIT</a></li>
                </ul>
            </nav>
 
        </header>
 
        <article id="content">
            <section id="main">
                <img src="./imgs_company/main_img.png" alt="main img">
            </section>
            <section>
                <ul id="banner">
                    <li><a href="#"><img src="./imgs_company/banner1.png" alt="banner1"></a></li>
                    <li><a href="#"><img src="./imgs_company/banner2.png" alt="banner2"></a></li>
                </ul>
 
            </section>
 
        </article>
 
        <footer>
            <img src="./imgs_company/address.png" alt="address">
        </footer>
 
    </div>
</body>
</html>
