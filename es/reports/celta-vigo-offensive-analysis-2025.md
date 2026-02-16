---
layout: report
title: Celta Vigo - Análisis Ofensivo
description: Análisis de mapa de tiros y eficiencia de finalización Premier League 24/25
category: Análisis de Equipo
competition: Premier League 24/25
date: 2026-01-11
lang: es
---

<!-- REPORT HERO -->
<div class="report-hero">
    <span class="report-category">{{ page.category }}</span>
    <h1>{{ page.title }}</h1>
    <div class="report-meta">
        <span>📍 {{ page.competition }}</span>
        <span>•</span>
        <span>📅 {{ page.date | date: "%d de %B de %Y" }}</span>
        <span>•</span>
        <span class="reading-time">⏱️ 2 min lectura</span>
    </div>
</div>

<!-- EXECUTIVE SUMMARY -->
<div class="executive-summary">
    <h2>🎯 Resumen Ejecutivo</h2>
    <ul class="key-insights">
        <li>El Celta generó 1.61 xG en 7 tiros, sobrerindiendo con 2 goles (124% de conversión)</li>
        <li>100% de tiros desde el pie (0 cabezazos), indicando baja dependencia del juego aéreo</li>
        <li>Ubicación de tiros concentrada en zonas centrales con promedio de 0.23 xG por tiro (sobre la media de liga)</li>
    </ul>
</div>

