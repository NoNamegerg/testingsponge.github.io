<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, shrink-to-fit=no">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&amp;family=Noto+Sans:wght@100;200;300;400;500;600;700;800;900&amp;display=swap" rel="stylesheet">
    <meta property="og:title" content="Sponge Store">
    <meta property="og:site_name" content="Sponge Store">
    <meta property="og:url" content="https://catbrawl.github.io/store/">
    <meta property="og:description" content="Новый способ покупать внутриигровые товары для себя и друзей по Sponge ID.">
    <meta property="og:image" content="images/delta.png">
    <meta name="description" content="Новый способ покупать внутриигровые товары для себя и друзей по Sponge ID.">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/style_1.css">
    <script src="js/jquery.js"></script>
    <link rel="icon" href="favicon.ico">
    <script src="js/script.js"></script>
    <title>Sponge Store</title>
</head>
<body>
    <div class="header">
        <img src="images/delta.png" class="imglogo">
        <div class="wrapper__menu">
            <div class="menu">
                <span></span>
            </div>
        </div>
        <nav class="center">
            <ul class="menu__nav">
                <li><a href="https://t.me/spongestars" class="menu__link">Telegram канал</a></li>
                <li><a href="https://t.me/spongestars" class="menu__link">Поддержка</a></li>
            </ul>
        </nav>
    </div>
    <div id="main">
        <div class="sidebar">
            <div class="games-sidebar" id="div-scroll">
                <div class="game-sidebar bs">
                    <div class="icon"><img src="images/delta.png" class="icon-img"></div>
                    <div class="text">Скачать игру</div>
                </div>
                <div class="game-sidebar bsb">
                    <div class="icon"><img src="images/telegram.png" class="icon-img"></div>
                    <div class="text">ТГ-Канал</div>
                </div>
                <div class="game-sidebar rgb">
                    <div class="icon"><img src="images/RGB.png" class="icon-img"></div>
                    <div class="text">Контакт Создателя</div>
                </div>
            </div>
        </div>
        <div class="roots">
            <div class="page-container">
                <div class="img_blockfi">
                    <span class="img_header">
                        <picture>
                            <source media="(max-width: 900px)" srcset="images/hero-mobile.webp">
                            <source media="(min-width: 901px)" srcset="images/hero-desktop.webp">
                            <img class="img_blockfi1" alt="Error" src="images/hero-desktop.webp">
                        </picture>
                    </span>
                </div>
                <div class="game_content">
                    <div class="products">
                        <div class="tovari_glav"></div>
                        <div class="tovar1">
                            <div class="tovar1img">
                                <img class="imgstictovar1" src="images/bp_plus.webp">
                                <img class="tovar2style" src="images/bg_bp_plus.webp">
                            </div>
                            <div class="cart_block_full">
                                <div class="cart_block_text">
                                    <div class="cart_block_padding_full">
                                        <div class="cart_blocktexttovar1">
                                            <div class="textcartblock">Premium Sponge VIP</div>
                                            <div class="descriptioncartblock">Подписка Premium в Sponge Stars</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="btn_cart_div">
                                <div class="btn_cart_tovar1_div">
                                    <a href="https://t.me/ivmaxpob" class="btn_cart_tovar1 btn_cart_tovars2 cookie">
                                        <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="BuyButton_Icon__rNCUh">
                                            <path d="M5 1.66675L2.5 5.00008V16.6667C2.5 17.1088 2.67559 17.5327 2.98816 17.8453C3.30072 18.1578 3.72464 18.3334 4.16667 18.3334H15.8333C16.2754 18.3334 16.6993 18.1578 17.0118 17.8453C17.3244 17.5327 17.5 17.1088 17.5 16.6667V5.00008L15 1.66675H5Z" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                            <path d="M2.5 5H17.5" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                            <path d="M13.3334 8.33325C13.3334 9.21731 12.9822 10.0652 12.357 10.6903C11.7319 11.3154 10.8841 11.6666 10 11.6666C9.11597 11.6666 8.26812 11.3154 7.643 10.6903C7.01788 10.0652 6.66669 9.21731 6.66669 8.33325" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                        </svg>
                                        <div class="text_btn_cart_tovar1">199 ₽</div>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="other_products">
            <div class="textvibor_block">
                <div class="textvibor">
                    <button id="vseButton" class="textviborvse">Все</button>
                    <script src="js/script_1.js"></script>
                </div>
            </div>
            <div class="block_cart_more">
                <div class="block_cart_full">
                    <div class="tovar" id="classic-vip">
                        <div class="tovarimg">
                            <div class="lent">
                                ВЫГОДА: +50 КРИСТАЛОВ
                            </div>
                            <img class="badge" src="images/badge.webp">
                            <img class="tovarimg1" src="images/yellowstick.webp">
                            <img class="tovar1stylecart" src="images/bg_bp_plus.webp">
                        </div>
                        <div class="tovarunder">
                            <div class="tovarname">Classic VIP</div>
                            <div class="descriptiontovar">Подписка Classic VIP</div>
                            <a href="https://t.me/ivmaxpob" class="btn_cart_tovar2 cookie">
                                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="BuyButton_Icon__rNCUh">
                                    <path d="M5 1.66675L2.5 5.00008V16.6667C2.5 17.1088 2.67559 17.5327 2.98816 17.8453C3.30072 18.1578 3.72464 18.3334 4.16667 18.3334H15.8333C16.2754 18.3334 16.6993 18.1578 17.0118 17.8453C17.3244 17.5327 17.5 17.1088 17.5 16.6667V5.00008L15 1.66675H5Z" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M2.5 5H17.5" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M13.3334 8.33325C13.3334 9.21731 12.9822 10.0652 12.357 10.6903C11.7319 11.3154 10.8841 11.6666 10 11.6666C9.11597 11.6666 8.26812 11.3154 7.643 10.6903C7.01788 10.0652 6.66669 9.21731 6.66669 8.33325" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                </svg>
                                <div class="text_btn_cart_tovar1">109 ₽</div>
                            </a>
                        </div>
                    </div>
                    <div class="tovar" id="sponge-ultra">
                        <div class="tovarimg">
                            <img class="badge" src="images/badge.webp">
                            <img class="tovarimg1" src="images/bp_plus.webp">
                            <img class="tovar1stylecart" src="images/bg_bp_plus.webp">
                        </div>
                        <div class="tovarunder">
                            <div class="tovarname">Sponge ULTRA</div>
                            <div class="descriptiontovar">Мега выгодная подписка Sponge Stars!</div>
                            <a href="https://t.me/ivmaxpob" class="btn_cart_tovar2 cookie">
                                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="BuyButton_Icon__rNCUh">
                                    <path d="M5 1.66675L2.5 5.00008V16.6667C2.5 17.1088 2.67559 17.5327 2.98816 17.8453C3.30072 18.1578 3.72464 18.3334 4.16667 18.3334H15.8333C16.2754 18.3334 16.6993 18.1578 17.0118 17.8453C17.3244 17.5327 17.5 17.1088 17.5 16.6667V5.00008L15 1.66675H5Z" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M2.5 5H17.5" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M13.3334 8.33325C13.3334 9.21731 12.9822 10.0652 12.357 10.6903C11.7319 11.3154 10.8841 11.6666 10 11.6666C9.11597 11.6666 8.26812 11.3154 7.643 10.6903C7.01788 10.0652 6.66669 9.21731 6.66669 8.33325" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                </svg>
                                <div class="text_btn_cart_tovar1">249 ₽</div>
                            </a>
                        </div>
                    </div>
                    <div class="tovar" id="sponge-lite">
                        <div class="tovarimg">
                            <img class="badge" src="images/badge.webp">
                            <img class="tovarimg1" src="images/yellowstick.webp">
                            <img class="tovar1stylecart" src="images/bg_bp_plus.webp">
                        </div>
                        <div class="tovarunder">
                            <div class="tovarname">Sponge Lite</div>
                            <div class="descriptiontovar">Дешёвая подписка</div>
                            <a href="https://t.me/ivmaxpob" class="btn_cart_tovar2 cookie">
                                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="BuyButton_Icon__rNCUh">
                                    <path d="M5 1.66675L2.5 5.00008V16.6667C2.5 17.1088 2.67559 17.5327 2.98816 17.8453C3.30072 18.1578 3.72464 18.3334 4.16667 18.3334H15.8333C16.2754 18.3334 16.6993 18.1578 17.0118 17.8453C17.3244 17.5327 17.5 17.1088 17.5 16.6667V5.00008L15 1.66675H5Z" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M2.5 5H17.5" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M13.3334 8.33325C13.3334 9.21731 12.9822 10.0652 12.357 10.6903C11.7319 11.3154 10.8841 11.6666 10 11.6666C9.11597 11.6666 8.26812 11.3154 7.643 10.6903C7.01788 10.0652 6.66669 9.21731 6.66669 8.33325" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                </svg>
                                <div class="text_btn_cart_tovar1">69 ₽</div>
                            </a>
                        </div>
                    </div>
                    <div class="tovar" id="gems-2000">
                        <div class="tovarimg">
                            <img class="badge" src="images/badge.webp">
                            <img class="tovarimg1" src="images/chest.webp">
                            <img class="tovar1stylecart" src="images/bg.webp">
                        </div>
                        <div class="tovarunder">
                            <div class="tovarname">2000 кристаллов</div>
                            <div class="sss" style="display: flex;">
                                <img class="bs_icon_gem1" src="images/bs_icon_gem.webp">
                                <div class="descriptiontovar">2000</div>
                            </div>
                            <a href="https://t.me/ivmaxpob" class="btn_cart_tovar2 cookie">
                                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="BuyButton_Icon__rNCUh">
                                    <path d="M5 1.66675L2.5 5.00008V16.6667C2.5 17.1088 2.67559 17.5327 2.98816 17.8453C3.30072 18.1578 3.72464 18.3334 4.16667 18.3334H15.8333C16.2754 18.3334 16.6993 18.1578 17.0118 17.8453C17.3244 17.5327 17.5 17.1088 17.5 16.6667V5.00008L15 1.66675H5Z" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M2.5 5H17.5" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M13.3334 8.33325C13.3334 9.21731 12.9822 10.0652 12.357 10.6903C11.7319 11.3154 10.8841 11.6666 10 11.6666C9.11597 11.6666 8.26812 11.3154 7.643 10.6903C7.01788 10.0652 6.66669 9.21731 6.66669 8.33325" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                </svg>
                                <div class="text_btn_cart_tovar1">599 ₽</div>
                            </a>
                        </div>
                    </div>
                    <div class="tovar" id="gems-950">
                        <div class="tovarimg">
                            <img class="badge" src="images/badge.webp">
                            <img class="tovarimg1" src="images/gems1.webp">
                            <img class="tovar1stylecart" src="images/bg.webp">
                        </div>
                        <div class="tovarunder">
                            <div class="tovarname">950 кристаллов</div>
                            <div class="sss" style="display: flex;">
                                <img class="bs_icon_gem1" src="images/bs_icon_gem.webp">
                                <div class="descriptiontovar">950</div>
                            </div>
                            <a href="https://t.me/ivmaxpob" class="btn_cart_tovar2 cookie">
                                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="BuyButton_Icon__rNCUh">
                                    <path d="M5 1.66675L2.5 5.00008V16.6667C2.5 17.1088 2.67559 17.5327 2.98816 17.8453C3.30072 18.1578 3.72464 18.3334 4.16667 18.3334H15.8333C16.2754 18.3334 16.6993 18.1578 17.0118 17.8453C17.3244 17.5327 17.5 17.1088 17.5 16.6667V5.00008L15 1.66675H5Z" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M2.5 5H17.5" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M13.3334 8.33325C13.3334 9.21731 12.9822 10.0652 12.357 10.6903C11.7319 11.3154 10.8841 11.6666 10 11.6666C9.11597 11.6666 8.26812 11.3154 7.643 10.6903C7.01788 10.0652 6.66669 9.21731 6.66669 8.33325" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                </svg>
                                <div class="text_btn_cart_tovar1">299 ₽</div>
                            </a>
                        </div>
                    </div>
                    <div class="tovar" id="gems-360">
                        <div class="tovarimg">
                            <img class="badge" src="images/badge.webp">
                            <img class="tovarimg1" src="images/gems2.webp">
                            <img class="tovar1stylecart" src="images/bg.webp">
                        </div>
                        <div class="tovarunder">
                            <div class="tovarname">360 кристаллов</div>
                            <div class="sss" style="display: flex;">
                                <img class="bs_icon_gem1" src="images/bs_icon_gem.webp">
                                <div class="descriptiontovar">360</div>
                            </div>
                            <a href="https://t.me/ivmaxpob" class="btn_cart_tovar2 cookie">
                                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="BuyButton_Icon__rNCUh">
                                    <path d="M5 1.66675L2.5 5.00008V16.6667C2.5 17.1088 2.67559 17.5327 2.98816 17.8453C3.30072 18.1578 3.72464 18.3334 4.16667 18.3334H15.8333C16.2754 18.3334 16.6993 18.1578 17.0118 17.8453C17.3244 17.5327 17.5 17.1088 17.5 16.6667V5.00008L15 1.66675H5Z" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M2.5 5H17.5" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M13.3334 8.33325C13.3334 9.21731 12.9822 10.0652 12.357 10.6903C11.7319 11.3154 10.8841 11.6666 10 11.6666C9.11597 11.6666 8.26812 11.3154 7.643 10.6903C7.01788 10.0652 6.66669 9.21731 6.66669 8.33325" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                </svg>
                                <div class="text_btn_cart_tovar1">189 ₽</div>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="tovar" id="gems-170">
                <div class="tovarimg">
                    <img class="badge" src="images/badge.webp">
                    <img class="tovarimg1" src="images/gems3.webp">
                    <img class="tovar1stylecart" src="images/bg.webp">
                </div>
                <div class="tovarunder">
                    <div class="tovarname">170 кристаллов</div>
                    <div class="sss" style="display: flex;">
                        <img class="bs_icon_gem1" src="images/bs_icon_gem.webp">
                        <div class="descriptiontovar">170</div>
                    </div>
                    <a href="https://t.me/ivmaxpob" class="btn_cart_tovar2 cookie">
                        <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="BuyButton_Icon__rNCUh">
                            <path d="M5 1.66675L2.5 5.00008V16.6667C2.5 17.1088 2.67559 17.5327 2.98816 17.8453C3.30072 18.1578 3.72464 18.3334 4.16667 18.3334H15.8333C16.2754 18.3334 16.6993 18.1578 17.0118 17.8453C17.3244 17.5327 17.5 17.1088 17.5 16.6667V5.00008L15 1.66675H5Z" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                            <path d="M2.5 5H17.5" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                            <path d="M13.3334 8.33325C13.3334 9.21731 12.9822 10.0652 12.357 10.6903C11.7319 11.3154 10.8841 11.6666 10 11.6666C9.11597 11.6666 8.26812 11.3154 7.643 10.6903C7.01788 10.0652 6.66669 9.21731 6.66669 8.33325" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                        </svg>
                        <div class="text_btn_cart_tovar1">110 ₽</div>
                    </a>
                </div>
            </div>
        </div>
    </div>
    <div class="tovar" id="gems-80">
        <div class="tovarimg">
            <img class="badge" src="images/badge.webp">
            <img class="tovarimg1" src="images/gems4.webp">
            <img class="tovar1stylecart" src="images/badge.webp">
            <div class="tovarunder">
