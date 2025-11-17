# 🌐 PRIX CONSULTORA - CÓDIGO COMPLETO DEL SITIO WEB

**Fecha:** 8 Noviembre 2025  
**Versión:** v1.5  
**URL producción:** https://ivlzbaxx.gensparkspace.com/  
**Dominio final:** prixconsultora.com

---

## 📋 ÍNDICE

1. [index.html](#indexhtml)
2. [css/style.css](#cssstylecss)
3. [js/main.js](#jsmainjs)
4. [README.md](#readmemd)
5. [Archivos de imágenes](#archivos-de-imágenes)

---

## 📄 index.html

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Prix Consultora - Consultora integral para emprendedores argentinos en España. Asesoramiento contable, legal, creativo e IA.">
    <title>Prix Consultora | Consultora Integral para Emprendedores Argentinos en España</title>
    
    <!-- Open Graph / Facebook / WhatsApp -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://ivlzbaxx.gensparkspace.com/">
    <meta property="og:title" content="Prix Consultora | Consultora para Emprendedores Argentinos en España">
    <meta property="og:description" content="Transformamos ideas en negocios sólidos. Asesoramiento integral: contable, legal, creativo e IA para argentinos en España.">
    <meta property="og:image" content="https://ivlzbaxx.gensparkspace.com/images/og-image.jpg?v=3">
    <meta property="og:image:secure_url" content="https://ivlzbaxx.gensparkspace.com/images/og-image.jpg?v=3">
    <meta property="og:image:type" content="image/jpeg">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:image:alt" content="Prix Consultora - Asesoramiento integral para emprendedores argentinos en España">
    
    <!-- Twitter -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:url" content="https://ivlzbaxx.gensparkspace.com/">
    <meta name="twitter:title" content="Prix Consultora | Consultora para Emprendedores Argentinos en España">
    <meta name="twitter:description" content="Transformamos ideas en negocios sólidos. Asesoramiento integral: contable, legal, creativo e IA para argentinos en España.">
    <meta name="twitter:image" content="https://ivlzbaxx.gensparkspace.com/images/og-image.jpg?v=3">
    
    <!-- Favicon -->
    <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'><path fill='%23f59e0b' d='M256 0C114.6 0 0 114.6 0 256s114.6 256 256 256s256-114.6 256-256S397.4 0 256 0zM256 448c-106 0-192-86-192-192S150 64 256 64s192 86 192 192S362 448 256 448zM368.7 162.1l-144.1 144.1c-13.3 13.3-34.8 13.3-48.1 0c-13.3-13.3-13.3-34.8 0-48.1l144.1-144.1c13.3-13.3 34.8-13.3 48.1 0C381.9 127.3 381.9 148.8 368.7 162.1z'/></svg>">
    <link rel="apple-touch-icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'><path fill='%23f59e0b' d='M256 0C114.6 0 0 114.6 0 256s114.6 256 256 256s256-114.6 256-256S397.4 0 256 0zM256 448c-106 0-192-86-192-192S150 64 256 64s192 86 192 192S362 448 256 448zM368.7 162.1l-144.1 144.1c-13.3 13.3-34.8 13.3-48.1 0c-13.3-13.3-13.3-34.8 0-48.1l144.1-144.1c13.3-13.3 34.8-13.3 48.1 0C381.9 127.3 381.9 148.8 368.7 162.1z'/></svg>">
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=Poppins:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    
    <!-- Custom CSS -->
    <link rel="stylesheet" href="css/style.css">
    
    <!-- Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-HY8SPB4B8P"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', 'G-HY8SPB4B8P');
    </script>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar" id="navbar">
        <div class="container">
            <div class="nav-wrapper">
                <div class="logo">
                    <i class="fas fa-compass"></i>
                    <span>PRIX CONSULTORA</span>
                </div>
                <button class="menu-toggle" id="menuToggle">
                    <span></span>
                    <span></span>
                    <span></span>
                </button>
                <ul class="nav-menu" id="navMenu">
                    <li><a href="#inicio" class="nav-link">Inicio</a></li>
                    <li><a href="#nosotros" class="nav-link">Nosotros</a></li>
                    <li><a href="#servicios" class="nav-link">Servicios</a></li>
                    <li><a href="#proceso" class="nav-link">Proceso</a></li>
                    <li><a href="#testimonios" class="nav-link">Testimonios</a></li>
                    <li><a href="#contacto" class="nav-link btn-nav">Contacto</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="inicio">
        <div class="hero-overlay"></div>
        <div class="container hero-content">
            <h1 class="hero-title fade-in">Transforma tu idea en un negocio sólido en España</h1>
            <p class="hero-subtitle fade-in">Consultoría integral para emprendedores argentinos: contable, legal, creativa e Inteligencia Artificial</p>
            <div class="hero-cta fade-in">
                <a href="#contacto" class="btn btn-primary">Comienza tu proyecto</a>
                <a href="#servicios" class="btn btn-secondary">Conoce nuestros servicios</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="section-about" id="nosotros">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Sobre Nosotros</h2>
                <p class="section-description">Tu socio estratégico en el camino del emprendimiento</p>
            </div>
            <div class="about-content">
                <div class="about-text">
                    <h3>Transformamos ideas en negocios exitosos</h3>
                    <p>En <strong>Prix Consultora</strong>, entendemos los desafíos únicos que enfrentan los emprendedores argentinos al establecerse en España. Hemos creado un ecosistema completo de servicios diseñado específicamente para facilitar tu camino hacia el éxito empresarial.</p>
                    <p>Combinamos el profundo conocimiento de ambos mercados con herramientas de última generación, incluyendo Inteligencia Artificial, para brindarte una ventaja competitiva real en el dinámico mercado europeo.</p>
                    <div class="about-stats">
                        <div class="stat-item">
                            <div class="stat-number">100+</div>
                            <div class="stat-label">Clientes satisfechos</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">95%</div>
                            <div class="stat-label">Tasa de éxito</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number">10+</div>
                            <div class="stat-label">Años de experiencia</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="section-services" id="servicios">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Nuestros Servicios</h2>
                <p class="section-description">Soluciones integrales para cada etapa de tu negocio</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-calculator"></i>
                    </div>
                    <h3>Contabilidad y Finanzas</h3>
                    <p>Gestión contable completa, asesoramiento fiscal personalizado y optimización financiera. Te ayudamos a cumplir con todas las obligaciones tributarias mientras maximizamos tu rentabilidad.</p>
                    <ul class="service-features">
                        <li><i class="fas fa-check"></i> Contabilidad mensual</li>
                        <li><i class="fas fa-check"></i> Declaraciones fiscales</li>
                        <li><i class="fas fa-check"></i> Planificación financiera</li>
                        <li><i class="fas fa-check"></i> Optimización tributaria</li>
                    </ul>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-balance-scale"></i>
                    </div>
                    <h3>Legal y Regulatorio</h3>
                    <p>Asesoramiento legal completo para la constitución y operación de tu empresa. Gestionamos todos los trámites necesarios para que puedas enfocarte en hacer crecer tu negocio.</p>
                    <ul class="service-features">
                        <li><i class="fas fa-check"></i> Constitución de empresas</li>
                        <li><i class="fas fa-check"></i> Trámites migratorios</li>
                        <li><i class="fas fa-check"></i> Contratos y acuerdos</li>
                        <li><i class="fas fa-check"></i> Protección de marca</li>
                    </ul>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-lightbulb"></i>
                    </div>
                    <h3>Marketing y Creatividad</h3>
                    <p>Desarrollamos tu identidad de marca y estrategias de marketing digital que conectan con tu audiencia. Creamos contenido que convierte y posiciona tu negocio en el mercado.</p>
                    <ul class="service-features">
                        <li><i class="fas fa-check"></i> Identidad de marca</li>
                        <li><i class="fas fa-check"></i> Marketing digital</li>
                        <li><i class="fas fa-check"></i> Gestión de redes sociales</li>
                        <li><i class="fas fa-check"></i> Estrategia de contenido</li>
                    </ul>
                </div>
                <div class="service-card featured">
                    <div class="service-badge">Innovación</div>
                    <div class="service-icon">
                        <i class="fas fa-robot"></i>
                    </div>
                    <h3>Inteligencia Artificial</h3>
                    <p>Implementamos soluciones de IA para automatizar procesos, mejorar la toma de decisiones y dar a tu negocio una ventaja competitiva en la era digital.</p>
                    <ul class="service-features">
                        <li><i class="fas fa-check"></i> Automatización de procesos</li>
                        <li><i class="fas fa-check"></i> Análisis predictivo</li>
                        <li><i class="fas fa-check"></i> Chatbots y atención al cliente</li>
                        <li><i class="fas fa-check"></i> Optimización con IA</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="section-process" id="proceso">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Nuestro Proceso</h2>
                <p class="section-description">Un camino claro hacia el éxito de tu negocio</p>
            </div>
            <div class="process-grid">
                <div class="process-step">
                    <div class="process-number">01</div>
                    <div class="process-icon">
                        <i class="fas fa-search"></i>
                    </div>
                    <h3>Diagnóstico</h3>
                    <p>Analizamos en profundidad tu situación actual, objetivos y desafíos. Identificamos oportunidades y establecemos las bases para tu estrategia de éxito.</p>
                </div>
                <div class="process-step">
                    <div class="process-number">02</div>
                    <div class="process-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3>Estrategia</h3>
                    <p>Diseñamos un plan personalizado que integra todos nuestros servicios según tus necesidades específicas. Definimos objetivos claros y métricas de éxito.</p>
                </div>
                <div class="process-step">
                    <div class="process-number">03</div>
                    <div class="process-icon">
                        <i class="fas fa-rocket"></i>
                    </div>
                    <h3>Implementación</h3>
                    <p>Ejecutamos el plan con precisión, gestionando cada detalle. Nuestro equipo trabaja en conjunto para asegurar una implementación fluida y efectiva.</p>
                </div>
                <div class="process-step">
                    <div class="process-number">04</div>
                    <div class="process-icon">
                        <i class="fas fa-trophy"></i>
                    </div>
                    <h3>Crecimiento</h3>
                    <p>Monitoreamos resultados, optimizamos continuamente y escalamos tu negocio. Te acompañamos en cada etapa de tu crecimiento empresarial.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Us Section -->
    <section class="section-why">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">¿Por qué elegirnos?</h2>
                <p class="section-description">Lo que nos hace diferentes</p>
            </div>
            <div class="why-grid">
                <div class="why-card">
                    <div class="why-icon">
                        <i class="fas fa-handshake"></i>
                    </div>
                    <h3>Experiencia Binacional</h3>
                    <p>Entendemos profundamente tanto el mercado argentino como el español. Esta perspectiva única nos permite anticipar desafíos y aprovechar oportunidades que otros no ven.</p>
                </div>
                <div class="why-card">
                    <div class="why-icon">
                        <i class="fas fa-puzzle-piece"></i>
                    </div>
                    <h3>Servicio Integral 360°</h3>
                    <p>Somos tu ventanilla única para todos los aspectos de tu negocio. Desde lo legal hasta lo creativo, pasando por la tecnología más avanzada, lo cubrimos todo.</p>
                </div>
                <div class="why-card">
                    <div class="why-icon">
                        <i class="fas fa-brain"></i>
                    </div>
                    <h3>Innovación con IA</h3>
                    <p>Somos pioneros en integrar Inteligencia Artificial en la consultoría empresarial. Te damos herramientas del futuro para competir hoy.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="section-testimonials" id="testimonios">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Lo que dicen nuestros clientes</h2>
                <p class="section-description">Historias reales de éxito</p>
            </div>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <div class="testimonial-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <p>"Prix Consultora nos ayudó a establecer nuestra empresa en España de manera impecable. Su conocimiento del mercado español y su profesionalismo hicieron que el proceso fuera mucho más simple de lo que esperábamos."</p>
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="author-info">
                            <h4>María González</h4>
                            <p>CEO, TechStart Solutions</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <div class="testimonial-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <p>"La implementación de IA en nuestros procesos, guiada por Prix, nos permitió reducir costos en un 40% y mejorar significativamente nuestro servicio al cliente. Realmente son expertos en su campo."</p>
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="author-info">
                            <h4>Carlos Rodríguez</h4>
                            <p>Fundador, Innovate Digital</p>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <div class="testimonial-rating">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <p>"Desde el primer día, el equipo de Prix demostró un compromiso excepcional con nuestro proyecto. Su enfoque integral nos permitió centrarnos en nuestro negocio mientras ellos se ocupaban de todo lo demás."</p>
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="author-info">
                            <h4>Laura Martínez</h4>
                            <p>Directora, Green Solutions España</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="section-cta">
        <div class="container">
            <div class="cta-content">
                <h2>¿Listo para transformar tu idea en realidad?</h2>
                <p>Agenda una consulta gratuita y descubre cómo podemos ayudarte a alcanzar tus objetivos empresariales en España.</p>
                <a href="#contacto" class="btn btn-large">Comienza ahora</a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="section-contact" id="contacto">
        <div class="container">
            <div class="section-header">
                <h2 class="section-title">Contacta con nosotros</h2>
                <p class="section-description">Estamos aquí para responder tus preguntas</p>
            </div>
            <div class="contact-wrapper">
                <div class="contact-info">
                    <h3>Información de contacto</h3>
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <div>
                            <h4>Email</h4>
                            <p>info@prixconsultora.com</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <div>
                            <h4>Teléfono</h4>
                            <p>+34 XXX XXX XXX</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <div>
                            <h4>Ubicación</h4>
                            <p>España</p>
                        </div>
                    </div>
                    <div class="contact-social">
                        <h4>Síguenos</h4>
                        <div class="social-links">
                            <a href="#" target="_blank"><i class="fab fa-linkedin"></i></a>
                            <a href="#" target="_blank"><i class="fab fa-instagram"></i></a>
                            <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
                            <a href="#" target="_blank"><i class="fab fa-facebook"></i></a>
                        </div>
                    </div>
                </div>
                <form class="contact-form" id="contactForm" action="https://formspree.io/f/mblqrozq" method="POST">
                    <div class="form-group">
                        <label for="name">Nombre completo *</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email *</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="phone">Teléfono</label>
                        <input type="tel" id="phone" name="phone">
                    </div>
                    <div class="form-group">
                        <label for="service">Servicio de interés</label>
                        <select id="service" name="service">
                            <option value="">Selecciona un servicio</option>
                            <option value="contabilidad">Contabilidad y Finanzas</option>
                            <option value="legal">Legal y Regulatorio</option>
                            <option value="marketing">Marketing y Creatividad</option>
                            <option value="ia">Inteligencia Artificial</option>
                            <option value="integral">Consultoría Integral</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="message">Mensaje *</label>
                        <textarea id="message" name="message" rows="5" required></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">
                        <span>Enviar mensaje</span>
                        <i class="fas fa-paper-plane"></i>
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <div class="footer-logo">
                        <i class="fas fa-compass"></i>
                        <span>PRIX CONSULTORA</span>
                    </div>
                    <p>Tu socio estratégico en el camino del emprendimiento. Transformamos ideas en negocios exitosos.</p>
                </div>
                <div class="footer-section">
                    <h4>Servicios</h4>
                    <ul>
                        <li><a href="#servicios">Contabilidad y Finanzas</a></li>
                        <li><a href="#servicios">Legal y Regulatorio</a></li>
                        <li><a href="#servicios">Marketing y Creatividad</a></li>
                        <li><a href="#servicios">Inteligencia Artificial</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h4>Empresa</h4>
                    <ul>
                        <li><a href="#nosotros">Sobre Nosotros</a></li>
                        <li><a href="#proceso">Nuestro Proceso</a></li>
                        <li><a href="#testimonios">Testimonios</a></li>
                        <li><a href="#contacto">Contacto</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h4>Contacto</h4>
                    <ul>
                        <li><i class="fas fa-envelope"></i> info@prixconsultora.com</li>
                        <li><i class="fas fa-phone"></i> +34 XXX XXX XXX</li>
                        <li><i class="fas fa-map-marker-alt"></i> España</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 Prix Consultora. Todos los derechos reservados.</p>
                <div class="footer-social">
                    <a href="#" target="_blank"><i class="fab fa-linkedin"></i></a>
                    <a href="#" target="_blank"><i class="fab fa-instagram"></i></a>
                    <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
                    <a href="#" target="_blank"><i class="fab fa-facebook"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Notification Container -->
    <div id="notification-container"></div>

    <!-- Custom JavaScript -->
    <script src="js/main.js"></script>
</body>
</html>
```

---

## 🎨 css/style.css

```css
/* ============================================
   PRIX CONSULTING - CSS Stylesheet
   Modern, Professional & Responsive Design
   ============================================ */

/* ============================================
   ROOT VARIABLES & RESET
   ============================================ */
:root {
    /* Color Palette */
    --primary-color: #1e40af; /* Deep Blue */
    --primary-dark: #1e3a8a;
    --primary-light: #3b82f6;
    --secondary-color: #f59e0b; /* Amber/Golden */
    --secondary-dark: #d97706;
    --secondary-light: #fbbf24;
    
    /* Neutrals */
    --dark: #0f172a;
    --dark-grey: #1e293b;
    --grey: #64748b;
    --light-grey: #cbd5e1;
    --lighter-grey: #f1f5f9;
    --white: #ffffff;
    
    /* Gradients */
    --gradient-primary: linear-gradient(135deg, var(--primary-color) 0%, var(--primary-light) 100%);
    --gradient-secondary: linear-gradient(135deg, var(--secondary-dark) 0%, var(--secondary-light) 100%);
    --gradient-hero: linear-gradient(135deg, rgba(30, 64, 175, 0.95) 0%, rgba(30, 58, 138, 0.98) 100%);
    
    /* Spacing */
    --section-padding: 100px 0;
    --container-max-width: 1200px;
    
    /* Typography */
    --font-primary: 'Inter', sans-serif;
    --font-heading: 'Poppins', sans-serif;
    
    /* Shadows */
    --shadow-sm: 0 2px 8px rgba(0, 0, 0, 0.08);
    --shadow-md: 0 4px 16px rgba(0, 0, 0, 0.1);
    --shadow-lg: 0 8px 32px rgba(0, 0, 0, 0.12);
    --shadow-xl: 0 12px 48px rgba(0, 0, 0, 0.15);
    
    /* Transitions */
    --transition-fast: 0.2s ease;
    --transition-normal: 0.3s ease;
    --transition-slow: 0.5s ease;
    
    /* Border Radius */
    --radius-sm: 8px;
    --radius-md: 12px;
    --radius-lg: 16px;
    --radius-xl: 24px;
}

/* Reset & Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: var(--font-primary);
    color: var(--dark);
    line-height: 1.7;
    background-color: var(--white);
    overflow-x: hidden;
}

/* ============================================
   TYPOGRAPHY
   ============================================ */
h1, h2, h3, h4, h5, h6 {
    font-family: var(--font-heading);
    font-weight: 700;
    line-height: 1.3;
    color: var(--dark);
}

h1 { font-size: 3.5rem; }
h2 { font-size: 2.5rem; }
h3 { font-size: 1.75rem; }
h4 { font-size: 1.5rem; }

p {
    font-size: 1.1rem;
    line-height: 1.8;
    color: var(--grey);
}

a {
    text-decoration: none;
    color: inherit;
    transition: var(--transition-normal);
}

ul {
    list-style: none;
}

img {
    max-width: 100%;
    height: auto;
}

/* ============================================
   CONTAINER
   ============================================ */
.container {
    max-width: var(--container-max-width);
    margin: 0 auto;
    padding: 0 2rem;
}

/* ============================================
   NAVIGATION
   ============================================ */
.navbar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(10px);
    box-shadow: var(--shadow-sm);
    z-index: 1000;
    transition: var(--transition-normal);
}

.navbar.scrolled {
    box-shadow: var(--shadow-md);
}

.nav-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 0;
}

.logo {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    font-family: var(--font-heading);
    font-size: 1.5rem;
    font-weight: 800;
    color: var(--primary-color);
}

.logo i {
    font-size: 2rem;
    color: var(--secondary-color);
}

.nav-menu {
    display: flex;
    gap: 2rem;
    align-items: center;
}

.nav-link {
    font-weight: 500;
    color: var(--dark);
    padding: 0.5rem 0;
    position: relative;
}

.nav-link::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 0;
    height: 2px;
    background: var(--secondary-color);
    transition: var(--transition-normal);
}

.nav-link:hover::after {
    width: 100%;
}

.btn-nav {
    background: var(--gradient-primary);
    color: var(--white);
    padding: 0.75rem 1.5rem;
    border-radius: var(--radius-md);
}

.btn-nav::after {
    display: none;
}

.btn-nav:hover {
    transform: translateY(-2px);
    box-shadow: var(--shadow-md);
}

.menu-toggle {
    display: none;
    flex-direction: column;
    gap: 0.4rem;
    background: none;
    border: none;
    cursor: pointer;
    padding: 0.5rem;
}

.menu-toggle span {
    width: 25px;
    height: 3px;
    background: var(--dark);
    border-radius: 2px;
    transition: var(--transition-normal);
}

/* ============================================
   HERO SECTION
   ============================================ */
.hero {
    position: relative;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: var(--gradient-primary);
    color: var(--white);
    padding-top: 80px;
    overflow: hidden;
}

.hero::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="%23ffffff" fill-opacity="0.05" d="M0,96L48,112C96,128,192,160,288,160C384,160,480,128,576,112C672,96,768,96,864,112C960,128,1056,160,1152,160C1248,160,1344,128,1392,112L1440,96L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>');
    background-size: cover;
    background-position: bottom;
}

.hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: linear-gradient(135deg, rgba(30, 64, 175, 0.9) 0%, rgba(30, 58, 138, 0.95) 100%);
}

