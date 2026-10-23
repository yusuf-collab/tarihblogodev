<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kocaeli Tarih Gezisi - 1. Dönem Blog Ödevi</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600;700&family=Plus+Jakarta+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --bg-primary: #0a1128;
            --bg-secondary: #0f172a;
            --accent-gold: #c5a059;
            --accent-gold-light: #dfc285;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
            --card-bg: rgba(30, 41, 59, 0.7);
            --border-color: rgba(197, 160, 89, 0.2);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg-primary);
            color: var(--text-main);
            line-height: 1.7;
        }

        /* Header & Navbar */
        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            background: rgba(10, 17, 40, 0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid var(--border-color);
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1.2rem 5%;
        }

        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 1.3rem;
            color: var(--accent-gold);
            font-weight: 700;
            letter-spacing: 1px;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 2.5rem;
        }

        nav ul li a {
            color: var(--text-main);
            text-decoration: none;
            font-size: 0.95rem;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: var(--accent-gold);
        }

        /* Hero Section */
        .hero {
            padding: 12rem 5% 6rem 5%;
            background: linear-gradient(135deg, var(--bg-primary) 0%, var(--bg-secondary) 100%);
            text-align: center;
            border-bottom: 1px solid var(--border-color);
        }

        .hero h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            color: var(--text-main);
            margin-bottom: 1.5rem;
        }

        .hero h1 span {
            color: var(--accent-gold);
        }

        .student-badge {
            display: inline-block;
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            padding: 0.75rem 2rem;
            border-radius: 50px;
            font-size: 0.95rem;
            color: var(--accent-gold-light);
            margin-top: 1rem;
        }

        /* Container & Content */
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 5rem 2rem;
        }

        .section-title {
            font-family: 'Playfair Display', serif;
            font-size: 2.2rem;
            color: var(--accent-gold);
            margin-bottom: 2.5rem;
            text-align: center;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 2px;
            background: var(--accent-gold);
            margin: 0.75rem auto 0 auto;
        }

        .content-card {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 2.5rem;
            margin-bottom: 2.5rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
        }

        .content-card h3 {
            font-family: 'Playfair Display', serif;
            font-size: 1.6rem;
            color: var(--accent-gold-light);
            margin-bottom: 1.2rem;
            display: flex;
            align-items: center;
            gap: 0.75rem;
        }

        .content-card p, .content-card li {
            color: var(--text-muted);
            font-size: 1.05rem;
            margin-bottom: 1rem;
        }

        .content-card ul {
            padding-left: 1.5rem;
            margin-top: 0.5rem;
        }

        .content-card li {
            margin-bottom: 0.5rem;
        }

        /* Footer */
        footer {
            background: var(--bg-secondary);
            border-top: 1px solid var(--border-color);
            text-align: center;
            padding: 2.5rem;
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2.2rem; }
            nav ul { gap: 1rem; }
            .content-card { padding: 1.5rem; }
        }
    </style>
