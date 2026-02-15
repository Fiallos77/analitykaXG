---
layout: default
title: Inicio
lang: es
---

<style>
    :root {
        --bg-primary: #0B1120;
        --bg-secondary: #141B2E;
        --bg-card: #1A2332;
        --accent-cyan: #00E5FF;
        --accent-green: #00FF88;
        --accent-red: #FF4A6B;
        --text-primary: #F0F4F8;
        --text-secondary: #7C8BA1;
        --border-color: rgba(0, 229, 255, 0.1);
    }

    /* HERO SECTION CON FOTO */
    .hero-section {
        padding: 80px 0 60px;
        text-align: center;
        position: relative;
    }

    .hero-content {
        max-width: 900px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 32px;
    }

    /* Foto Profesional */
    .profile-photo {
        width: 200px;
        height: 200px;
        border-radius: 50%;
        border: 4px solid var(--accent-cyan);
        box-shadow: 0 0 60px rgba(0, 229, 255, 0.4);
        object-fit: cover;
        object-position: center;
        animation: fadeInScale 0.8s ease-out;
    }

    @keyframes fadeInScale {
        from {
            opacity: 0;
            transform: scale(0.8);
        }
        to {
            opacity: 1;
            transform: scale(1);
        }
    }

    .hero-text {
        text-align: center;
    }

    .hero-text h1 {
        font-family: 'Montserrat', sans-serif;
        font-size: 56px;
        font-weight: 900;
        margin-bottom: 16px;
        background: linear-gradient(135deg, var(--text-primary) 0%, var(--accent-cyan) 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
        line-height: 1.2;
    }

    .hero-text .subtitle {
        font-size: 18px;
        color: var(--accent-cyan);
        font-weight: 600;
        margin-bottom: 16px;
        text-transform: uppercase;
        letter-spacing: 2px;
    }

    .hero-text .tagline {
        font-size: 18px;
        color: var(--text-secondary);
        max-width: 700px;
        margin: 0 auto 32px;
        line-height: 1.8;
    }

    .hero-text .tagline strong {
        color: var(--accent-cyan);
        font-weight: 600;
    }

    /* CTA Buttons */
    .hero-cta {
        display: flex;
        gap: 16px;
        justify-content: center;
        flex-wrap: wrap;
    }

    .cta-primary {
        display: inline-flex;
        align-items: center;
        gap: 12px;
        padding: 16px 40px;
        background: var(--accent-cyan);
        color: var(--bg-primary);
        text-decoration: none;
        font-weight: 700;
        font-size: 16px;
        border-radius: 8px;
        transition: all 0.3s ease;
        box-shadow: 0 0 30px rgba(0, 229, 255, 0.3);
    }

    .cta-primary:hover {
        transform: translateY(-2px);
        box-shadow: 0 8px 40px rgba(0, 229, 255, 0.5);
    }

    .cta-secondary {
        display: inline-flex;
        align-items: center;
        gap: 12px;
        padding: 16px 40px;
        background: transparent;
        color: var(--accent-cyan);
        text-decoration: none;
        font-weight: 700;
        font-size: 16px;
        border-radius: 8px;
        border: 2px solid var(--accent-cyan);
        transition: all 0.3s ease;
    }

    .cta-secondary:hover {
        background: var(--accent-cyan);
        color: var(--bg-primary);
    }

    /* STATS BAR */
    .stats-bar {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 24px;
        margin-top: 60px;
        padding: 40px;
        background: var(--bg-secondary);
        border-radius: 16px;
        border: 1px solid var(--border-color);
        max-width: 900px;
        margin-left: auto;
        margin-right: auto;
    }

    .stat-item {
        text-align: center;
    }

    .stat-number {
        font-family: 'Montserrat', sans-serif;
        font-size: 48px;
        font-weight: 900;
        color: var(--accent-cyan);
        display: block;
        margin-bottom: 8px;
    }

    .stat-label {
        font-size: 14px;
        color: var(--text-secondary);
        text-transform: uppercase;
        letter-spacing: 1px;
    }

    /* SECTION HEADERS */
    .section {
        padding: 80px 20px;
        max-width: 1200px;
        margin: 0 auto;
    }

    .section-header {
        text-align: center;
        margin-bottom: 60px;
    }

    .section-header h2 {
        font-family: 'Montserrat', sans-serif;
        font-size: 48px;
        font-weight: 900;
        margin-bottom: 16px;
        color: var(--text-primary);
    }

    .section-header p {
        font-size: 18px;
        color: var(--text-secondary);
        max-width: 600px;
        margin: 0 auto;
    }

    /* REPORTS GRID */
    .reports-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
        gap: 32px;
    }

    .report-card {
        background: var(--bg-card);
        border-radius: 16px;
        border: 1px solid var(--border-color);
        overflow: hidden;
        transition: all 0.3s ease;
        cursor: pointer;
        text-decoration: none;
        display: block;
    }

    .report-card:hover {
        transform: translateY(-8px);
        border-color: var(--accent-cyan);
        box-shadow: 0 12px 40px rgba(0, 229, 255, 0.2);
    }

    .report-thumbnail {
        width: 100%;
        height: 200px;
        background: linear-gradient(135deg, var(--bg-secondary) 0%, var(--bg-primary) 100%);
        display: flex;
        align-items: center;
        justify-content: center;
        border-bottom: 1px solid var(--border-color);
        overflow: hidden;
    }

    .report-thumbnail img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        opacity: 0.9;
    }

    .report-content {
        padding: 24px;
    }

    .report-tag {
        display: inline-block;
        padding: 4px 12px;
        background: rgba(0, 229, 255, 0.1);
        color: var(--accent-cyan);
        font-size: 12px;
        font-weight: 600;
        border-radius: 4px;
        text-transform: uppercase;
        letter-spacing: 0.5px;
        margin-bottom: 12px;
    }

    .report-card h3 {
        font-family: 'Montserrat', sans-serif;
        font-size: 22px;
        font-weight: 700;
        margin-bottom: 12px;
        color: var(--text-primary);
    }

    .report-meta {
        font-size: 14px;
        color: var(--text-secondary);
        margin-bottom: 16px;
        display: flex;
        gap: 12px;
        align-items: center;
    }

    .report-excerpt {
        font-size: 15px;
        color: var(--text-secondary);
        line-height: 1.7;
        margin-bottom: 20px;
    }

    .report-link {
        color: var(--accent-cyan);
        text-decoration: none;
        font-weight: 600;
        font-size: 14px;
        display: inline-flex;
        align-items: center;
        gap: 8px;
        transition: gap 0.3s ease;
    }

    .report-link:hover {
        gap: 12px;
    }

    /* METHODOLOGY GRID */
    .methodology-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 32px;
    }

    .method-card {
        background: var(--bg-card);
        padding: 32px;
        border-radius: 12px;
        border: 1px solid var(--border-color);
        transition: border-color 0.3s ease;
    }

    .method-card:hover {
        border-color: var(--accent-cyan);
    }

    .method-icon {
        width: 56px;
        height: 56px;
        background: rgba(0, 229, 255, 0.1);
        border-radius: 12px;
        display: flex;
        align-items: center;
        justify-content: center;
        margin-bottom: 20px;
        font-size: 28px;
    }

    .method-card h3 {
        font-family: 'Montserrat', sans-serif;
        font-size: 20px;
        font-weight: 700;
        margin-bottom: 12px;
        color: var(--text-primary);
    }

    .method-card p {
        color: var(--text-secondary);
        font-size: 15px;
        line-height: 1.7;
    }

    /* CTA SECTION */
    .cta-section {
        background: linear-gradient(135deg, var(--bg-secondary) 0%, var(--bg-card) 100%);
        border-radius: 24px;
        padding: 80px 40px;
        text-align: center;
        border: 1px solid var(--border-color);
        margin: 80px 20px;
        max-width: 1200px;
        margin-left: auto;
        margin-right: auto;
    }

    .cta-section h2 {
        font-family: 'Montserrat', sans-serif;
        font-size: 42px;
        font-weight: 900;
        margin-bottom: 20px;
        color: var(--text-primary);
    }

    .cta-section p {
        font-size: 18px;
        color: var(--text-secondary);
        margin-bottom: 40px;
        max-width: 600px;
        margin-left: auto;
        margin-right: auto;
    }

    /* RESPONSIVE */
    @media (max-width: 768px) {
        .hero-text h1 {
            font-size: 36px;
        }

        .profile-photo {
            width: 150px;
            height: 150px;
        }

        .stats-bar {
            grid-template-columns: 1fr;
            padding: 30px 20px;
        }

        .section-header h2 {
            font-size: 32px;
        }

        .hero-cta {
            flex-direction: column;
        }

        .cta-section {
            padding: 60px 30px;
        }

        .cta-section h2 {
            font-size: 32px;
        }
    }
