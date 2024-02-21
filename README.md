<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kiwix - Offline Access to Knowledge</title>
    <style>
        /* Add your custom CSS styles here */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .navbar {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background-color: #f0f0f0;
            padding: 20px;
        }

        .navbar-logo {
            font-size: 24px;
            font-weight: bold;
            color: #333333;
        }

        .navbar-menu {
            list-style: none;
            display: flex;
        }

        .navbar-menu li {
            margin: 0 10px;
        }

        .navbar-menu a {
            text-decoration: none;
            color: #333333;
        }

        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            height: 80vh;
            padding: 40px;
        }

        .hero-left {
            width: 50%;
        }

        .hero-right {
            width: 50%;
        }

        .hero-title {
            font-size: 48px;
            font-weight: bold;
            color: #333333;
            margin-bottom: 20px;
        }

        .hero-subtitle {
            font-size: 24px;
            color: #666666;
            margin-bottom: 40px;
        }

        .hero-button {
            display: inline-block;
            padding: 15px 25px;
            background-color: #333333;
            color: #ffffff;
            text-decoration: none;
            border-radius: 5px;
        }

        .hero-image {
            width: 100%;
            height: auto;
        }

        .section {
            padding: 60px 0;
        }

        .section-title {
            font-size: 36px;
            font-weight: bold;
            color: #333333;
            margin-bottom: 20px;
            text-align: center;
        }

        .section-subtitle {
            font-size: 18px;
            color: #666666;
            margin-bottom: 40px;
            text-align: center;
        }

        .section-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .section-content-left {
            width: 50%;
        }

        .section-content-right {
            width: 50%;
        }

        .section-content-text {
            font-size: 18px;
            color: #333333;
            line-height: 1.5;
        }

        .section-content-image {
            width: 100%;
            height: auto;
        }

        .section-reverse .section-content {
            flex-direction: row-reverse;
        }

        .footer {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background-color: #333333;
            color: #ffffff;
            padding: 20px;
        }

        .footer-logo {
            font-size: 24px;
            font-weight: bold;
        }

        .footer-menu {
            list-style: none;
            display: flex;
        }

        .footer-menu li {
            margin: 0 10px;
        }

        .footer-menu a {
            text-decoration: none;
            color: #ffffff;
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="container">
            <div class="navbar-logo">Kiwix</div>
            <ul class="navbar-menu">
                <li><a href="#about">About</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#content">Content</a></li>
                <li><a href="#download">Download</a></li>
            </ul>
        </div>
    </nav>
    <div class="hero">
        <div class="container">
            <div class="hero-left">
                <h1 class="hero-title">Offline Access to Knowledge</h1>
                <p class="hero-subtitle">Kiwix is a free and open-source software that allows you to access millions of articles, videos, and books without an internet connection.</p>
                <a href="#download" class="hero-button">Get Kiwix</a>
            </div>
            <div class="hero-right">
                <img src="hero-image.jpg" alt="Hero image" class="hero-image">
            </div>
        </div>
    </div>
    <div class="section" id="about">
        <div class="container">
            <h2 class="section-title">About Kiwix</h2>
            <p class="section-subtitle">Kiwix is a project that aims to make knowledge accessible to everyone, everywhere, even offline.</p>
            <div class="section-content">
                <div class="section-content-left">
                    <p class="section-content-text">Kiwix is a software that allows you to download and view content from various sources, such as Wikipedia, Khan Academy, TED talks, and more, without an internet connection. You can use Kiwix on your computer, smartphone, tablet, or even a Raspberry Pi. You can also share your content with others using a local network or a hotspot.</p>
                </div>
                <div class="section-content-right">
                    <img src="about-image.jpg" alt="About image" class="section-content-image">
                </div>
            </div>
        </div>
    </div>
    <div class="section section-reverse" id="features">
        <div class="container">
            <h2 class="section-title">Features of Kiwix</h2>
            <p class="section-subtitle">Kiwix offers a range of features that make offline access to knowledge easy and enjoyable.</p>
            <div class="section-content">
                <div class="section-content-left">
                    <img src="features-image.jpg" alt="Features image" class="section-content-image">
                </div>
                <div class="section-content-right">
                    <ul class="section-content-text">
                        <li>Fast and reliable: Kiwix works smoothly and efficiently, even on low-end devices.</li>
                        <li>Simple and user-friendly: Kiwix has a clear and intuitive interface that allows you to browse, search, and bookmark your content.</li>
                        <li>Customizable and flexible: Kiwix lets you choose the content you want to download, from a variety of sources and languages.</li>
                        <li>Portable and shareable: Kiwix can be installed on a USB stick or a SD card, and can be used to create a hotspot or a server.</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <div class="section" id="content">
        <div class="container">
            <h2 class="section-title">Content Available on Kiwix</h2>
            <p class="section-subtitle">Kiwix offers a rich and diverse collection of content that covers various topics and domains.</p>
            <div class="section-content">
                <div class="section-content-left">
                    <p class="section-content-text">With Kiwix, you can access millions of articles, videos, and books from various sources, such as:</p>
                    <ul class="section-content-text">
                        <li>Wikipedia: The free encyclopedia that anyone can edit.</li>
                        <li>Khan Academy: A nonprofit organization that provides free online courses and videos.</li>
                        <li>TED talks: A platform that features inspiring and informative talks from experts and innovators.</li>
                        <li>OpenStax: A nonprofit organization that provides free and open textbooks.</li>
                        <li>And many more: You can also find content from Wiktionary, Wikisource, Project Gutenberg, and more.</li>
                    </ul>
                </div>
                <div class="section-content-right">
                    <img src="content-image.jpg" alt="Content image" class="section-content-image">
                </div>
            </div>
        </div>
    </div>
    <div class="section section-reverse" id="download">
        <div class="container">
            <h2 class="section-title">Download Kiwix</h2>
            <p class="section-subtitle">Kiwix is free and easy to download and install on your device.</p>
            <div class="section-content">
                <div class="section-content-left">
                    <img src="download-image.jpg" alt="Download image" class="section-content-image">
                </div>
                <div class="section-content-right">
                                        <p class="section-content-text">To download Kiwix, you need to follow these steps:</p>
                    <ol class="section-content-text">
                        <li>Go to the [Kiwix website] and choose the version that suits your device and operating system.</li>
                        <li>Download the Kiwix installer and run it on your device.</li>
                        <li>Follow the instructions to complete the installation process.</li>
                        <li>Launch Kiwix and start browsing the content you want to download.</li>
                    </ol>
                    <p class="section-content-text">If you need more help, you can check the [Kiwix user guide] or contact the [Kiwix support team].</p>
                </div>
            </div>
        </div>
    </div>
    <div class="footer">
        <div class="container">
            <div class="footer-logo">Kiwix</div>
            <ul class="footer-menu">
                <li><a href="#">About</a></li>
                <li><a href="#">Features</a></li>
                <li><a href="#">Content</a></li>
                <li><a href="#">Download</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
    </div>
</body>
</html>
