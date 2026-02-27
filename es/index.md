---
layout: default
title: Inicio
lang: es
---

<!-- HERO SECTION -->
<section class="hero-section" style="background-image: url('{{ site.baseurl }}/assets/images/hero-bg.jpg'); background-size: cover; background-position: center; position: relative;">
    <div style="position:absolute;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.75);z-index:0;"></div>
    <div class="hero-content" style="position:relative;z-index:1;width:100%;text-align:center;">        
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

        <div class="stats-bar">
            <div class="stat-item">
                <span class="stat-number">25+</span>
                <span class="stat-label">Reportes</span>
            </div>
            <div class="stat-item">
                <span class="stat-number">10</span>
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
        
        <!-- Card 1: Celta Vigo - VERSIÓN ESPAÑOL -->
        <a href="{{ site.baseurl }}/es/reports/celta-vigo-offensive-analysis-2025" class="report-card">
            <div class="report-thumbnail">
                <img src="{{ site.baseurl }}/assets/images/celta-vigo-shot-map.png" alt="Mapa de Tiros Celta Vigo">
            </div>
            <div class="report-content">
                <span class="report-tag">Análisis de Equipo</span>
                <h3>Celta Vigo - Análisis Ofensivo</h3>
                <div class="report-meta">
                    <span>Premier League 24/25</span>
                    <span>•</span>
                    <span>Jan 2026</span>
                </div>
                <p class="report-excerpt">
                    Análisis de mapa de tiros mostrando 1.61 xG en 7 tiros con 124% de conversión. 
                    Progresión central y finalización clínica.
                </p>
                <span class="report-link">
                    Leer análisis completo
                    <span>→</span>
                </span>
            </div>
        </a>

        <!-- Card 2: Argentina vs Ecuador -->
        <a href="{{ site.baseurl }}/es/reports/argentina-ecuador-2024" class="report-card">
            <div class="report-thumbnail">
                <div style="font-size: 64px; color: var(--accent-cyan); opacity: 0.3;">📊</div>
            </div>
            <div class="report-content">
                <span class="report-tag">Análisis Post-Partido</span>
                <h3>Argentina vs Ecuador</h3>
                <div class="report-meta">
                    <span>Copa América 2024</span>
                    <span>•</span>
                    <span>Julio 2024</span>
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

        <!-- Card 3: Próximamente -->
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
        <a href="mailto:analitykaxg@gmail.com" class="cta-primary">
            Contactar para Proyectos
            <span>→</span>
        </a>
        <a href="#methodology" class="cta-secondary">
            Ver Metodología Completa
        </a>
    </div>
</div>