.hero-content {
    position: relative;
    z-index: 1;
    text-align: center;
    max-width: 900px;
}

.hero-title {
    font-size: 4rem;
    font-weight: 800;
    margin-bottom: 1.5rem;
    color: var(--white);
    text-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
}

.hero-subtitle {
    font-size: 1.5rem;
    margin-bottom: 2.5rem;
    color: rgba(255, 255, 255, 0.95);
    font-weight: 400;
}

.hero-cta {
    display: flex;
    gap: 1.5rem;
    justify-content: center;
    flex-wrap: wrap;
}

/* ============================================
   BUTTONS
   ============================================ */
.btn {
    display: inline-flex;
    align-items: center;
    gap: 0.75rem;
    padding: 1rem 2rem;
    font-size: 1.1rem;
    font-weight: 600;
    border-radius: var(--radius-md);
    transition: var(--transition-normal);
    cursor: pointer;
    border: none;
    text-align: center;
}

.btn-primary {
    background: var(--secondary-color);
    color: var(--white);
    box-shadow: var(--shadow-md);
}

.btn-primary:hover {
    background: var(--secondary-dark);
    transform: translateY(-3px);
    box-shadow: var(--shadow-lg);
}

.btn-secondary {
    background: var(--white);
    color: var(--primary-color);
    box-shadow: var(--shadow-md);
}

