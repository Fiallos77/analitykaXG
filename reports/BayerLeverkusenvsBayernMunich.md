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
        <li>Statistical Parity: The match concluded with a remarkably balanced expected goals (xG) profile, with Leverkusen reaching 1.52 xG against Bayern Munich's slight lead of ~1.72 xG, reflecting the 2-2 tactical stalemate on the pitch.</li>
        <li>High-Value Chance Creation: Leverkusen's offensive strategy prioritized quality over volume in the second half, identified by the "Big Chances" (glowing markers) created in the central finishing zone by Jeremie Frimpong and Jonathan Tah.</li>
        <li>Dynamic Threat Profile: The xG Flow analysis reveals that Leverkusen maintained a consistent danger output, notably recovering from Bayern's early pressure to dominate the mid-game threat windows.</li>
        <li>Individual Impact: Jeremie Frimpong emerged as the primary offensive catalyst for Leverkusen, leading the team with 0.49 individual xG, followed closely by Florian Wirtz (0.45 xG), who orchestrated play in the final third.</li>
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
            This Bundesliga encounter features a high-stakes tactical battle between Bayern Munich and Bayer Leverkusen. 
            Played at the Allianz Arena, the match served as a definitive test for Xabi Alonso’s side against the reigning 
            champions.
        </p>
        <p>
            The analysis focuses on spatial efficiency and finishing quality, utilizing StatsBomb open data to break down 
            how Leverkusen managed to secure a 2-2 draw through disciplined shot selection and clinical execution in 
            high-probability zones.
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
            The shot map reveals a highly concentrated attacking pattern, with Leverkusen successfully penetrating the "Golden Zone" 
            (central six-yard and penalty area). Key findings include:
        </p>
        <ul class="key-insights">
            <li>Shot Quality over Volume: Despite having fewer total attempts than Bayern, Leverkusen’s average xG per shot was remarkably high, evidenced by the large, glowing markers representing "Big Chances" created in central positions.
            </li>
            <li>Central Dominance: The visualization shows a clear rejection of low-probability long-range efforts, with almost all significant threats originating from inside the box.</li>
            <li>Individual Precision: The primary threat was spearheaded by Jeremie Frimpong (0.49 xG) and Florian Wirtz (0.45 xG), who effectively exploited vertical gaps in Bayern's defensive line to reach high-value shooting coordinates.
            </li>
        </ul>    
    </div>
<!-- Section 1: Match 2 -->
    <div class="content-section">
         <h2>Match Momentum & xG Evolution</h2>
         <p>
         The xG Flow model shows Leverkusen's high resilience. Despite Bayern's early pressure, the team maintained a steady threat level, achieving statistical parity (1.52 xG) by the final whistle through clinical efficiency in key transitions.
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
            Leverkusen’s performance at the Allianz Arena was a masterclass in efficient attacking transition. By maintaining a high xG per shot ratio (0.13 avg), they neutralized Bayern’s volume-based pressure. To sustain this elite level, Leverkusen must:
        </p>
        <ul class="key-insights">
            <li>Continue isolating Wirtz in half-spaces to trigger high-value shot assists against aggressive defensive lines.
            </li>
            <li>Improve defensive coverage on the wings to prevent early deficit spikes as seen in the first 20 minutes of the xG Flow.</li>
            <li>Maintain the high-press intensity that led to Frimpong's central recoveries and high-probability scoring chances.
            </li>
        </ul>   
        <p style="margin-top: 16px;">
            <strong>Key Recommendation: Direct pressing on Upamecano and Kim Min-jae during build-up could disrupt Bayern's progression, forcing long balls that reduce their effectiveness in creating high xG opportunities.</strong>
        </p>
    </div>
 <!-- Analyst's Note: Efficiency vs. Volume -->
    <div class="conclusion-box">
        <h3>Analyst's Note: Efficiency vs. Volume</h3>
        <p>
            While Bayern Munich led in total xG (1.72) and shot volume (16), the underlying data reveals a superior tactical execution by Bayer Leverkusen. By generating 3 Big Chances from fewer attempts, Leverkusen achieved a higher xG per shot (0.116) compared to Bayern’s 0.10. This analysis proves that Xabi Alonso’s side didn't just "survive" the Allianz Arena; they optimized their attacking possessions to challenge the champions through clinical spatial dominance rather than mere persistence.
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
