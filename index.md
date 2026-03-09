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
            <p class="subtitle">Football Performance & Data Analyst</p>
            <h1>Tactical Intelligence<br>Through Data</h1>
            <p class="tagline">
                Performance analysis combining data, video observation and spatial metrics to understand how teams and players create advantages on the pitch.
            </p>
            <div class="hero-cta">
                <a href="#reports" class="cta-primary">
                    View Analysis
                    <span>→</span>
                </a>
            </div>
        </div>
    </div>
</section>
<!-- STATS BAR 
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
</div> -->
<!-- ABOUT SECTION -->
<section class="section" id="about" style="background: var(--bg-secondary); max-width: 100%; padding: 80px 40px;">
    <div class="section-header">
        <h2>Analytical Approach</h2>
    </div>
    <p style="text-align: justify; color: var(--text-secondary); font-size: 16px; line-height: 1.8; max-width: 700px; margin: 0 auto;">
        Football analyst combining data analysis and tactical observation to understand team performance and player impact.
        My work explores match dynamics, tactical structures and individual contributions across different phases of play.
    </p>
</section> 

<!-- FEATURED REPORTS -->
<section class="section" id="reports">
    <div class="section-header">
        <h2>Latest Analysis</h2>
        <p>Tactical reports based on proprietary expected goals models and spatial analysis</p>
    </div>
    <div class="reports-grid">
        <!-- Card 1: LeverKUsen Campeon BundesLiga vs Werbem -->
        <a href="{{ site.baseurl }}/reports/BayerLeverkusenPassNetwork" class="report-card">
            <div class="report-thumbnail">
                <img src="{{ site.baseurl }}/assets/images/1_pass_network_top.png" alt="B.Leverkusen PassNetwork">
            </div>
            <div class="report-content">
                <span class="report-tag">Team Analysis</span>
                <h3>Leverkusen Passing Network – Possession Structure</h3>
                <div class="report-meta">
                    <span>Bundesliga 23/24</span><span>•</span><span>March 2024</span>
                </div>
                <p class="report-excerpt">Pass network and spatial structure analysis showing how Leverkusen organized possession and circulation before the first substitution.</p>
                <span class="report-link">Read full analysis <span>→</span></span>
            </div>
        </a>
        <!-- Card 2: Bayer vs Bayern Leverkusen -->
        <a href="{{ site.baseurl }}/reports/BayerLeverkusenvsBayernMunich" class="report-card">
            <div class="report-thumbnail">
                <img src="{{ site.baseurl }}/assets/images/shot_map_final_leverkusen.png" alt="Leverkusen Shot Map">
            </div>
            <div class="report-content">
                <span class="report-tag">Match Analysis</span>
                <h3>Bayer Leverkusen: Tactical xG Breakdown</h3>
                <div class="report-meta">
                    <span>Bundesliga 23/24</span><span>•</span><span>Marzo 2026</span>
                </div>
                <p class="report-excerpt">An in-depth study of Xabi Alonso's finishing zone dominance using advanced xG Flow models at the Allianz Arena.</p>
                <span class="report-link">Read full analysis <span>→</span></span>
            </div>
        </a>
        <!-- Card 3: Argentina vs Francea-->
        <a href="{{ site.baseurl }}/reports/ArgentinavsFranceHeadMap" class="report-card">
            <div class="report-thumbnail">
                <img src="{{ site.baseurl }}/assets/images/heatmap_argentina.png" alt="Leverkusen Shot Map">
            </div>
            <div class="report-content">
                <span class="report-tag">Match Analysis</span>
                <h3>Argentina vs France: Activity Heatmaps</h3>
                <div class="report-meta">
                    <span>FIFA World Cup 2022 Final</span><span>•</span><span>Dic 2022</span>
                </div>
                <p class="report-excerpt">Spatial analysis of Argentina and France during the 2022 World Cup Final, using event density heatmaps to explore team activity and Lionel Messi's influence zones.</p>
                <span class="report-link">Read full analysis <span>→</span></span>
            </div>
        </a>
        <!-- Card 4: Coming Soon 
        <a href="#" class="report-card">
            <div class="report-thumbnail">
                <div style="font-size: 64px; color: var(--accent-cyan); opacity: 0.3;">⚽</div>
            </div>
            <div class="report-content">
                <span class="report-tag">Player Scouting</span>
                <h3>Coming Soon</h3>
                <div class="report-meta"><span>Individual Analysis</span></div>
                <p class="report-excerpt">Upcoming player analysis with comparative radar and heatmaps.</p>
                <span class="report-link">Coming soon <span>→</span></span>
            </div>
        </a> -->
    </div> 

    <!-- BOTÓN VER TODOS -->
    <div style="text-align: center; margin-top: 48px;">
        <a href="{{ site.baseurl }}/reports/" class="cta-secondary">View all reports <span>→</span></a>
    </div>
</section>

<!-- METHODOLOGY 
<section class="section" id="methodology">
    <div class="section-header">
        <h2>Analysis Framework</h2>
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
</section> -->

<!-- CTA SECTION -->
<div class="cta-section">
    <h2>Need help analysing a game??</h2>
    <p>
        I create tactical reports and video analysis for clubs, coaches, and scouting teams.
    </p>
    <div class="hero-cta">
        <a href="mailto:analitykaxg@gmail.com" class="cta-primary">
            Contact for Projects
            <span>→</span>
        </a>
    </div>
</div>