.btn-secondary:hover {
    background: var(--lighter-grey);
    transform: translateY(-3px);
    box-shadow: var(--shadow-lg);
}

.btn-large {
    padding: 1.25rem 2.5rem;
    font-size: 1.2rem;
}

/* ============================================
   SECTIONS
   ============================================ */
section {
    padding: var(--section-padding);
}

.section-header {
    text-align: center;
    margin-bottom: 4rem;
}

.section-title {
    font-size: 3rem;
    margin-bottom: 1rem;
    color: var(--dark);
}

.section-description {
    font-size: 1.25rem;
    color: var(--grey);
    max-width: 700px;
    margin: 0 auto;
}

/* ============================================
   ABOUT SECTION
   ============================================ */
.section-about {
    background: var(--lighter-grey);
}

.about-content {
    max-width: 900px;
    margin: 0 auto;
}

.about-text h3 {
    font-size: 2rem;
    margin-bottom: 1.5rem;
    color: var(--primary-color);
}

.about-text p {
    margin-bottom: 1.5rem;
}

.about-text strong {
    color: var(--primary-color);
    font-weight: 600;
}

.about-stats {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 2rem;
    margin-top: 3rem;
}

.stat-item {
    text-align: center;
    padding: 2rem;
    background: var(--white);
    border-radius: var(--radius-lg);
    box-shadow: var(--shadow-sm);
    transition: var(--transition-normal);
}

