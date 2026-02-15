---
layout: default
title: Home
lang: en
---

<!-- HERO SECTION -->
<section class="hero-section">
    <div class="hero-content">
        <img src="{{ site.baseurl }}/assets/images/profile.jpg" alt="Football Data Analyst" class="profile-photo">
        
        <div class="hero-text">
            <p class="subtitle">Football Data Analyst</p>
            <h1>Tactical Intelligence<br>Through Data</h1>
            <p class="tagline">
                Elite-level tactical analysis based on <strong>advanced xG models</strong>, 
                spatial dominance, and pressure structures. Transforming data into decisions for professional clubs.
            </p>
            
            <div class="hero-cta">
                <a href="#reports" class="cta-primary">
                    View Analysis
                    <span>→</span>
                </a>
                <a href="#methodology" class="cta-secondary">
                    Methodology
                </a>
            </div>
        </div>

        <div class="stats-bar">
            <div class="stat-item">
                <span class="stat-number">25+</span>
                <span class="stat-label">Reports</span>
            </div>
            <div class="stat-item">
                <span class="stat-number">10</span>
                <span class="stat-label">Leagues</span>
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
        <h2>Latest Analysis</h2>
        <p>Tactical reports based on proprietary expected goals models and spatial analysis</p>
    </div>

    <div class="reports-grid">
        <a href="{{ site.baseurl }}/reports/argentina-ecuador-2024" class="report-card">
            <div class="report-thumbnail">
                <div style="font-size: 64px; color: var(--accent-cyan); opacity: 0.3;">📊</div>
            </div>
            <div class="report-content">
                <span class="report-tag">Post-Match Analysis</span>
                <h3>Argentina vs Ecuador</h3>
                <div class="report-meta">
                    <span>Copa América 2024</span>
                    <span>•</span>
                    <span>July 2024</span>
                </div>
                <p class="report-excerpt">
                    Spatial threat distribution analysis using 15-second window model. 
                    Finishing zone dominance and pressure patterns breakdown.
                </p>
                <span class="report-link">
                    Read full analysis
                    <span>→</span>
                </span>
            </div>
        </a>

        <a href="#" class="report-card">
            <div class="report-thumbnail">
                <div style="font-size: 64px; color: var(--accent-cyan); opacity: 0.3;">⚽</div>
            </div>
            <div class="report-content">
                <span class="report-tag">Player Scouting</span>
                <h3>Coming Soon</h3>
                <div class="report-meta">
                    <span>Individual Analysis</span>
                </div>
                <p class="report-excerpt">
                    Upcoming player analysis with comparative radar and heatmaps.
                </p>
                <span class="report-link">
                    Coming soon
                    <span>→</span>
                </span>
            </div>
        </a>

        <a href="#" class="report-card">
            <div class="report-thumbnail">
                <div style="font-size: 64px; color: var(--accent-cyan); opacity: 0.3;">🎯</div>
            </div>
            <div class="report-content">
                <span class="report-tag">Tactical Study</span>
                <h3>Coming Soon</h3>
                <div class="report-meta">
                    <span>Tactical Breakdown</span>
                </div>
                <p class="report-excerpt">
                    Pressure structures analysis and xG generation in transitions.
                </p>
                <span class="report-link">
                    Coming soon
                    <span>→</span>
                </span>
            </div>
        </a>
    </div>
</section>

<!-- METHODOLOGY -->
<section class="section" id="methodology">
    <div class="section-header">
        <h2>Methodology</h2>
        <p>Proprietary models developed in Python on StatsBomb data</p>
    </div>

    <div class="methodology-grid">
        <div class="method-card">
            <div class="method-icon">📈</div>
            <h3>xG Modeling</h3>
            <p>
                Expected goals models incorporating distance, angle, 
                defensive pressure, and game context to calculate goal probability.
            </p>
        </div>

        <div class="method-card">
            <div class="method-icon">🗺️</div>
            <h3>Spatial Analysis</h3>
            <p>
                Heatmaps, pass networks, and spatial occupation analysis 
                to identify tactical patterns and dominance zones.
            </p>
        </div>

        <div class="method-card">
            <div class="method-icon">⚡</div>
            <h3>Threat Windows</h3>
            <p>
                Proprietary 15-second threat window model measuring possession 
                dangerousness based on pressure and spatial position.
            </p>
        </div>
    </div>
</section>

<!-- CTA SECTION -->
<div class="cta-section">
    <h2>Need this level of analysis?</h2>
    <p>
        Custom tactical analysis for professional clubs, 
        representation agencies, and scouting departments.
    </p>
    <div class="hero-cta">
        <a href="mailto:analitykaxg@gmail.com" class="cta-primary">
            Contact for Projects
            <span>→</span>
        </a>
        <a href="#methodology" class="cta-secondary">
            View Full Methodology
        </a>
    </div>
</div>