<!-- CONTENT SECTIONS -->
<div class="report-content">
    
    <!-- Contexto del Partido -->
    <div class="content-section">
        <h2>Contexto del Partido</h2>
        <p>
            El rendimiento ofensivo del Celta Vigo en la Premier League 24/25 mostró eficiencia 
            a pesar del bajo volumen de tiros. Con solo 7 tiros totales, lograron anotar 2 goles, 
            superando sus expected goals por 0.39.
        </p>
        <p>
            Este análisis se centra en el posicionamiento de tiros, la calidad y la capacidad del 
            equipo para generar ocasiones de alto valor desde zonas centrales sin depender del juego aéreo.
        </p>
    </div>

    <!-- Visualización: Mapa de Tiros -->
    <div class="visualization">
        <img src="{{ site.baseurl }}/assets/images/celta-vigo-shot-map.png" alt="Mapa de Tiros Celta Vigo">
        <p class="viz-caption">
            <strong>Figura 1:</strong> Mapa de tiros mostrando los 7 tiros del Celta con 2 goles (marcadores rojos). 
            Concentración en zonas centrales con 1.61 xG total. Cero intentos aéreos registrados.
        </p>
    </div>

    <!-- Análisis de Calidad de Tiros -->
    <div class="content-section">
        <h2>Análisis de Calidad de Tiros</h2>
        <p>
            Los 1.61 xG del Celta en 7 tiros representan un promedio de 0.23 xG por tiro, lo cual 
            está por encima del promedio de la Premier League (típicamente 0.10-0.15). Los dos goles 
            provinieron de posiciones de alta calidad dentro del área, ambos desde el pie.
        </p>
        <p>
            La ausencia de intentos de cabeza (0 cabezazos) sugiere que el Celta priorizó ataques 
            a ras de suelo en lugar de centros. La concentración de tiros en zonas centrales indica 
            una progresión efectiva del balón por el medio.
        </p>
    </div>

    <!-- Métricas Clave (visualización horizontal) -->
    <div class="content-section">
        <h2>Métricas Clave</h2>
    </div>
    
    <div style="background: var(--bg-card); padding: 32px; border-radius: 12px; border: 1px solid var(--border-color); margin: 32px 0;">
        <div style="text-align: center; margin-bottom: 32px;">
            <div style="font-family: 'Montserrat', sans-serif; font-size: 24px; font-weight: 700; color: var(--text-primary); margin-bottom: 24px;">CELTA VIGO</div>
        </div>
        
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(140px, 1fr)); gap: 24px; text-align: center;">
            
            <div>
                <div style="font-family: 'Montserrat', sans-serif; font-size: 48px; font-weight: 900; color: var(--accent-cyan); margin-bottom: 8px;">1.61</div>
                <div style="font-size: 12px; color: var(--text-secondary); text-transform: uppercase; letter-spacing: 1px;">xG Total</div>
            </div>
            
            <div>
                <div style="font-family: 'Montserrat', sans-serif; font-size: 48px; font-weight: 900; color: var(--accent-cyan); margin-bottom: 8px;">7</div>
                <div style="font-size: 12px; color: var(--text-secondary); text-transform: uppercase; letter-spacing: 1px;">Tiros Totales</div>
            </div>
            
            <div>
                <div style="font-family: 'Montserrat', sans-serif; font-size: 48px; font-weight: 900; color: var(--accent-green); margin-bottom: 8px;">2</div>
                <div style="font-size: 12px; color: var(--text-secondary); text-transform: uppercase; letter-spacing: 1px;">Goles</div>
            </div>
            
            <div>
                <div style="font-family: 'Montserrat', sans-serif; font-size: 48px; font-weight: 900; color: var(--accent-cyan); margin-bottom: 8px;">0.23</div>
                <div style="font-size: 12px; color: var(--text-secondary); text-transform: uppercase; letter-spacing: 1px;">xG por Tiro</div>
            </div>
            
            <div>
                <div style="font-family: 'Montserrat', sans-serif; font-size: 48px; font-weight: 900; color: var(--text-secondary); margin-bottom: 8px;">0</div>
                <div style="font-size: 12px; color: var(--text-secondary); text-transform: uppercase; letter-spacing: 1px;">Cabezazos</div>
            </div>
            
        </div>
    </div>

    <!-- Patrones Tácticos -->
    <div class="content-section">
        <h2>Patrones Tácticos Identificados</h2>
        
        <h3>Dominancia en Progresión Central</h3>
        <p>
            El mapa de tiros revela la preferencia del Celta por ataques centrales. Con 5 de 7 tiros 
            provenientes del corredor central (71%), el equipo claramente evitó el juego por las bandas 
            en favor de pases entre líneas y penetraciones centrales.
        </p>
        <p>
            Los tiros de larga distancia desde fuera del área (3 intentos) sugieren tiro oportunista 
            cuando las defensas retrocedieron profundamente, creando espacio para remates desde el borde del área.
        </p>
        
        <h3>Alta Eficiencia de Conversión</h3>
        <p>
            Convertir 2 goles desde 1.61 xG demuestra finalización clínica. Ambos goles provinieron 
            de posiciones con valores xG superiores a 0.25, indicando paciencia para esperar ocasiones 
            de alta calidad en lugar de forzar tiros de bajo porcentaje.
        </p>
        
        <h3>Filosofía de Ataque a Ras de Suelo</h3>
        <p>
            La ausencia completa de intentos de cabeza (0 cabezazos de 7 tiros) es significativa. 
            Esto sugiere una preferencia táctica por combinaciones a ras de suelo en lugar de duelos 
            aéreos. El equipo probablemente construye mediante pases cortos y carreras directas en 
            lugar de centros tradicionales.
        </p>
    </div>

    <!-- Conclusión -->
    <div class="conclusion-box">
        <h3>💡 Conclusión Táctica</h3>
        <p>
            El Celta Vigo demostró ofensiva eficiente con calidad sobre cantidad. Sus 7 tiros generaron 
            xG por encima del promedio (0.23 por tiro) y finalización clínica (124% de conversión vs xG). 
            La ausencia de intentos aéreos sugiere un enfoque táctico a ras de suelo priorizando 
            penetración central.
        </p>
        <p style="margin-top: 16px;">
            <strong>Recomendación Clave:</strong> Los rivales deberían comprimir espacios centrales para 
            forzar al Celta hacia las bandas, donde mostraron menor comodidad. Prevenir pases entre líneas 
            en el corredor central limitará sus ocasiones de alto xG. Adicionalmente, permitir centros 
            puede ser más seguro que permitir penetraciones centrales, dada su falta de amenaza aérea.
        </p>
    </div>

</div>

<!-- METADATA -->
<div class="report-metadata">
    <div class="metadata-row">
        <div class="metadata-item">
            <span class="metadata-label">Fuente de Datos</span>
            <span>Análisis Customizado</span>
        </div>
        <div class="metadata-item">
            <span class="metadata-label">Modelo</span>
            <span>Modelo xG Custom</span>
        </div>
        <div class="metadata-item">
            <span class="metadata-label">Herramientas</span>
            <span>Python, mplsoccer, pandas</span>
        </div>
        <div class="metadata-item">
            <span class="metadata-label">Análisis por</span>
            <span>analitykaXG</span>
        </div>
        <div class="metadata-item">
            <span class="metadata-label">Publicado</span>
            <span>{{ page.date | date: "%d de %B de %Y" }}</span>
        </div>
    </div>
</div>