.stat-item:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-md);
}

.stat-number {
    font-size: 3rem;
    font-weight: 800;
    color: var(--secondary-color);
    margin-bottom: 0.5rem;
}

.stat-label {
    font-size: 1rem;
    color: var(--grey);
}

/* ============================================
   SERVICES SECTION
   ============================================ */
.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 2rem;
}

.service-card {
    background: var(--white);
    padding: 2.5rem;
    border-radius: var(--radius-lg);
    box-shadow: var(--shadow-md);
    transition: var(--transition-normal);
    position: relative;
    overflow: hidden;
}

.service-card::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 4px;
    background: var(--gradient-secondary);
    transform: scaleX(0);
    transition: var(--transition-normal);
}

.service-card:hover::before {
    transform: scaleX(1);
}

.service-card:hover {
    transform: translateY(-10px);
    box-shadow: var(--shadow-xl);
}

.service-card.featured {
    border: 2px solid var(--secondary-color);
}

.service-badge {
    position: absolute;
    top: 1rem;
    right: 1rem;
    background: var(--gradient-secondary);
    color: var(--white);
    padding: 0.5rem 1rem;
    border-radius: var(--radius-sm);
    font-size: 0.85rem;
    font-weight: 600;
}

.service-icon {
    width: 80px;
    height: 80px;
    background: var(--gradient-primary);
    border-radius: var(--radius-lg);
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 1.5rem;
}