</style>

<!-- HERO SECTION -->
<section class="hero-section">
    <div class="hero-content">
        <!-- Professional Photo -->
        <img src="{{ site.baseurl }}/assets/images/profile.jpg" alt="Football Data Analyst" class="profile-photo">
        
        <div class="hero-text">
            <p class="subtitle">Analista de Datos Futbolísticos</p>
            <h1>Inteligencia Táctica<br>A Través de Datos</h1>
            <p class="tagline">
                Análisis táctico de élite basado en <strong>modelos xG avanzados</strong>, 
                dominancia espacial y estructuras de presión. Transformando datos en decisiones para clubes profesionales.
            </p>
            
            <div class="hero-cta">
                <a href="#reports" class="cta-primary">
                    Ver Análisis
                    <span>→</span>
                </a>
                <a href="#methodology" class="cta-secondary">
                    Metodología
                </a>
            </div>
        </div>

        <!-- Stats Bar -->
        <div class="stats-bar">
            <div class="stat-item">
                <span class="stat-number">50+</span>
                <span class="stat-label">Reportes</span>
            </div>
            <div class="stat-item">
                <span class="stat-number">15</span>
                <span class="stat-label">Ligas</span>
            </div>
            <div class="stat-item">
                <span class="stat-number">Python</span>
                <span class="stat-label">Tech Stack</span>
            </div>
        </div>
    </div>
