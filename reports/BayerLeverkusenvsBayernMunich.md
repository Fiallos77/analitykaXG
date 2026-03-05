---
layout: report
title: Bayer Leverkusen vs Bayern Munich - xG & Finishing Analysis
description: Tactical breakdown of Bundesliga's high-stake draw using advanced xG Shot Maps and Danger Flow models.
category: Post-Match Analysis
competition: Bundesliga 23/24
date: 2024-03-03
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
    <ul class="key-insights">
        <li>Bayern generated higher shot volume (16 shots) but with lower average shot quality.</li>
        <li>Leverkusen created fewer opportunities but consistently reached central areas, producing three big chances.</li>
        <li>Most of Leverkusen’s threat came during transitional phases rather than sustained possession.</li>
    </ul>
</div>
 <!-- Stats Comparison -->
 <div class="stats-comparison">
    <div class="team-stats">
        <div class="team-name">BAYERN MUNICH</div>
        <div class="stat-row">
            <span class="stat-value">1.72</span>
            <span class="stat-label">Total xG</span>
        </div>
        <div class="stat-row">
            <span class="stat-value">16</span>
            <span class="stat-label">Shots</span>
        </div>
        <div class="stat-row">
            <span class="stat-value">10</span>
            <span class="stat-label">In Box</span>
        </div>
        <div class="stat-row">
            <span class="stat-value">2</span>
            <span class="stat-label">BIG CHANCES</span>
        </div>
    </div>
    <div class="divider"></div>
    <div class="team-stats">
        <div class="team-name">BAYER LEVERKUSEN</div>
        <div class="stat-row">
            <span class="stat-value">1.52</span>
            <span class="stat-label">Total xG</span>
        </div>
        <div class="stat-row">
            <span class="stat-value">13</span>
            <span class="stat-label">Shots</span>
        </div>
        <div class="stat-row">
            <span class="stat-value">9</span>
            <span class="stat-label">In Box</span>
        </div>
        <div class="stat-row">
            <span class="stat-value">3</span>
            <span class="stat-label">BIG CHANCES</span>
        </div>
    </div>
</div>

<!-- CONTENT SECTIONS -->
<div class="report-content">
<!-- Section 1: Match Context -->
    <div class="content-section">
        <h2>Match Context</h2>
        <p>
            This Bundesliga matchup at the Allianz Arena tested Bayer Leverkusen’s ability to compete against Bayern Munich’s territorial dominance.
While Bayern controlled possession for long periods, Leverkusen relied on vertical progression and quick transitions to generate high-quality chances.
        </p>
    </div>
<!-- Visualization 1: Shot Map -->
    <div class="visualization">
        <img src="{{ site.baseurl }}/assets/images/shot_map_final_leverkusen.png" alt="Shot Map Bayern Munich vs Leverkusen">
        <p class="viz-caption">
            <strong>Figure 1:</strong> Leverkusen Advanced Shot Map. Arrows indicate goals from Jonathan Tah, Jeremie Frimpong, and Florian Wirtz. The "glow" markers highlight high-value central opportunities (>0.4 xG), showcasing Leverkusen's efficiency in reaching the Golden Zone.
        </p>
    </div>
 <!-- Section 2.1: Threat Windows -->
    <div class="content-section">
        <h3>Tactical Analysis: Shot Map & Efficiency</h3>
        <p>
            The shot map reveals a clear difference in attacking approach.
            Bayern produced a higher volume of attempts, but many of them came from wider or deeper positions. Leverkusen, on the other hand, generated fewer shots but consistently accessed central areas inside the penalty box.
            This suggests a more selective attacking structure, prioritizing high-probability chances rather than shot volume.
        </p>    
    </div>
<!-- Section 1: Match 2 -->
    <div class="content-section">
         <h2>Match Momentum & xG Evolution</h2>
         <p>
             The xG timeline shows Bayern creating early pressure during the opening 20 minutes.
             However, Leverkusen gradually balanced the threat profile, producing several high-value chances during the middle phase of the match.
        </p>
   </div>
 <!-- Visualization 2: XG -->
    <div class="visualization">
        <img src="{{ site.baseurl }}/assets/images/xg_flow_final_leverkusen.png" alt="Shot Map Bayern Munich vs Leverkusen">
        <p class="viz-caption">
            <strong>Figure 2:</strong> Cumulative xG Flow. The step-function lines track the timing and probability of every shot. Soccer ball markers indicate goals, while the dashed line represents Bayern Munich’s threat timeline, providing a direct comparison of match dominance over the 95-minute duration.
        </p>
    </div>
    <!-- Conclusion -->
    <div class="conclusion-box">
        <h3>💡 Tactical Conclusion</h3>
        <p>
            Leverkusen’s performance relied on attacking efficiency rather than shot volume.
            Despite Bayern generating more attempts overall, Leverkusen consistently reached central shooting zones and created a similar level of expected goals through fewer but higher-quality chances.
        </p>
        <p style="margin-top: 16px;">
            <strong>Key Insight:</strong> Bayern's build-up relies heavily on the distribution of Upamecano and Kim Min-jae. Applying targeted pressure on these first-phase passes could force longer progressions and potentially reduce Bayern’s ability to generate structured high-xG chances.
        </p>
    </div>
 <!-- Analyst's Note: Efficiency vs. Volume -->
    <div class="conclusion-box">
        <h3>Analyst's Note: Efficiency vs. Volume</h3>
        <p>
            This match illustrates how shot quality can compensate for differences in shot volume.
            Leverkusen’s attacking structure allowed them to access central areas and generate high-value opportunities even while spending less time in possession.
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
            <span class="metadata-label">Model</span>
            <span>xG Flow model</span>
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