.service-icon i {
    font-size: 2.5rem;
    color: var(--white);
}

.service-card h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    color: var(--dark);
}

.service-card p {
    margin-bottom: 1.5rem;
}

.service-features {
    margin-top: 1.5rem;
}

.service-features li {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    margin-bottom: 0.75rem;
    color: var(--grey);
}

.service-features i {
    color: var(--secondary-color);
    font-size: 1rem;
}

/* ============================================
   PROCESS SECTION
   ============================================ */
.section-process {
    background: var(--lighter-grey);
}

.process-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    align-items: stretch;
}

.process-step {
    background: var(--white);
    padding: 2.5rem;
    border-radius: var(--radius-lg);
    box-shadow: var(--shadow-sm);
    text-align: center;
    position: relative;
    transition: var(--transition-normal);
    display: flex;
    flex-direction: column;
    height: 100%;
}

.process-step:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-md);
}

.process-number {
    position: absolute;
    top: -1rem;
    right: 1.5rem;
    font-size: 4rem;
    font-weight: 900;
    color: var(--secondary-light);
    opacity: 0.3;
}

.process-icon {
    width: 80px;
    height: 80px;
    background: var(--gradient-secondary);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 1.5rem;
}

.process-icon i {
    font-size: 2rem;
    color: var(--white);
}

.process-step h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    color: var(--primary-color);
}

.process-step p {
    font-size: 1rem;
}

/* ============================================
   WHY CHOOSE US SECTION
   ============================================ */
.why-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.why-card {
    background: var(--white);
    padding: 2.5rem;
    border-radius: var(--radius-lg);
    box-shadow: var(--shadow-md);
    text-align: center;
    transition: var(--transition-normal);
}

.why-card:hover {
    transform: translateY(-10px);
    box-shadow: var(--shadow-xl);
}

.why-icon {
    width: 100px;
    height: 100px;
    background: var(--gradient-primary);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 1.5rem;
}

.why-icon i {
    font-size: 3rem;
    color: var(--white);
}

.why-card h3 {
    font-size: 1.75rem;
    margin-bottom: 1rem;
    color: var(--dark);
}

.why-card p {
    font-size: 1rem;
}

/* ============================================
   TESTIMONIALS SECTION
   ============================================ */
.section-testimonials {
    background: var(--lighter-grey);
}

.testimonials-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.testimonial-card {
    background: var(--white);
    padding: 2.5rem;
    border-radius: var(--radius-lg);
    box-shadow: var(--shadow-md);
    transition: var(--transition-normal);
}

.testimonial-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-lg);
}

.testimonial-rating {
    display: flex;
    gap: 0.25rem;
    margin-bottom: 1.5rem;
}

.testimonial-rating i {
    color: var(--secondary-color);
    font-size: 1.25rem;
}

.testimonial-content p {
    font-style: italic;
    margin-bottom: 2rem;
    color: var(--dark);
}