>
        <div class="tovarname">80 кристаллов</div>
            <div class="sss" style="display: flex;">
            <div class="descriptiontovar">80</div>
            <div class="tovarunder">
="11">
 <div class="text_btn_cart_tovar2 cookie>
                                <div class="text_btn_cart_tovar1">60 ₽</div>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            </div>
            <div class="tovar" id="gems-30">
="tovarunder">
=" class="="tovarname">30 кристаллов</div>
            <div class="sss" style="display: flex;">
                <img class="bs_icon_gem1" src="images/bs_icon_gem.webp">
                <div class="descriptiontovar">30</div>
            </div>
        </div>
    </div>
</div>
</div>
</div>
</div>
                    <a href="https://://t.me/ivmaxpob" class="btn_cart_tovar2 cookie">
                                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="BuyButton_Icon__rNCUh">
                                    <path d="="M5 1.66675L2.5 5.00008V16.6667C2.5 17.1088 2.67559 17.5327 2.98816 17.8453C3.30072 18.1578 3.72464 18.3334 4.16667 18.3334H15.8333C16.2754 18.3334 16.6993 18.1578 17.0118 17.8453C17.3244 17.5327 17.5 17.1088 17.5 16.6667V5.00008L15 1.66675H5Z" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M2.5 5H17.5" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                    <path d="M13.3334 8.33325C13.3334 9.21731 12.9822 10.0652 12.357 10.6903C11.7319 11.3154 10.8841 11.6666 10 11.6666C9.11597 11.6666 8.26812 11.3154 7.643 10.6903C7.01788 10.0652 6.66669 9.21731 6.66669 8.33325" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                                </svg>
                                <div class="text_btn_cart_tovar1">24 ₽</div>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="tovar" id="test">
                <div class="tovarimg">
                    <img class="badge" src="images/badge.webp">
                    <img class="tovarimg1" src="images/gems5.webp">
                    <img class="tovar1stylecart" src="images/bg.webp">
                </div>
                <div class="tovarunder">
                    <div class="tovarname">Test</div>
                    <div class="descriptiontovar">500</div>
                    <a href="https://t.me/ivmaxpob" class="btn_cart_tovar2 cookie">
                        <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="BuyButton_Icon__rNCUh">
                            <path d="M5 1.66675L2.5 5.00008V16.6667C2.5 17.1088 2.67559 17.5327 2.98816 17.8453C3.30072 18.1578 3.72464 18.3334 4.16667 18.3334H15.8333C16.2754 18.3334 16.6667V5.00008L15 1.66675H5Z" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                            <M13.33325C13.33325 12.9822 12.33325 10.66325 11.33325 10.6903C11.7319 11.3154 10.8841 11.6666 10 11.6666C9.11597 11.6666 8.26812 11.3154 7.643 10.6903C7.01788 10.0652 6.66669 9.21731 6.66669 8.33325" stroke="white" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round"></path>
                        </svg>
                        <div class="text_btn_cart_tovar1">499 ₽</div>
                    </a>
                </div>
            </div>
        </div>
    </div>
