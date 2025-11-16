<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- SEO Meta Tags -->
    <title>Jak odzyskać spokój w 14 dni bez rewolucji w życiu</title>
    <meta name="description" content="Program dla zapracowanych kobiet. Odzyskaj spokój w 60-90 min dziennie, bez technikaliów. Cena startowa 55 zł.">
    
    <!-- Open Graph -->
    <meta property="og:title" content="Jak odzyskać spokój w 14 dni bez rewolucji w życiu">
    <meta property="og:description" content="Program dla zapracowanych kobiet. 14 dni, 60-90 min dziennie.">
    <meta property="og:type" content="website">
    
    <style>
        /* Reset & Base */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #fff;
        }
        
        /* Container */
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Sections */
        section {
            padding: 60px 0;
        }
        
        /* Typography */
        h1 {
            font-size: 2.5rem;
            line-height: 1.2;
            margin-bottom: 20px;
            font-weight: 700;
        }
        
        h2 {
            font-size: 2rem;
            margin-bottom: 30px;
            font-weight: 700;
            color: #1e40af;
        }
        
        h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            font-weight: 600;
        }
        
        p {
            font-size: 1.125rem;
            margin-bottom: 15px;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #1e40af 0%, #3b82f6 100%);
            color: white;
            text-align: center;
            padding: 80px 0;
        }
        
        .hero h1 {
            color: white;
            font-size: 2.8rem;
        }
        
        .hero .subtitle {
            font-size: 1.3rem;
            margin-bottom: 20px;
            opacity: 0.95;
        }
        
        .hero .mini-proof {
            display: inline-block;
            background: rgba(255, 255, 255, 0.2);
            padding: 10px 20px;
            border-radius: 25px;
            margin: 20px 0;
            font-size: 1rem;
        }
        
        /* Buttons */
        .btn {
            display: inline-block;
            padding: 16px 40px;
            font-size: 1.125rem;
            font-weight: 700;
            text-decoration: none;
            border-radius: 6px;
            transition: all 0.3s;
            cursor: pointer;
            border: none;
        }
        
        .btn-primary {
            background: #dc2626;
            color: white;
        }
        
        .btn-primary:hover {
            background: #b91c1c;
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(220, 38, 38, 0.3);
        }
        
        .btn-secondary {
            background: white;
            color: #1e40af;
            margin-left: 15px;
        }
        
        .btn-secondary:hover {
            background: #f3f4f6;
        }
        
        /* Lists */
        ul.check-list {
            list-style: none;
            margin: 20px 0;
        }
        
        ul.check-list li {
            padding: 12px 0;
            padding-left: 35px;
            position: relative;
            font-size: 1.125rem;
        }
        
        ul.check-list li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #1e40af;
            font-weight: bold;
            font-size: 1.4rem;
        }
        
        ul.x-list li:before {
            content: "✗";
            color: #dc2626;
        }
        
        /* Cards */
        .card {
            background: white;
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }
        
        .card h3 {
            color: #1e40af;
        }
        
        /* Grid */
        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin: 30px 0;
        }
        
        /* Steps */
        .steps {
            counter-reset: step-counter;
            margin: 40px 0;
        }
        
        .step {
            counter-increment: step-counter;
            position: relative;
            padding-left: 70px;
            margin-bottom: 40px;
        }
        
        .step:before {
            content: counter(step-counter);
            position: absolute;
            left: 0;
            top: 0;
            width: 50px;
            height: 50px;
            background: #1e40af;
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 1.5rem;
            line-height: 50px;
            text-align: center;
        }
        
        /* Price Box */
        .price-box {
            background: linear-gradient(135deg, #1e40af 0%, #3b82f6 100%);
            color: white;
            border-radius: 10px;
            padding: 50px;
            text-align: center;
            margin: 40px 0;
        }
        
        .price-box h2 {
            color: white;
        }
        
        .price {
            font-size: 4rem;
            font-weight: 800;
            margin: 20px 0;
        }
        
        .price-note {
            font-size: 1rem;
            opacity: 0.9;
            margin-bottom: 30px;
        }
        
        /* FAQ */
        .faq-item {
            border-bottom: 1px solid #e5e7eb;
            padding: 25px 0;
        }
        
        .faq-question {
            font-weight: 700;
            font-size: 1.2rem;
            color: #1e40af;
            margin-bottom: 10px;
        }
        
        .faq-answer {
            color: #4b5563;
            font-size: 1.1rem;
        }
        
        /* Trust Bar */
        .trust-bar {
            background: #f3f4f6;
            padding: 20px 0;
            text-align: center;
            font-size: 0.95rem;
            color: #6b7280;
        }
        
        .trust-bar span {
            display: inline-block;
            margin: 0 15px;
        }
        
        /* Background Variations */
        .bg-light {
            background: #f9fafb;
        }
        
        .bg-white {
            background: white;
        }
        
        /* Error/Success Boxes */
        .error-box {
            background: #fee2e2;
            border-left: 4px solid #dc2626;
            padding: 25px;
            border-radius: 6px;
            margin: 20px 0;
        }
        
        .success-box {
            background: #d1fae5;
            border-left: 4px solid #059669;
            padding: 25px;
            border-radius: 6px;
            margin: 20px 0;
        }
        
        /* Testimonial */
        .testimonial {
            background: #eff6ff;
            border-left: 4px solid #1e40af;
            padding: 30px;
            border-radius: 6px;
            font-style: italic;
            margin: 30px 0;
            font-size: 1.15rem;
        }
        
        /* Thank You Section */
        .thank-you {
            display: none;
            padding: 80px 0;
            text-align: center;
        }
        
        .thank-you.active {
            display: block;
        }
        
        .thank-you-box {
            background: #f9fafb;
            border-radius: 10px;
            padding: 50px;
            max-width: 600px;
            margin: 0 auto;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            h2 {
                font-size: 1.6rem;
            }
            
            .grid-2 {
                grid-template-columns: 1fr;
            }
            
            .btn-secondary {
                margin-left: 0;
                margin-top: 15px;
                display: block;
            }
            
            .price {
                font-size: 3rem;
            }
            
            section {
                padding: 40px 0;
            }
            
            .trust-bar span {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>

    <!-- HERO SECTION -->
    <section class="hero">
        <div class="container">
            <h1>Jak odzyskać spokój w 14 dni<br>bez rewolucji w życiu</h1>
            <p class="subtitle">Dla zapracowanych kobiet – zrobisz to po pracy, w 60–90 min, bez technikaliów.</p>
            <div class="mini-proof">Wczoraj dołączyło 317 kobiet</div>
            <br><br>
            <a href="#cta" class="btn btn-primary">Kup Teraz — 55 zł</a>
            <a href="#co-dostajesz" class="btn btn-secondary">Zobacz co dostajesz</a>
        </div>
    </section>

    <!-- SECTION 2: DLA KOGO / NIE DLA KOGO -->
    <section class="bg-white">
        <div class="container">
            <h2>Dla kogo jest ten program?</h2>
            
            <div class="grid-2">
                <div class="card">
                    <h3>✓ To dla Ciebie, jeśli:</h3>
                    <ul class="check-list">
                        <li>Masz 60–90 min wieczorem</li>
                        <li>Chcesz prosty i naturalny sposób na spokój</li>
                        <li>Lubisz prowadzenie krok-po-kroku</li>
                        <li>Wolisz gotowy plan zamiast szukania informacji</li>
                        <li>Chcesz odzyskać energię bez radykalnych zmian</li>
                    </ul>
                </div>
                
                <div class="card">
                    <h3>✗ Nie dla Ciebie, jeśli:</h3>
                    <ul class="check-list x-list">
                        <li>Oczekujesz efektów bez pracy</li>
                        <li>Nie masz 10 min dziennie</li>
                        <li>Szukasz "magicznej pigułki"</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION 3: EFEKT W 60-90 MIN -->
    <section class="bg-light">
        <div class="container">
            <h2>Po dzisiejszym wieczorze będziesz mieć:</h2>
            <ul class="check-list" style="max-width: 700px; margin: 0 auto;">
                <li>Gotowy plan 14 dni</li>
                <li>Listę 5 mikro-rytuałów</li>
                <li>Mini-audio „Reset w 3 minuty"</li>
                <li>Gotową stronę „Kup teraz"</li>
                <li>Automatyczną dostawę PDF</li>
            </ul>
        </div>
    </section>

    <!-- SECTION 4: CO DOSTAJESZ -->
    <section class="bg-white" id="co-dostajesz">
        <div class="container">
            <h2>Co dostajesz w środku?</h2>
            
            <div class="card">
                <h3>📦 Kompletny pakiet</h3>
                <ul class="check-list">
                    <li>Szablon strony sprzedażowej</li>
                    <li>Przykładowy tekst (5 bulletów)</li>
                    <li>Instrukcja „Kup teraz" + płatność</li>
                    <li>Szablon „Dziękuję / Pobierz"</li>
                    <li>Checklista wdrożenia w 15 min</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- SECTION 5: JAK TO DZIAŁA -->
    <section class="bg-light">
        <div class="container">
            <h2>Jak to działa? (3 kroki)</h2>
            
            <div class="steps">
                <div class="step">
                    <h3>Wybierasz temat i wklejasz szablon</h3>
                    <p>Gotowy szablon strony — po prostu kopiujesz i wklejasz.</p>
                </div>
                
                <div class="step">
                    <h3>Dodajesz przycisk „Kup teraz" + link do płatności</h3>
                    <p>Prosty proces: jeden przycisk, jeden link — działa od razu.</p>
                </div>
                
                <div class="step">
                    <h3>Ustawiasz automatyczną dostawę (PDF / mini-kurs)</h3>
                    <p>Po płatności kupujący dostaje produkt — wszystko automatycznie.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION 6: NAJCZĘSTSZY BŁĄD -->
    <section class="bg-white">
        <div class="container">
            <h2>Najczęstszy błąd → Rozwiązanie</h2>
            
            <div class="error-box">
                <h3 style="color: #dc2626;">❌ Błąd: Pisanie długich opisów</h3>
                <p>Większość osób pisze zbyt dużo tekstu, co odstrasza kupujących.</p>
            </div>
            
            <div class="success-box">
                <h3 style="color: #059669;">✓ Rozwiązanie: Nagłówek + 5 bulletów + CTA</h3>
                <p>Użyj mocnego nagłówka + 5 bulletów + jeden przycisk. Strona ma sprzedawać kliknięcie, nie być książką.</p>
            </div>
        </div>
    </section>

    <!-- SECTION 7: MINI CASE -->
    <section class="bg-light">
        <div class="container">
            <h2>Przykład z życia</h2>
            
            <div class="testimonial">
                <p><strong>„Zrobiłam 3 pierwsze sprzedaże w 48 h bez reklam (tylko post + ta strona). Cena: 55 zł."</strong></p>
                <p style="margin-top: 15px; font-style: normal; font-size: 0.95rem;">Lub wersja dla nowej użytkowniczki: „Zaczynam dziś — wpiszę wyniki za 48 h."</p>
            </div>
        </div>
    </section>

    <!-- SECTION 8: OFERTA / CENA -->
    <section class="bg-white" id="cta">
        <div class="container">
            <div class="price-box">
                <h2>Cena startowa</h2>
                <div class="price">55 zł</div>
                <p class="price-note">⚡ Limit: pierwsze 20 osób w tej cenie</p>
                <p style="margin-bottom: 30px; font-size: 1.15rem;">
                    Kupujesz gotowy, powtarzalny system.
                </p>
                <a href="#thankyou" class="btn btn-primary">KUP TERAZ — 55 zł</a>
            </div>
        </div>
    </section>

    <!-- SECTION 9: FAQ -->
    <section class="bg-light">
        <div class="container">
            <h2>Najczęściej zadawane pytania</h2>
            
            <div class="faq-item">
                <div class="faq-question">Czy muszę umieć kodować?</div>
                <div class="faq-answer">Nie. Wszystko jest gotowe do skopiowania i wklejenia.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Ile czasu to zajmie?</div>
                <div class="faq-answer">60–90 min na pierwsze wdrożenie.</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-question">Jak dostanę produkt?</div>
                <div class="faq-answer">Automatyczna dostawa + mail po płatności. Natychmiastowy dostęp.</div>
            </div>
        </div>
    </section>

    <!-- SECTION 10: CTA KOŃCOWE -->
    <section class="bg-white">
        <div class="container" style="text-align: center;">
            <h2>Gotowa na spokój?</h2>
            <a href="#thankyou" class="btn btn-primary" style="font-size: 1.3rem; padding: 20px 50px;">KUP TERAZ — 55 zł</a>
            <p style="margin-top: 30px; color: #6b7280;">
                Płatność Stripe / Gumroad. Masz pytanie? Napisz: <a href="mailto:kontakt@twojadomena.pl" style="color: #1e40af;">kontakt@twojadomena.pl</a>
            </p>
        </div>
    </section>

    <!-- Trust Bar -->
    <div class="trust-bar">
        <span>🔒 Stripe</span>
        <span>💳 Gumroad</span>
        <span>✓ 14-dni zwrot</span>
        <span>🔐 Bezpieczne płatności</span>
    </div>

    <!-- BONUS: SEKCJA DZIĘKUJĘ / POBIERZ -->
    <section class="thank-you" id="thankyou">
        <div class="container">
            <div class="thank-you-box">
                <h1 style="color: #1e40af;">🎉 Dziękuję!</h1>
                <p style="font-size: 1.3rem; margin: 30px 0;">
                    Twój e-produkt <strong>„Czuły Reset"</strong> jest gotowy.
                </p>
                <a href="#download" class="btn btn-primary" style="font-size: 1.2rem;">👉 POBIERZ TERAZ (PDF)</a>
                <p style="margin-top: 30px; color: #6b7280;">
                    Link wysłałam też na e-mail.<br>
                    W razie problemów napisz: <a href="mailto:kontakt@twojadomena.pl" style="color: #1e40af;">kontakt@twojadomena.pl</a>
                </p>
            </div>
        </div>
    </section>

</body>
</html>