.testimonial-author {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.author-avatar {
    width: 60px;
    height: 60px;
    background: var(--gradient-primary);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.author-avatar i {
    font-size: 1.75rem;
    color: var(--white);
}

.author-info h4 {
    font-size: 1.1rem;
    color: var(--dark);
    margin-bottom: 0.25rem;
}

.author-info p {
    font-size: 0.95rem;
    color: var(--grey);
}

/* ============================================
   CTA SECTION
   ============================================ */
.section-cta {
    background: var(--gradient-primary);
    color: var(--white);
    text-align: center;
}

.cta-content h2 {
    font-size: 3rem;
    color: var(--white);
    margin-bottom: 1.5rem;
}

.cta-content p {
    font-size: 1.25rem;
    color: rgba(255, 255, 255, 0.95);
    margin-bottom: 2.5rem;
    max-width: 700px;
    margin-left: auto;
    margin-right: auto;
}

/* ============================================
   CONTACT SECTION
   ============================================ */
.contact-wrapper {
    display: grid;
    grid-template-columns: 1fr 1.5fr;
    gap: 3rem;
    align-items: start;
}

.contact-info h3 {
    font-size: 2rem;
    margin-bottom: 2rem;
    color: var(--primary-color);
}

.contact-item {
    display: flex;
    gap: 1.5rem;
    margin-bottom: 2rem;
}

.contact-item i {
    font-size: 1.5rem;
    color: var(--secondary-color);
    width: 40px;
    height: 40px;
    background: var(--lighter-grey);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
}

.contact-item h4 {
    font-size: 1.1rem;
    color: var(--dark);
    margin-bottom: 0.5rem;
}

.contact-item p {
    color: var(--grey);
}

.contact-social {
    margin-top: 3rem;
}

.contact-social h4 {
    font-size: 1.1rem;
    color: var(--dark);
    margin-bottom: 1rem;
}

.social-links {
    display: flex;
    gap: 1rem;
}

.social-links a {
    width: 45px;
    height: 45px;
    background: var(--gradient-primary);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--white);
    font-size: 1.25rem;
    transition: var(--transition-normal);
}

.social-links a:hover {
    transform: translateY(-3px);
    box-shadow: var(--shadow-md);
}

/* ============================================
   CONTACT FORM
   ============================================ */
.contact-form {
    background: var(--lighter-grey);
    padding: 2.5rem;
    border-radius: var(--radius-lg);
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-group label {
    display: block;
    font-weight: 600;
    color: var(--dark);
    margin-bottom: 0.5rem;
}

.form-group input,
.form-group select,
.form-group textarea {
    width: 100%;
    padding: 1rem;
    border: 2px solid var(--light-grey);
    border-radius: var(--radius-sm);
    font-family: var(--font-primary);
    font-size: 1rem;
    transition: var(--transition-normal);
    background: var(--white);
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
    outline: none;
    border-color: var(--primary-color);
    box-shadow: 0 0 0 3px rgba(30, 64, 175, 0.1);
}

.form-group textarea {
    resize: vertical;
    min-height: 120px;
}

.contact-form .btn {
    width: 100%;
    justify-content: center;
}

/* ============================================
   FOOTER
   ============================================ */
.footer {
    background: var(--dark);
    color: var(--light-grey);
    padding: 4rem 0 2rem;
}

.footer-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 3rem;
    margin-bottom: 3rem;
}

.footer-logo {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    font-family: var(--font-heading);
    font-size: 1.5rem;
    font-weight: 800;
    color: var(--white);
    margin-bottom: 1rem;
}

.footer-logo i {
    font-size: 2rem;
    color: var(--secondary-color);
}

.footer-section p {
    margin-bottom: 1rem;
    line-height: 1.6;
}

.footer-section h4 {
    color: var(--white);
    margin-bottom: 1.5rem;
    font-size: 1.25rem;
}

.footer-section ul li {
    margin-bottom: 0.75rem;
}

.footer-section ul li a {
    color: var(--light-grey);
    transition: var(--transition-fast);
}

.footer-section ul li a:hover {
    color: var(--secondary-color);
    padding-left: 0.5rem;
}

.footer-section ul li i {
    color: var(--secondary-color);
    margin-right: 0.75rem;
    width: 20px;
}

.footer-bottom {
    border-top: 1px solid var(--dark-grey);
    padding-top: 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 1rem;
}

.footer-social {
    display: flex;
    gap: 1rem;
}

.footer-social a {
    width: 40px;
    height: 40px;
    background: var(--dark-grey);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    color: var(--light-grey);
    transition: var(--transition-normal);
}

.footer-social a:hover {
    background: var(--secondary-color);
    color: var(--white);
    transform: translateY(-3px);
}

/* ============================================
   NOTIFICATIONS
   ============================================ */
#notification-container {
    position: fixed;
    top: 100px;
    right: 20px;
    z-index: 10000;
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.notification {
    min-width: 300px;
    max-width: 400px;
    padding: 1.25rem;
    background: var(--white);
    border-radius: var(--radius-md);
    box-shadow: var(--shadow-xl);
    display: flex;
    align-items: start;
    gap: 1rem;
    animation: slideIn 0.3s ease;
}

@keyframes slideIn {
    from {
        transform: translateX(400px);
        opacity: 0;
    }
    to {
        transform: translateX(0);
        opacity: 1;
    }
}

.notification-icon {
    font-size: 1.5rem;
    flex-shrink: 0;
}

.notification.success {
    border-left: 4px solid #10b981;
}

.notification.success .notification-icon {
    color: #10b981;
}

.notification.error {
    border-left: 4px solid #ef4444;
}

.notification.error .notification-icon {
    color: #ef4444;
}

.notification-content h4 {
    font-size: 1rem;
    margin-bottom: 0.25rem;
    color: var(--dark);
}

.notification-content p {
    font-size: 0.9rem;
    color: var(--grey);
}

.notification-close {
    background: none;
    border: none;
    color: var(--grey);
    cursor: pointer;
    padding: 0;
    margin-left: auto;
    font-size: 1.25rem;
    transition: var(--transition-fast);
}

.notification-close:hover {
    color: var(--dark);
}

/* ============================================
   ANIMATIONS
   ============================================ */
.fade-in {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.6s ease, transform 0.6s ease;
}

.fade-in.visible {
    opacity: 1;
    transform: translateY(0);
}

/* ============================================
   RESPONSIVE DESIGN
   ============================================ */

/* Tablet */
@media (max-width: 1024px) {
    :root {
        --section-padding: 80px 0;
    }
    
    .hero-title {
        font-size: 3rem;
    }
    
    .section-title {
        font-size: 2.5rem;
    }
    
    .services-grid,
    .process-grid,
    .why-grid,
    .testimonials-grid {
        grid-template-columns: repeat(2, 1fr);
    }
    
    .contact-wrapper {
        grid-template-columns: 1fr;
    }
}

/* Mobile */
@media (max-width: 768px) {
    .nav-menu {
        position: fixed;
        top: 80px;
        left: 0;
        right: 0;
        background: var(--white);
        flex-direction: column;
        padding: 2rem;
        box-shadow: var(--shadow-lg);
        transform: translateY(-100%);
        opacity: 0;
        visibility: hidden;
        transition: var(--transition-normal);
    }
    
    .nav-menu.active {
        transform: translateY(0);
        opacity: 1;
        visibility: visible;
    }
    
    .menu-toggle {
        display: flex;
    }
    
    .hero-title {
        font-size: 2.5rem;
    }
    
    .hero-subtitle {
        font-size: 1.25rem;
    }
    
    .hero-cta {
        flex-direction: column;
    }
    
    .section-title {
        font-size: 2rem;
    }
    
    .services-grid,
    .process-grid,
    .why-grid,
    .testimonials-grid {
        grid-template-columns: 1fr;
    }
    
    .about-stats {
        grid-template-columns: 1fr;
    }
    
    .footer-bottom {
        flex-direction: column;
        text-align: center;
    }
}

/* Small Mobile */
@media (max-width: 480px) {
    .container {
        padding: 0 1rem;
    }
    
    .hero-title {
        font-size: 2rem;
    }
    
    .hero-subtitle {
        font-size: 1.1rem;
    }
    
    .section-title {
        font-size: 1.75rem;
    }
    
    .btn {
        padding: 0.875rem 1.5rem;
        font-size: 1rem;
    }
    
    .service-card,
    .process-step,
    .why-card,
    .testimonial-card {
        padding: 1.5rem;
    }
    
    .contact-form {
        padding: 1.5rem;
    }
}
```

---

## 🎯 js/main.js

```javascript
/**
 * PRIX CONSULTING - JavaScript
 * Interactive functionality and animations
 */

// ============================================
// DOM CONTENT LOADED
// ============================================
document.addEventListener('DOMContentLoaded', function() {
    // Initialize all components
    initNavigation();
    initScrollAnimations();
    initContactForm();
    initSmoothScroll();
    initAOS();
});

// ============================================
// NAVIGATION
// ============================================
function initNavigation() {
    const navbar = document.getElementById('navbar');
    const menuToggle = document.getElementById('menuToggle');
    const navMenu = document.getElementById('navMenu');
    const navLinks = document.querySelectorAll('.nav-menu a');
    
    // Navbar scroll effect
    window.addEventListener('scroll', function() {
        if (window.scrollY > 50) {
            navbar.classList.add('scrolled');
        } else {
            navbar.classList.remove('scrolled');
        }
    });
    
    // Mobile menu toggle
    menuToggle.addEventListener('click', function() {
        navMenu.classList.toggle('active');
        menuToggle.classList.toggle('active');
        
        // Animate hamburger icon
        const spans = menuToggle.querySelectorAll('span');
        if (menuToggle.classList.contains('active')) {
            spans[0].style.transform = 'rotate(45deg) translateY(10px)';
            spans[1].style.opacity = '0';
            spans[2].style.transform = 'rotate(-45deg) translateY(-10px)';
        } else {
            spans[0].style.transform = '';
            spans[1].style.opacity = '';
            spans[2].style.transform = '';
        }
    });
    
    // Close mobile menu when clicking on a link
    navLinks.forEach(link => {
        link.addEventListener('click', function() {
            navMenu.classList.remove('active');
            menuToggle.classList.remove('active');
            
            const spans = menuToggle.querySelectorAll('span');
            spans[0].style.transform = '';
            spans[1].style.opacity = '';
            spans[2].style.transform = '';
        });
    });
    
    // Close mobile menu when clicking outside
    document.addEventListener('click', function(e) {
        if (!navMenu.contains(e.target) && !menuToggle.contains(e.target)) {
            navMenu.classList.remove('active');
            menuToggle.classList.remove('active');
            
            const spans = menuToggle.querySelectorAll('span');
            spans[0].style.transform = '';
            spans[1].style.opacity = '';
            spans[2].style.transform = '';
        }
    });
}

// ============================================
// SMOOTH SCROLL
// ============================================
function initSmoothScroll() {
    const links = document.querySelectorAll('a[href^="#"]');
    
    links.forEach(link => {
        link.addEventListener('click', function(e) {
            const href = this.getAttribute('href');
            
            // Don't prevent default for non-section links
            if (href === '#' || href.length <= 1) return;
            
            const target = document.querySelector(href);
            if (target) {
                e.preventDefault();
                const offsetTop = target.offsetTop - 80; // Account for fixed navbar
                
                window.scrollTo({
                    top: offsetTop,
                    behavior: 'smooth'
                });
            }
        });
    });
}

// ============================================
// SCROLL ANIMATIONS
// ============================================
function initScrollAnimations() {
    const observerOptions = {
        threshold: 0.1,
        rootMargin: '0px 0px -100px 0px'
    };
    
    const observer = new IntersectionObserver(function(entries) {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                entry.target.style.opacity = '1';
                entry.target.style.transform = 'translateY(0)';
            }
        });
    }, observerOptions);
    
    // Observe all sections
    const sections = document.querySelectorAll('section');
    sections.forEach(section => {
        section.style.opacity = '0';
        section.style.transform = 'translateY(30px)';
        section.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
        observer.observe(section);
    });
}

