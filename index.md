---
layout: default
title: Home
lang: en
---

<!-- HERO SECTION -->
<section class="hero-section" style="background-image: url('{{ site.baseurl }}/assets/images/profile.png'); background-size: cover; background-position: center; position: relative;">
    <div style="position:absolute;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.75);z-index:0;"></div>
    <div class="hero-content" style="position:relative;z-index:1;width:100%;text-align:center;">
         <div class="hero-text">
            <p class="subtitle">Football Data Analyst</p>
            <h1>Tactical Intelligence<br>Through Data</h1>
            <p class="tagline">
                Match analysis combining data, video observation
                and spatial metrics to understand how teams create
                and concede scoring opportunities.
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
    </div>
</section>
<!-- STATS BAR -->
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
<!-- ABOUUT SECTION -->
<section class="section" id="about">
    <div class="section-header">
        <h2>About</h2>
        <p>Football analyst combining data and tactical observation</p>
    </div>
    <div class="about-grid">
        <div class="about-text">
            <p>
                I'm a football data analyst focused on turning raw match data into 
                tactical insights. My work combines Python-based xG modeling, spatial 
                analysis, and video observation to understand how teams create and 
                concede opportunities.
            </p>
            <p>
                With experience across 10+ leagues and 25+ published reports, I build 
                custom analytical frameworks for clubs, agencies, and scouting departments 
                looking for an edge beyond traditional stats.
            </p>
        </div>
        <div class="about-tags">
            <span class="report-tag">xG Modeling</span>
            <span class="report-tag">Spatial Analysis</span>
            <span class="report-tag">Python</span>
            <span class="report-tag">StatsBomb</span>
            <span class="report-tag">Tactical Scouting</span>
            <span class="report-tag">Video Analysis</span>
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
       <!-- Card 1: Celta Vigo - TU NUEVO REPORTE -->
        <a href="{{ site.baseurl }}/reports/celta-vigo-offensive-analysis-2025" class="report-card">
            <div class="report-thumbnail">
                <img src="{{ site.baseurl }}/assets/images/celta-vigo-shot-map.png" alt="Celta Vigo Shot Map">
            </div>
            <div class="report-content">
                <span class="report-tag">Team Analysis</span>
                <h3>Celta Vigo - Offensive Analysis</h3>
                <div class="report-meta">
                    <span>Premier League 24/25</span>
                    <span>•</span>
                    <span>Jan 2026</span>
                </div>
                <p class="report-excerpt">
                    Shot map analysis showing 1.61 xG from 7 shots with 124% conversion rate. 
                    Central progression and clinical finishing breakdown.
                </p>
                <span class="report-link">
                    Read full analysis
                    <span>→</span>
                </span>
            </div>
        </a>
        <!-- Card 2: Bayer vs Leverkusen  -->
        <a href="{{ site.baseurl }}/reports/BayerLeverkusenvsBayernMunich" class="report-card">
            <div class="report-thumbnail">
                <img src="{{ site.baseurl }}/assets/images/shot_map_final_leverkusen.png" alt="Leverkusen Shot Map">
            </div>
            <div class="report-content">
                <span class="report-tag">Post-Match Analysis</span>
                <h3>Bayer Leverkusen: Tactical xG Breakdown</h3>
                <div class="report-meta">
                    <span>Bundesliga 23/24</span>
                    <span>•</span>
                    <span>Marzo 2026</span>
                </div>
                <p class="report-excerpt">
                    An in-depth study of Xabi Alonso's finishing zone dominance. Using advanced xG Flow models to analyze how Leverkusen achieved statistical parity against the reigning champions at the Allianz Arena.
                </p>
                <span class="report-link">
                    Read full analysis
                    <span>→</span>
                </span>
            </div>
        </a>
        <!-- Card 3: Coming Soon -->
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
            <h3>Methods</h3>
            <p>
                • Data analysis
                • Video-based tactical observation
                • Spatial event analysis
                • Performance metrics interpretation
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
            <h3>Areas of Analysis</h3>
            <p>
                • Match performance analysis
                • Team tactical structure
                • Player performance evaluation
                • Attacking and defensive patterns
                • Game dynamics and momentum
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
