---
layout: report
title: "Argentina vs France: Spatial Control & Heatmap Analysis"
description: "Spatial analysis of the 2022 World Cup Final using activity heatmaps to examine territorial control and Lionel Messi's influence."
category: Match Analysis
competition: FIFA World Cup Qatar 2022
date: 2022-12-18
lang: en
---
<!-- REPORT HERO -->
<div class="report-hero">
    <span class="report-category">{{ page.category }}</span>
    <h1>{{ page.title }}</h1>
    <div class="report-meta">
        <span>📍 {{ page.competition }}</span>
        <span>•</span>
        <span>📅 {{ page.date | date: "%d %B %Y" }}</span>
        <span>•</span>
        <span class="reading-time">⏱️ 2 min read</span>
    </div>
</div>
<!-- EXECUTIVE SUMMARY -->
<div class="executive-summary">
    <h2>🎯 Executive Summary</h2>
      <p>Argentina controlled the spatial dynamics of the final through strong left-sided activity and central midfield circulation. Heatmap analysis highlights sustained territorial presence in advanced zones, while France showed limited progression until the final stages of the match. Lionel Messi’s activity map further reveals his role as the central connector of Argentina’s attacking structure.
      </p>
</div>
 <!-- Stats Comparison -->
 <div class="stats-comparison">
    <div class="team-stats">
        <div class="team-name">Métrica</div>
        <div class="stat-row">
            <span class="stat-value">Pass Accuracy</span>
            <span class="stat-label"></span>
        </div>
        <div class="stat-row">
            <span class="stat-value">Progressive Passes</span>
            <span class="stat-label"></span>
        </div>
        <div class="stat-row">
            <span class="stat-value">Passes to Final Third</span>
            <span class="stat-label"></span>
        </div>
        <div class="stat-row">
            <span class="stat-value">Avg. Pass Distance</span>
            <span class="stat-label"></span>
        </div>
    </div>
    <div class="divider"></div>
    <div class="team-stats">
        <div class="team-name">BAYER LEVERKUSEN</div>
        <div class="stat-row">
            <span class="stat-value">89%</span>
            <span class="stat-label"></span>
        </div>
        <div class="stat-row">
            <span class="stat-value">32</span>
            <span class="stat-label"></span>
        </div>
        <div class="stat-row">
            <span class="stat-value">41</span>
            <span class="stat-label"></span>
        </div>
        <div class="stat-row">
            <span class="stat-value">17.4m</span>
            <span class="stat-label"></span>
        </div>
    </div>
</div>

<!-- CONTENT SECTIONS -->
<div class="report-content">
<!-- Section 1: Match Context -->
    <div class="content-section">
        <h2>Match Context</h2>
        <p>
            This report analyzes spatial activity during the final of the 2022 FIFA World Cup between Argentina and France. Using event data from StatsBomb, heatmaps are used to visualize territorial occupation and player influence throughout the match.
        </p>
    </div>
  <div class="content-section">
        <h3>Argentina Territorial Control</h3>
        <p> 
            Argentina's heatmap reveals sustained activity in advanced areas, particularly along the left side of the pitch. This pattern reflects the team's ability to progress possession through central midfield and overload wide zones during attacking phases.
        </p>    
  </div>
 <!-- Section 2.1: Threat Windows --> 
    <!-- Visualization 1: Mapa argentina -->
    <div class="visualization">
        <img src="{{ site.baseurl }}/assets/images/heatmap_argentina.png" alt="Argentina Head Map">
        <p class="viz-caption">
            <strong>Figure 1: </strong>Pass network of Bayer Leverkusen showing successful passing relationships before the first substitution.
            Node size represents number of completed passes, while line thickness indicates the frequency of connections between players. Only connections with at least six passes are displayed.
        </p>
    </div>
    <!-- Section 2 --> 
    <!-- Visualization 2: France shot map -->
    <div class="visualization">
      <h3>France Activity Map</h3>
        <img src="{{ site.baseurl }}/assets/images/heatmap_francia.png" alt="France Head Map">
        <p class="viz-caption">
            <strong>Figure 2: </strong>Average on-ball positions based on successful passes.
            Marker size represents passing involvement, providing a snapshot of Leverkusen’s spatial structure during possession.
        </p>
    </div>
    <div class="content-section">
        <p> 
            France’s spatial activity appears more dispersed and deeper in their own half. The map suggests limited territorial progression during large phases of the match, with most actions concentrated in defensive and middle zones.
        </p>    
    </div>
    <!-- Section 3 -->
    <!-- Visualization 1: Messi Shot map -->
    <div class="visualization">
      <h3>Messi Influence Map</h3>
        <img src="{{ site.baseurl }}/assets/images/heatmap_messi.png" alt="Messi Head Map">
        <p class="viz-caption">
            <strong>Figure 3: </strong>Successful passes completed by Granit Xhaka during the analyzed phase.
            Arrows represent pass direction and length, highlighting his role in connecting midfield circulation.
        </p>
    </div>
    <div class="content-section">
        <p> 
            Lionel Messi’s activity map highlights his constant involvement across central and left-sided zones. The visualization reflects his role as the primary connector between midfield circulation and attacking phases, frequently dropping deeper to participate in build-up before progressing play forward.
        </p>    
    </div>
    <!-- Conclusion -->
    <div class="conclusion-box">
        <h3>💡 Tactical Insight</h3>
        <p style="margin-bottom:16px;">
            The spatial patterns suggest that Argentina controlled the territorial dynamics of the final through structured possession and strong central connectivity. Messi’s positioning between midfield and attacking zones provided a consistent link for ball progression, allowing Argentina to sustain pressure in advanced areas while maintaining control of possession phases.
        </p>
    </div>
</div>
<!-- METADATA -->
<div class="report-metadata">
    <div class="metadata-row">
        <div class="metadata-item">
            <span class="metadata-label">Data Source</span>
            <span>StatsBomb Open Data</span>
        </div>
        <div class="metadata-item">
            <span class="metadata-label">Tools</span>
            <span>Python, mplsoccer, pandas, statsbombpy</span>
        </div>
        <div class="metadata-item">
            <span class="metadata-label">Analysis by</span>
            <span>Carlos Fiallos</span>
        </div>
        <div class="metadata-item">
            <span class="metadata-label">Published</span>
            <span>{{ page.date | date: "%d %B %Y" }}</span>
        </div>
    </div>
</div>