// ============================================
// ANIMATED NUMBERS (Stats Counter)
// ============================================
function animateNumbers() {
    const stats = document.querySelectorAll('.stat-number');
    const observer = new IntersectionObserver(entries => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                const target = entry.target;
                const value = target.textContent;
                
                // Only animate if not already animated
                if (!target.classList.contains('animated')) {
                    target.classList.add('animated');
                    
                    // Check if value contains numbers
                    if (/\d/.test(value)) {
                        const num = parseInt(value.replace(/\D/g, ''));
                        if (!isNaN(num)) {
                            animateValue(target, 0, num, 1500, value);
                        }
                    }
                }
            }
        });
    }, { threshold: 0.5 });
    
    stats.forEach(stat => observer.observe(stat));
}

function animateValue(element, start, end, duration, originalText) {
    const range = end - start;
    const increment = range / (duration / 16);
    let current = start;
    
    const timer = setInterval(() => {
        current += increment;
        if (current >= end) {
            current = end;
            clearInterval(timer);
        }
        
        // Preserve original text format
        if (originalText.includes('°')) {
            element.textContent = Math.floor(current) + '°';
        } else if (originalText.includes('%')) {
            element.textContent = Math.floor(current) + '%';
        } else {
            element.textContent = Math.floor(current);
        }
    }, 16);
}

// Initialize number animation
setTimeout(animateNumbers, 500);

// ============================================
// ANIMATE ON SCROLL (AOS)
// ============================================
function initAOS() {
    const elements = document.querySelectorAll('[data-aos]');
    
    const observerOptions = {
        threshold: 0.15,
        rootMargin: '0px 0px -50px 0px'
    };
    
    const observer = new IntersectionObserver(function(entries) {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                const delay = entry.target.getAttribute('data-aos-delay') || 0;
                
                setTimeout(() => {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }, delay);
                
                observer.unobserve(entry.target);
            }
        });
    }, observerOptions);
    
    elements.forEach(element => {
        element.style.opacity = '0';
        element.style.transform = 'translateY(30px)';
        element.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
        observer.observe(element);
    });
}

// ============================================
// CONTACT FORM
// ============================================
function initContactForm() {
    const form = document.getElementById('contactForm');
    
    if (!form) return;
    
    form.addEventListener('submit', async function(e) {
        e.preventDefault();
        
        // Get form data
        const formData = {
            name: document.getElementById('name').value,
            email: document.getElementById('email').value,
            phone: document.getElementById('phone').value,
            service: document.getElementById('service').value,
            message: document.getElementById('message').value
        };
        
        // Validate form
        if (!validateForm(formData)) {
            return;
        }
        
        // Show loading state
        const submitBtn = form.querySelector('button[type="submit"]');
        const originalText = submitBtn.innerHTML;
        submitBtn.disabled = true;
        submitBtn.innerHTML = '<span>Enviando...</span> <i class="fas fa-spinner fa-spin"></i>';
        
        try {
            // Send to FormSpree
            const response = await fetch(form.action, {
                method: 'POST',
                body: new FormData(form),
                headers: {
                    'Accept': 'application/json'
                }
            });
            
            if (response.ok) {
                // Success message
                showNotification('¡Mensaje enviado exitosamente! Nos pondremos en contacto contigo pronto.', 'success');
                
                // Track conversion in Google Analytics
                if (typeof gtag !== 'undefined') {
                    gtag('event', 'form_submission', {
                        'event_category': 'Contact',
                        'event_label': 'Contact Form Submitted',
                        'value': 1
                    });
                }
                
                // Reset form
                form.reset();
            } else {
                throw new Error('Error al enviar el mensaje');
            }
        } catch (error) {
            // Error message
            showNotification('Hubo un error al enviar el mensaje. Por favor, intenta nuevamente o contáctanos directamente.', 'error');
        } finally {
            // Restore button
            submitBtn.disabled = false;
            submitBtn.innerHTML = originalText;
        }
    });
}

function validateForm(data) {
    // Validate name
    if (!data.name || data.name.trim().length < 3) {
        showNotification('Por favor, ingresa un nombre válido (mínimo 3 caracteres).', 'error');
        return false;
    }
    
    // Validate email
    const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    if (!data.email || !emailRegex.test(data.email)) {
        showNotification('Por favor, ingresa un email válido.', 'error');
        return false;
    }
    
    // Validate service selection
    if (!data.service) {
        showNotification('Por favor, selecciona un servicio de interés.', 'error');
        return false;
    }
    
    // Validate message
    if (!data.message || data.message.trim().length < 10) {
        showNotification('Por favor, ingresa un mensaje (mínimo 10 caracteres).', 'error');
        return false;
    }
    
    return true;
}

