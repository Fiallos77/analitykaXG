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
      <p>This report examines spatial activity patterns during the 2022 FIFA World Cup Final between Argentina and France. Using event density heatmaps, the analysis highlights how both teams occupied the pitch and where Lionel Messi exerted the greatest influence during attacking phases.
      </p>
</div>
<!-- CONTENT SECTIONS -->
<div class="report-content">
<!-- Section 1: Match Context -->
    <div class="content-section">
        <h2>Match Context</h2>
        <p>
            The analysis is based on StatsBomb open event data from the 2022 FIFA World Cup Final.
            Heatmaps represent the spatial distribution of key attacking actions.
            For team maps:
            <ul class="key-insights">
                <li>Argentina: Pass, Carry, Shot events</li>
                <li>France: Pass, Carry events</li>
            </ul>
            For the player analysis, Messi’s actions include passes, carries, shots and dribbles.
        </p>
    </div>
    <!-- Section 1: -->
    <div class="content-section">
        <h3>Territorial Control</h3>   
    </div>
    <div class="visualization">
        <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 16px;">
            <div>
                <img src="{{ site.baseurl }}/assets/images/heatmap_argentina.png" alt="Argentina Head Map">
                <p class="viz-caption"><strong>Figure 1: </strong>Argentina spatial activity during the match.</p>
            </div>
            <div>
                <img src="{{ site.baseurl }}/assets/images/heatmap_francia.png" alt="Imagen derecha">
                <p class="viz-caption"><strong>Figure 2: </strong>France activity distribution across the pitch.</p>
            </div>
        </div>
    </div>
    <div class="content-section">
        <p>The heatmaps illustrate how each team occupied attacking territory during the match.
            Argentina shows strong activity in advanced areas, particularly through the left half-space and central attacking lanes.
            This pattern suggests sustained progression into the final third and frequent involvement around the edge of the penalty area.
            France’s activity is more concentrated around midfield zones, with notable presence on the left side during build-up phases.
            Compared to Argentina, their density appears deeper, indicating longer phases of circulation before entering advanced areas.</p>   
    </div>
    <!-- Section 2 -->
    <div class="content-section">
        <h3>Messi Influence Map</h3>   
    </div>
    <!-- Visualization 1: Messi Shot map -->
    <div class="visualization">
        <img src="{{ site.baseurl }}/assets/images/heatmap_messi.png" alt="Messi Head Map">
        <p class="viz-caption">
            <strong>Figure 3: </strong>Lionel Messi influence map highlighting involvement between midfield and attacking zones.
        </p>
    </div>
    <div class="content-section">
        <p> 
            Messi’s influence map highlights his spatial role throughout Argentina’s attacking phases.
            The highest density appears in the right half-space between midfield and the penalty area, a zone frequently used to connect build-up with final third actions.
            His activity also extends into deeper midfield areas, indicating involvement in progression rather than remaining exclusively in advanced positions.
            This spatial distribution reflects Messi’s hybrid role: both a creator in deeper zones and a decisive presence near the attacking third.
        </p>    
    </div>
    <!-- Conclusion -->
    <div class="conclusion-box">
        <h3>💡 Tactical Interpretation</h3>
        <p style="margin-bottom:16px;">
            Together, the heatmaps reveal a clear structural contrast between the two teams.
            Argentina’s activity is more advanced and concentrated around attacking corridors, suggesting greater territorial progression during key phases of play.
            France’s distribution appears deeper and more spread across midfield zones, indicating a greater share of activity during transitional or build-up phases.
            Within this structure, Messi’s positional influence emerges primarily in the right half-space, linking central progression with final third actions.
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
