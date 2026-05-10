<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Balcón | Experiencia Gastronómica</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700&family=Playfair+Display:ital,wght@0,700;1,700&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        :root {
            --primary: #FF5722; /* Naranja Energético */
            --primary-dark: #E64A19;
            --secondary: #2E7D32; /* Verde Frescura */
            --accent: #FFC107; /* Amarillo Sol */
            --dark: #1A1A1A;
            --light: #FFFFFF;
            --cream: #FFF9F1;
        }

        * { box-sizing: border-box; }
        body {
            margin: 0;
            font-family: 'Montserrat', sans-serif;
            background-color: var(--cream);
            color: var(--dark);
            scroll-behavior: smooth;
            line-height: 1.6;
        }

        /* Hero Section Impactante */
        header {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 0 20px;
        }

        header h1 {
            font-family: 'Playfair Display', serif;
            font-size: clamp(3rem, 8vw, 6rem);
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.5rem;
            margin-bottom: 40px;
            max-width: 700px;
            font-weight: 300;
        }

        /* Sección de Propuesta de Valor (Datos: Frescura y Calidad) */
        .info-strip {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            background: var(--light);
            padding: 50px 10%;
            gap: 30px;
            box-shadow: 0 -10px 30px rgba(0,0,0,0.05);
        }

        .info-box {
            text-align: center;
            padding: 20px;
        }

        .info-box h3 { color: var(--primary); margin-top: 15px; }
        .info-box i { font-size: 2.5rem; color: var(--secondary); }

        /* Menú Dinámico con Categorías */
        .section-title {
            text-align: center;
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            margin: 60px 0 40px;
            position: relative;
        }

        .section-title::after {
            content: '';
            width: 80px;
            height: 4px;
            background: var(--primary);
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
        }

        .menu-container {
            padding: 0 10%;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 40px;
            margin-bottom: 80px;
        }

        .card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
            transition: 0.4s;
        }

        .card:hover { transform: translateY(-15px); }

        .card-img {
            height: 250px;
            background-size: cover;
            background-position: center;
        }

        .card-content { padding: 25px; }
        .price { 
            float: right; 
            color: var(--secondary); 
            font-weight: bold; 
            font-size: 1.2rem; 
        }

        /* Sección de Ambiente (Imágenes Grandes) */
        .parallax-bg {
            height: 400px;
            background: linear-gradient(rgba(46, 125, 50, 0.7), rgba(46, 125, 50, 0.7)),
                        url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-attachment: fixed;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }

        /* Sección de Testimonios (Social Proof) */
        .testimonials {
            padding: 80px 10%;
            background: var(--cream);
        }

        .testi-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .testi-card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            font-style: italic;
            border-left: 5px solid var(--accent);
        }

        /* Formulario de Fidelización Vistoso */
        .club-balcon {
            background: var(--primary);
            color: white;
            padding: 100px 10%;
            text-align: center;
            clip-path: polygon(0 10%, 100% 0, 100% 90%, 0 100%);
        }

        .input-group {
            margin-top: 30px;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .input-group input {
            padding: 20px 30px;
            border-radius: 50px;
            border: none;
            width: 400px;
            font-size: 1rem;
            margin: 10px;
        }

        .btn-submit {
            padding: 20px 40px;
            border-radius: 50px;
            background: var(--dark);
            color: white;
            border: none;
            cursor: pointer;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn-submit:hover { background: #000; transform: scale(1.05); }

        footer {
            background: var(--dark);
            color: rgba(255,255,255,0.6);
            padding: 60px 10% 20px;
            text-align: center;
        }

        .footer-links { margin-bottom: 30px; }
        .footer-links a { color: white; margin: 0 15px; text-decoration: none; }

        @media (max-width: 768px) {
            .input-group input { width: 100%; }
            .section-title { font-size: 2rem; }
        }
    </style>
</head>
<body>

    <header>
        <p style="text-transform: uppercase; letter-spacing: 5px; color: var(--accent);">Desde el Corazón de la Ciudad</p>
        <h1>EL BALCÓN</h1>
        <p>Donde los datos se vuelven sabor. Disfruta de la mejor experiencia de Brunch & Café diseñada para ti.</p>
        <a href="#menu" class="cta-button" style="padding: 15px 40px; background: var(--primary); color: white; border-radius: 50px; text-decoration: none; font-weight: bold;">EXPLORAR EL MENÚ</a>
    </header>

    <section class="info-strip">
        <div class="info-box">
            <div style="font-size: 3rem;">🥑</div>
            <h3>Ingredientes Locales</h3>
            <p>Seleccionamos lo mejor del mercado cada mañana.</p>
        </div>
        <div class="info-box">
            <div style="font-size: 3rem;">☕</div>
            <h3>Café de Especialidad</h3>
            <p>Tostado artesanal para despertar tus sentidos.</p>
        </div>
        <div class="info-box">
            <div style="font-size: 3rem;">✨</div>
            <h3>Ambiente Único</h3>
            <p>El espacio perfecto para trabajar o convivir.</p>
        </div>
    </section>

    <section id="menu">
        <h2 class="section-title">Los Favoritos del Público</h2>
        <div class="menu-container">
            <div class="card">
                <div class="card-img" style="background-image: url('https://images.unsplash.com/photo-1626074353765-517a681e40be?auto=format&fit=crop&w=600&q=80');"></div>
                <div class="card-content">
                    <span class="price">$145</span>
                    <h3>Enchiladas El Balcón</h3>
                    <p>Nuestra receta secreta con salsa verde artesanal, crema de rancho y queso fresco.</p>
                </div>
            </div>
            <div class="card">
                <div class="card-img" style="background-image: url('https://images.unsplash.com/photo-1525351484163-7529414344d8?auto=format&fit=crop&w=600&q=80');"></div>
                <div class="card-content">
                    <span class="price">$120</span>
                    <h3>Omelette Especial</h3>
                    <p>Tres huevos orgánicos, espinacas baby, champiñones y un toque de queso de cabra.</p>
                </div>
            </div>
            <div class="card">
                <div class="card-img" style="background-image: url('https://images.unsplash.com/photo-1553531384-397c80973a0b?auto=format&fit=crop&w=600&q=80');"></div>
                <div class="card-content">
                    <span class="price">$75</span>
                    <h3>Smoothie de Moras</h3>
                    <p>Antioxidante natural con mezcla de frutos rojos, yogurt griego y miel de abeja.</p>
                </div>
            </div>
        </div>
    </section>

    <div class="parallax-bg">
        <div>
            <h2 style="font-size: 2.5rem; margin-bottom: 10px;">¿Buscas un lugar para trabajar?</h2>
            <p style="font-size: 1.2rem;">Contamos con WiFi de alta velocidad y el mejor café para tus mañanas productivas.</p>
        </div>
    </div>

    <section class="testimonials">
        <h2 class="section-title">Lo que dicen nuestros clientes</h2>
        <div class="testi-grid">
            <div class="testi-card">
                "Las enchiladas son de otro mundo, se nota la frescura de los ingredientes. Mi lugar favorito para desayunar los sábados."
                <p><strong>- Mariana G.</strong></p>
            </div>
            <div class="testi-card">
                "Excelente ambiente para juntas de trabajo. El café tiene un sabor increíble y el servicio es muy rápido."
                <p><strong>- Roberto V.</strong></p>
            </div>
            <div class="testi-card">
                "Me encanta que siempre tienen opciones saludables y los smoothies son deliciosos. ¡Súper recomendado!"
                <p><strong>- Lucía M.</strong></p>
            </div>
        </div>
    </section>

    <section class="club-balcon">
        <h2 style="font-family: 'Playfair Display'; font-size: 2.5rem;">Únete al Club del Postre</h2>
        <p>¿Sabías que el 40% de nuestros visitantes olvidan el postre? <br> Regístrate y te regalamos unos <strong>Churros Tradicionales</strong> en tu próxima visita.</p>
        <div class="input-group">
            <input type="email" placeholder="Ingresa tu correo favorito...">
            <button class="btn-submit">QUIERO MI REGALO</button>
        </div>
    </section>

    <footer>
        <div class="footer-links">
            <a href="#">Inicio</a>
            <a href="#">Menú</a>
            <a href="#">Reservaciones</a>
            <a href="#">Contacto</a>
        </div>
        <p>Av. Principal #123, Ciudad del Sabor | Tel: (55) 1234-5678</p>
        <p style="margin-top: 20px; font-size: 0.8rem;">&copy; 2024 El Balcón. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