// ============================================
// NOTIFICATION SYSTEM
// ============================================
function showNotification(message, type = 'info') {
    // Remove existing notification if any
    const existingNotification = document.querySelector('.notification');
    if (existingNotification) {
        existingNotification.remove();
    }
    
    // Create notification element
    const notification = document.createElement('div');
    notification.className = `notification notification-${type}`;
    notification.innerHTML = `
        <div class="notification-content">
            <i class="fas ${type === 'success' ? 'fa-check-circle' : 'fa-exclamation-circle'}"></i>
            <span>${message}</span>
        </div>
        <button class="notification-close">
            <i class="fas fa-times"></i>
        </button>
    `;
    
    // Add styles
    notification.style.cssText = `
        position: fixed;
        top: 100px;
        right: 20px;
        background: ${type === 'success' ? '#10b981' : '#ef4444'};
        color: white;
        padding: 1rem 1.5rem;
        border-radius: 12px;
        box-shadow: 0 8px 32px rgba(0, 0, 0, 0.15);
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 1rem;
        max-width: 400px;
        z-index: 10000;
        animation: slideInRight 0.4s ease;
    `;
    
    // Add to body
    document.body.appendChild(notification);
    
    // Close button functionality
    const closeBtn = notification.querySelector('.notification-close');
    closeBtn.style.cssText = `
        background: transparent;
        border: none;
        color: white;
        cursor: pointer;
        font-size: 1.2rem;
        padding: 0;
        display: flex;
        align-items: center;
    `;
    
    closeBtn.addEventListener('click', () => {
        notification.style.animation = 'slideOutRight 0.4s ease';
        setTimeout(() => notification.remove(), 400);
    });
    
    // Auto remove after 5 seconds
    setTimeout(() => {
        if (notification.parentElement) {
            notification.style.animation = 'slideOutRight 0.4s ease';
            setTimeout(() => notification.remove(), 400);
        }
    }, 5000);
}

// Add notification animations to document
const style = document.createElement('style');
style.textContent = `
    @keyframes slideInRight {
        from {
            transform: translateX(100%);
            opacity: 0;
        }
        to {
            transform: translateX(0);
            opacity: 1;
        }
    }
    
    @keyframes slideOutRight {
        from {
            transform: translateX(0);
            opacity: 1;
        }
        to {
            transform: translateX(100%);
            opacity: 0;
        }
    }
    
    .notification-content {
        display: flex;
        align-items: center;
        gap: 0.75rem;
    }
    
    .notification-content i {
        font-size: 1.5rem;
    }
`;
document.head.appendChild(style);

// ============================================
// PARALLAX EFFECT (Hero Shapes)
// ============================================
window.addEventListener('scroll', function() {
    const scrolled = window.pageYOffset;
    const shapes = document.querySelectorAll('.hero-shapes .shape');
    
    shapes.forEach((shape, index) => {
        const speed = (index + 1) * 0.05;
        shape.style.transform = `translateY(${scrolled * speed}px)`;
    });
});

// ============================================
// ACTIVE SECTION HIGHLIGHTING IN NAV
// ============================================
function highlightActiveSection() {
    const sections = document.querySelectorAll('section[id]');
    const navLinks = document.querySelectorAll('.nav-menu a[href^="#"]');
    
    window.addEventListener('scroll', () => {
        const scrollY = window.pageYOffset;
        
        sections.forEach(section => {
            const sectionHeight = section.offsetHeight;
            const sectionTop = section.offsetTop - 100;
            const sectionId = section.getAttribute('id');
            
            if (scrollY > sectionTop && scrollY <= sectionTop + sectionHeight) {
                navLinks.forEach(link => {
                    link.classList.remove('active');
                    if (link.getAttribute('href') === `#${sectionId}`) {
                        link.classList.add('active');
                    }
                });
            }
        });
    });
}

highlightActiveSection();

// ============================================
// PREVENT FOUC (Flash of Unstyled Content)
// ============================================
window.addEventListener('load', function() {
    document.body.style.opacity = '1';
});

// ============================================
// UTILITY FUNCTIONS
// ============================================

/**
 * Debounce function to limit function execution rate
 */
function debounce(func, wait) {
    let timeout;
    return function executedFunction(...args) {
        const later = () => {
            clearTimeout(timeout);
            func(...args);
        };
        clearTimeout(timeout);
        timeout = setTimeout(later, wait);
    };
}

/**
 * Check if element is in viewport
 */
function isInViewport(element) {
    const rect = element.getBoundingClientRect();
    return (
        rect.top >= 0 &&
        rect.left >= 0 &&
        rect.bottom <= (window.innerHeight || document.documentElement.clientHeight) &&
        rect.right <= (window.innerWidth || document.documentElement.clientWidth)
    );
}

/**
 * Get scroll percentage
 */
function getScrollPercentage() {
    const scrollTop = window.pageYOffset || document.documentElement.scrollTop;
    const scrollHeight = document.documentElement.scrollHeight - document.documentElement.clientHeight;
    return (scrollTop / scrollHeight) * 100;
}

// ============================================
// CONSOLE MESSAGE
// ============================================
console.log('%c🧭 PRIX CONSULTORA', 'font-size: 20px; font-weight: bold; color: #1e40af;');
console.log('%cWeb desarrollado con ❤️', 'font-size: 14px; color: #f59e0b;');
console.log('%cTransformamos ideas en negocios sólidos', 'font-size: 12px; color: #64748b;');
``` 

---

## 📝 Archivos de Imágenes

**Imágenes en el proyecto:**

1. `images/og-image.jpg` (1200x630px) - Open Graph image
2. `images/logo-prix.png` (500x500px) - Logo original
3. Favicon: SVG inline en el HTML

---

## 📦 Instrucciones de Instalación Local

**Para usar este código en tu computadora:**

1. **Crea una carpeta** llamada `prixconsultora`

2. **Crea la estructura:**
```
prixconsultora/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   └── og-image.jpg
└── README.md
```

3. **Copia el código** de cada sección a su archivo correspondiente

4. **Abre index.html** en tu navegador

5. **Para editar:** Usa cualquier editor de código (VS Code, Sublime, etc.)

---

## 🔧 Configuraciones a Actualizar

**Cuando el dominio esté activo, cambiar:**

- URLs en meta tags (de ivlzbaxx.gensparkspace.com a prixconsultora.com)
- Google Analytics ID (ya está configurado: G-HY8SPB4B8P)
- FormSpree endpoint (ya está: mblqrozq)
- Links de redes sociales cuando se creen

---

**¿Necesitas el archivo JavaScript completo también o así está bien?** 🚀