</div>
<div class="big_block">
    <div class="osn_big_block">
        <div class="osn_bb">
            <div class="blocks">
                <img class="img_blocks" src="images/game-badge.webp">
            </div>
            <div class="ttosn">
                <div class="tto">
                    <div class="textosn">
                        <div class="nameosn">
                            <h1 class="nameosnh1">Sponge Stars в <br>Sponge Store</h1>
                        </div>
                    </div>
                    <div class="descrosn">
                        <p>В Sponge Store появились товары<br>Sponge Stars! Не пропустите наши<br>особые акции и запаситесь<br>кристаллами.</p>
                    </div>
                </div>
                <div class="ttosnimg">
                    <img class="ttimg" onclick="goToLink('https://apps.apple.com/uz/app/brawl-stars/id1229016807?l=ru&amp;platform=ipad%5C')" src="images/app-store_badge_ru.b7a32385.svg">
                    <img class="ttimg" onclick="goToLink('https://play.google.com/store/apps/details?id=com.supercell.brawlstars&amp;hl=ru&amp;gl=US&amp;pli=1')" src="images/google-play-badge_ru.webp">
                </div>
            </div>
        </div>
    </div>
</div>
<footer>
    <div class="footer_div">
        <div class="footer_text_svg">
            <h1 class="footer_h1">SPONGE STORE!!</h1>
        </div>
        <div class="footer_about">
            <h1>Руководители:</h1>
            <p>- @SpongeStars</p>
            <h1>Разработчики:</h1>
            <p>- @IvMaxPob, @Pashka435</p>
            <h1>Принимаем оплату на:</h1>
            <p>- Т-Банк, СБП</p>
        </div>
    </div>
    <div class="ooo">
        ООО "Sponge Stars" все права защищены 2024г.
    </div>
</footer>
</body>
</html>
