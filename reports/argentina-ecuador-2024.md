---
layout: report
title: Bayer Leverkusen vs Bayern Munich - xG & Finishing Analysis
description: Tactical breakdown of Bundesliga's high-stake draw using advanced xG Shot Maps and Danger Flow models..
category: Post-Match Analysis
competition: Bundesliga 23/24
date: 2024-07-04
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
            <strong>Figure 1:</strong> Shot map with xG values. Argentina concentrated their shots 
            in high-value central zones (0.15+ xG), while Ecuador attempted from more distant positions.
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

    <!-- Section 2: xG Analysis -->
    <div class="content-section">
        <h2>Expected Goals Analysis</h2>
        <p>
            Argentina generated a total xG of 2.1, significantly higher than Ecuador's 0.8. 
            The key difference lay in shot position quality: while La Albiceleste 
            shot 8 times from inside the box with an average xG of 0.21, Ecuador only managed 3 shots 
            in that zone with an average xG of 0.13.
        </p>
    </div>

    <!-- Stats Comparison -->
    <div class="stats-comparison">
        <div class="team-stats">
            <div class="team-name">ARGENTINA</div>
            <div class="stat-row">
                <span class="stat-value">2.1</span>
                <span class="stat-label">Total xG</span>
            </div>
            <div class="stat-row">
                <span class="stat-value">14</span>
                <span class="stat-label">Shots</span>
            </div>
            <div class="stat-row">
                <span class="stat-value">8</span>
                <span class="stat-label">In Box</span>
            </div>
            <div class="stat-row">
                <span class="stat-value">8.2</span>
                <span class="stat-label">PPDA</span>
            </div>
        </div>

        <div class="divider"></div>

        <div class="team-stats">
            <div class="team-name">ECUADOR</div>
            <div class="stat-row">
                <span class="stat-value">0.8</span>
                <span class="stat-label">Total xG</span>
            </div>
            <div class="stat-row">
                <span class="stat-value">9</span>
                <span class="stat-label">Shots</span>
            </div>
            <div class="stat-row">
                <span class="stat-value">3</span>
                <span class="stat-label">In Box</span>
            </div>
            <div class="stat-row">
                <span class="stat-value">11.3</span>
                <span class="stat-label">PPDA</span>
            </div>
        </div>
    </div>

    <!-- Section 3: Threat Windows -->
    <div class="content-section">
        <h3>Threat Windows (15s Model)</h3>
        <p>
            Our model identifies high-risk possessions based on spatial progression 
            within 15-second windows. Argentina generated 8 sequences classified as "high threat", 
            primarily after recoveries in the opponent's half.
        </p>
        <p>
            Ecuador, on the other hand, only achieved 3 significant threat windows, all in quick 
            counterattacks where they exploited spaces left by Argentina's high defensive line.
        </p>
    </div>

    <!-- Visualization 2: Heatmap (placeholder) -->
    <div class="visualization">
        <div style="width: 100%; height: 400px; background: linear-gradient(135deg, var(--bg-secondary) 0%, var(--bg-primary) 100%); border-radius: 8px; display: flex; align-items: center; justify-content: center; color: var(--text-secondary); font-size: 18px;">
            [Heatmap of dangerous possessions]
        </div>
        <p class="viz-caption">
            <strong>Figure 2:</strong> Heatmap of possessions classified as high threat. 
            Argentina dominated central spaces between 20-40m from the opponent's goal.
        </p>
    </div>

    <!-- Section 4: Tactical Patterns -->
    <div class="content-section">
        <h2>Tactical Patterns Identified</h2>
        
        <h3>Argentina - Positional Control</h3>
        <p>
            La Albiceleste implemented an effective high-pressing scheme, recovering 12 balls 
            in the opponent's half. Messi operated as a link between lines, generating 0.6 xA from 
            attacking midfielder positions.
        </p>
        <p>
            The defensive line maintained an average height of 52m, allowing quick pressure 
            transitions when losing possession. De Paul and Mac Allister controlled the midfield 
            with an 87% pass completion rate in progressive passes.
        </p>
        
        <h3>Ecuador - Vertical Transitions</h3>
        <p>
            Ecuador opted for long direct outlets to Valencia, who won 8 of 14 aerial duels. 
            However, lack of immediate support limited the generation of dangerous second plays.
        </p>
        <p>
            In organized defense, Ecuador employed a medium block, allowing Argentina possession 
            in non-dangerous zones but closing central passing lanes effectively.
        </p>
    </div>

    <!-- Visualization 3: Pass Network (placeholder) -->
    <div class="visualization">
        <div style="width: 100%; height: 400px; background: linear-gradient(135deg, var(--bg-secondary) 0%, var(--bg-primary) 100%); border-radius: 8px; display: flex; align-items: center; justify-content: center; color: var(--text-secondary); font-size: 18px;">
            [Argentina pass network visualization]
        </div>
        <p class="viz-caption">
            <strong>Figure 3:</strong> Argentina's pass network. Messi acted as the central hub 
            with 78 completed passes, 45% of them progressive.
        </p>
    </div>

    <!-- Conclusion -->
    <div class="conclusion-box">
        <h3>💡 Tactical Conclusion</h3>
        <p>
            Argentina demonstrated superiority in xG generation and spatial control. To neutralize 
            this scheme, future opponents should: (1) avoid Argentina's high press with more elaborate 
            build-up play, (2) close spaces between lines where Messi and De Paul operate, and 
            (3) be more aggressive in transitions to exploit spaces left by the high defensive line.
        </p>
        <p style="margin-top: 16px;">
            <strong>Key Recommendation:</strong> Direct pressing on Rodríguez and Otamendi during build-up 
            could disrupt Argentina's progression, forcing long balls that reduce their effectiveness 
            in creating high xG opportunities.
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
            <span>Custom xG + 15s Threat Window</span>
        </div>
        <div class="metadata-item">
            <span class="metadata-label">Tools</span>
            <span>Python, mplsoccer, pandas</span>
        </div>
        <div class="metadata-item">
            <span class="metadata-label">Analysis by</span>
            <span>analitykaXG</span>
        </div>
        <div class="metadata-item">
            <span class="metadata-label">Published</span>
            <span>{{ page.date | date: "%d %B %Y" }}</span>
        </div>
    </div>
</div>
