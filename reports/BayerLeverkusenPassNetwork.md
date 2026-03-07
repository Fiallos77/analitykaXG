---
layout: report
title: "Bayer Leverkusen: Structural Connectivity & Pass Network Analysis"
description: "Tactical breakdown of Bundesliga's high-stake draw using advanced xG Shot Maps and Danger Flow models."
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
        <li>Leverkusen’s pass network highlights a strong central circulation involving Tapsoba, Tah, Xhaka and Andrich.</li>
        <li>Tapsoba and Xhaka appear as the main distributors in possession, recording the highest number of successful passes before the first substitution.</li>
        <li>The average positions show a compact central structure, while wide players maintain width to stretch the pitch.</li>
    </ul>
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
            This report examines Bayer Leverkusen’s passing structure during their Bundesliga match against Werder Bremen in the 2023/24 season.
            To capture the team’s initial tactical organization, the analysis focuses exclusively on successful passes before the first substitution. This allows us to observe the passing structure of the starting eleven during the early phases of the match..
        </p>
    </div>
 <!-- Section 2.1: Threat Windows --> 
    <!-- Visualization 1: Red de pases1 -->
    <div class="visualization">
        <img src="{{ site.baseurl }}/assets/images/1_pass_network_top.png" alt="Shot Map Bayern Munich vs Leverkusen">
        <p class="viz-caption">
            <strong>Figure 1: </strong>Pass network of Bayer Leverkusen showing successful passing relationships before the first substitution.
            Node size represents number of completed passes, while line thickness indicates the frequency of connections between players. Only connections with at least six passes are displayed.
        </p>
    </div>
    <div class="content-section">
        <h3>Pass Network & Key Influencers</h3>
        <p> 
            The pass network highlights the primary passing relationships within Leverkusen’s build-up structure.
            Several strong connections appear in central areas of the pitch, particularly between Tah, Andrich, Boniface and Xhaka. These players form the core of the team’s circulation, suggesting that progression often occurred through central combinations.
            The influence table reinforces this observation. Tapsoba recorded the highest number of successful passes (44), followed closely by Xhaka (43) and Tah (39). This indicates that the defensive line and central midfielders were heavily involved in controlling possession during this phase of the match.
            In total, Leverkusen completed 272 successful passes before the first substitution, illustrating a sustained phase of controlled circulation.
        </p>    
    </div>
    <!-- Section 2 --> 
    <!-- Visualization 2: Red de pases2 -->
    <div class="visualization">
        <img src="{{ site.baseurl }}/assets/images/2_average_positions.png" alt="Shot Map Bayern Munich vs Leverkusen">
        <p class="viz-caption">
            <strong>Figure 2: </strong>Average on-ball positions based on successful passes.
            Marker size represents passing involvement, providing a snapshot of Leverkusen’s spatial structure during possession.
        </p>
    </div>
    <div class="content-section">
        <h3>Average Positions & Team Shape</h3>
        <p> 
            The average positions provide insight into Leverkusen’s spatial organization during possession.
            The visualization shows a compact cluster of players in central midfield areas, particularly around the center circle. This suggests that the team prioritized central control to facilitate short passing combinations.
            At the same time, players such as Tella and Adli appear positioned wider and slightly higher on the pitch, providing width and stretching the opposition’s defensive shape.
            The defensive line, led by Tapsoba and Tah, remains relatively advanced, supporting circulation and helping maintain territorial control.
        </p>    
    </div>
    <!-- Section 3 -->
    <!-- Visualization 1: Red de pases3 -->
    <div class="visualization">
        <img src="{{ site.baseurl }}/assets/images/3_xhaka_pass_map.png" alt="Shot Map Bayern Munich vs Leverkusen">
        <p class="viz-caption">
            <strong>Figure 3: </strong>Successful passes completed by Granit Xhaka during the analyzed phase.
            Arrows represent pass direction and length, highlighting his role in connecting midfield circulation.
        </p>
    </div>
    <div class="content-section">
        <h3>Individual Analysis – Granit Xhaka</h3>
        <p> 
            This pass map illustrates Granit Xhaka’s distribution during the analyzed phase of the match.
            The visualization highlights the direction and location of his successful passes, showing how he contributed to maintaining circulation in central midfield areas.Several forward-oriented passes are also visible, indicating attempts to progress possession into more advanced zones.
        </p>    
    </div>
    <!-- Conclusion -->
    <div class="conclusion-box">
        <h3>💡 Tactical Insight</h3>
        <p style="margin-bottom:16px;">
            Taken together, the three visualizations suggest that Leverkusen’s possession structure relied heavily on central connectivity.
            The defensive line and central midfielders handled most of the circulation, while wide players provided positional width to stretch the pitch.
            Within this structure, Granit Xhaka played an important role in linking phases of possession and maintaining the rhythm of the team’s build-up.
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