</head>
<body>

    <!-- Header / Navbar -->
    <header>
        <div class="logo">KOCAELİ TARİH</div>
        <nav>
            <ul>
                <li><a href="#ev">Ev</a></li>
                <li><a href="#fazlasi">Daha Fazlası</a></li>
                <li><a href="#kaynakca">Kaynakça</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="ev" class="hero">
        <h1>Tarih Ödevi <span>1. Dönem Gezi Bloğu</span></h1>
        <p>Kocaeli'nin tarihi mekanları, anıtları ve mimari yapıları üzerine hazırlanan dijital araştırma projesi.</p>
        <div class="student-badge">
            <i class="fa-solid fa-user-graduate"></i> Son Teslim: 23 Ekim 2026
        </div>
    </section>

    <!-- Main Content Container -->
    <div class="container">

        <!-- Soru 1 -->
        <section class="content-card">
            <h3><span style="color: var(--accent-gold);">01.</span> Namazgah Nedir?</h3>
            <p>Namazgahlar, İslam mimarisinde özellikle ordunun sefer güzergâhlarında, yolcuların konaklama noktalarında veya açık havada toplu ibadet edilmesi amacıyla inşa edilmiş üstü açık ibadet mekânlarıdır. Kocaeli ve çevresinde de Osmanlı döneminde hem askerlerin sefer öncesi Cuma ve bayram namazlarını kılmaları hem de halkın bir araya gelmesi için sıkça kullanılmıştır.</p>
            <p>Temel yapısı itibarıyla kıble yönünü belirten bir <strong>mihrap taşı</strong>, hatibin hutbe okuduğu <strong>minber</strong> ve etrafını çevreleyen alçak bir taş duvardan oluşur. Üstü kapalı camilerden farklı olarak doğayla iç içe, sade ve işlevsel mimarileriyle öne çıkarlar.</p>
            <h4 style="color: var(--text-main); margin-top: 1.5rem; margin-bottom: 0.5rem;">Namazgah Alanlarındaki Uzun Şehit Mezarları</h4>
            <p>Namazgah çevrelerinde veya tarihi şehitliklerde dikkati çeken bir diğer unsur ise <strong>normalden çok daha uzun tutulmuş (3-5 metreye varan) mezarlardır</strong>. Bu durumun temel sebepleri şunlardır:</p>
            <ul>
                <li><strong>Toplu Defin (Şehitlik Geleneği):</strong> Savaş ve muharebe anlarında şehit düşen birden fazla askerin aynı alana, tek bir hat halinde yan yana defnedilmesi durumunda mezar yapısı tek bir bütün olarak uzun inşa edilirdi.</li>
                <li><strong>Makam Mezar ve Saygı:</strong> Tarihte iz bırakmış alp, gazi veya önemli şehitlerin anısını yaşatmak, yoldan geçenlerin dikkatini çekip dua etmelerini sağlamak amacıyla hürmeten "makam mezar" şeklinde uzun tasarlanmışlardır. Burada amaç fiziki boyu temsil etmek değil, manevi makamın yüceliğini simgelemektir.</li>
            </ul>
        </section>

        <!-- Soru 2 -->
        <section class="content-card">
            <h3><span style="color: var(--accent-gold);">02.</span> Kocaeli Şehitliği (Dönemsel Mimari Farklar)</h3>
            <p>Kocaeli Şehitliği, bölgenin geçirdiği tarihi kırılmaları ve mimari anlayıştaki değişimi tek bir alanda görmemizi sağlayan çok özel bir mekândır. Farklı dönemlere ait mezar yapılarını incelediğimizde hem kullanılan malzeme hem de üzerlerindeki sembolizm açısından belirgin farklar göze çarpar:</p>
            
            <h4 style="color: var(--text-main); margin-top: 1.2rem; margin-bottom: 0.4rem;">1. Osmanlı Dönemi Mezarları</h4>
            <p>Genellikle mermer veya kesme taştan yapılır. İşlemeler ve taş işçiliği ön plandadır. Mezarların baş kısımlarındaki taşlar (şahide) mevki ve mesleğe göre şekil alır (sarık, fes veya kavuk başlıkları gibi). Osmanlı Türkçesiyle yazılmış kitabeler ve servi ağacı, lale gibi derin manevi anlamlar taşıyan kabartmalar yer alır.</p>
            
            <h4 style="color: var(--text-main); margin-top: 1.2rem; margin-bottom: 0.4rem;">2. Kurtuluş Savaşı Dönemi Mezarları</h4>
            <p>Savaşın getirdiği zorlu maddi imkânsızlıklar ve acil defin ihtiyaçları nedeniyle son derece yalın tasarlanmışlardır. Süslü taş işçiliği görülmez. Yerel taşlar kullanılmış, bazen isim yazılamadan sadece "Meçhul Asker" levhalarıyla bırakılmıştır; dönemin mücadelesini ve sadeliğini yansıtır.</p>

            <h4 style="color: var(--text-main); margin-top: 1.2rem; margin-bottom: 0.4rem;">3. Cumhuriyet Dönemi Mezarları</h4>
            <p>Belirli bir mimari düzen ve standart benimsenmiştir. Mezarlar düzenli sıralar halinde, beyaz mermerden ve tek tip ölçülerde inşa edilmiştir. Osmanlı dönemi dini motiflerinin yerini Ay-Yıldız almıştır. Kitabeler Latin alfabesiyle yazılmış olup ad, soyad ve şehadet tarihleri net bir şekilde yer alır.</p>
        </section>

        <!-- Kalan Sorular için Alan (Daha Fazlası Başlığı Altında) -->
        <div id="fazlasi"></div>
        <h2 class="section-title" style="margin-top: 4rem;">Diğer Gezi ve Araştırma Konuları</h2>

        <section class="content-card">
            <h3><span style="color: var(--accent-gold);">03 - 08.</span> Devam Eden Araştırma Başlıkları</h3>
            <p>Ödev yönergesinde yer alan diğer konular (`Orhan Cami detayları`, `Osmanlı hamam kültürü`, `Sırrıpaşa Konağı`, `Ahşap evler`, `Redif Müzesi` ve `Saat Kulesi`) bu alanda sergilenecektir.</p>
            <p style="color: var(--accent-gold-light); font-style: italic;">* Diğer soruların içerikleri eklendikçe bu alan otomatik olarak güncellenecektir.*</p>
        </section>

        <!-- Kaynakça Bölümü (İletişim yerine) -->
        <div id="kaynakca"></div>
        <h2 class="section-title" style="margin-top: 4rem;">Kaynakça</h2>
        <section class="content-card">
            <h3><span style="color: var(--accent-gold);"><i class="fa-solid fa-book"></i></span> Yararlanılan Kaynaklar</h3>
            <ul>
                <li>Kocaeli İl Kültür ve Turizm Müdürlüğü Arşivleri ve Gezi Rehberleri</li>
                <li>Osmanlı ve Kurtuluş Savaşı Dönemi Kocaeli Tarihi Literatürü</li>
                <li>Saha Araştırmaları ve Yerinde İnceleme Görselleri</li>
                <li>MEB 10. Sınıf Tarih Ders Kitabı ve İlgili Kaynak Metinleri</li>
            </ul>
        </section>

    </div>

    <!-- Footer -->
    <footer>
        <p>Kocaeli Tarih Gezisi Blog Projesi &copy; 2026 | Tüm Hakları Saklıdır.</p>
    </footer>

</body>
</html>