</section>

<!-- FEATURED REPORTS -->
<section class="section" id="reports">
    <div class="section-header">
        <h2>Últimos Análisis</h2>
        <p>Reportes tácticos basados en modelos propios de expected goals y análisis espacial</p>
    </div>

    <div class="reports-grid">
        <!-- Report Card - Argentina vs Ecuador -->
        <a href="{{ site.baseurl }}/es/reports/argentina-ecuador-2024" class="report-card">
            <div class="report-thumbnail">
                <img src="{{ site.baseurl }}/assets/images/Argentina1.jpg" alt="Argentina vs Ecuador">
            </div>
            <div class="report-content">
                <span class="report-tag">Análisis Post-Partido</span>
                <h3>Argentina vs Ecuador</h3>
                <div class="report-meta">
                    <span>Copa América 2024</span>
                    <span>•</span>
                    <span>Feb 2026</span>
                </div>
                <p class="report-excerpt">
                    Análisis de distribución espacial de amenazas con modelo de ventana de 15 segundos. 
                    Dominancia en zonas de finalización y patrones de presión.
                </p>
                <span class="report-link">
                    Leer análisis completo
                    <span>→</span>
                </span>
            </div>
        </a>

        <!-- More cards -->
        <a href="#" class="report-card">
            <div class="report-thumbnail">
                <div style="font-size: 64px; color: var(--accent-cyan); opacity: 0.3;">⚽</div>
            </div>
            <div class="report-content">
                <span class="report-tag">Scouting de Jugador</span>
                <h3>Próximamente</h3>
                <div class="report-meta">
                    <span>Análisis Individual</span>
                </div>
                <p class="report-excerpt">
                    Próximo análisis de jugador con radar comparativo y mapas de calor.
                </p>
                <span class="report-link">
                    Próximamente
                    <span>→</span>
                </span>
            </div>
        </a>

        <a href="#" class="report-card">
            <div class="report-thumbnail">
                <div style="font-size: 64px; color: var(--accent-cyan); opacity: 0.3;">🎯</div>
            </div>
            <div class="report-content">
                <span class="report-tag">Estudio Táctico</span>
                <h3>Próximamente</h3>
                <div class="report-meta">
                    <span>Análisis Táctico</span>
                </div>
                <p class="report-excerpt">
                    Análisis de estructuras de presión y generación de xG en transiciones.
                </p>
                <span class="report-link">
                    Próximamente
                    <span>→</span>
                </span>
            </div>
        </a>
    </div>
</section>

<!-- METHODOLOGY -->
<section class="section" id="methodology">
    <div class="section-header">
        <h2>Metodología</h2>
        <p>Modelos propios desarrollados en Python sobre datos de StatsBomb</p>
    </div>

    <div class="methodology-grid">
        <div class="method-card">
            <div class="method-icon">📈</div>
            <h3>Modelado xG</h3>
            <p>
                Modelos de expected goals que incorporan distancia, ángulo, 
                presión defensiva y contexto de juego para calcular probabilidad de gol.
            </p>
        </div>

        <div class="method-card">
            <div class="method-icon">🗺️</div>
            <h3>Análisis Espacial</h3>
            <p>
                Mapas de calor, redes de pases y análisis de ocupación espacial 
                para identificar patrones tácticos y zonas de dominancia.
            </p>
        </div>

        <div class="method-card">
            <div class="method-icon">⚡</div>
            <h3>Ventanas de Amenaza</h3>
            <p>
                Modelo propietario de ventanas de 15 segundos que mide la peligrosidad 
                de posesiones según presión y posición espacial.
            </p>
        </div>
    </div>
</section>

<!-- CTA SECTION -->
<div class="cta-section">
    <h2>¿Necesitas este nivel de análisis?</h2>
    <p>
        Análisis táctico customizado para clubes profesionales, 
        agencias de representación y departamentos de scouting.
    </p>
    <div class="hero-cta">
        <a href="mailto:contact@analitykaxg.com" class="cta-primary">
            Contactar para Proyectos
            <span>→</span>
        </a>
        <a href="#methodology" class="cta-secondary">
            Ver Metodología Completa
        </a>
    </div>
</div>
