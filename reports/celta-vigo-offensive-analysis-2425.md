---
layout: report
title: Celta Vigo - Offensive Analysis
description: Shot map analysis and finishing efficiency Premier League 24/25
category: Team Analysis
competition: Premier League 24/25
date: 2026-01-11
lang: en
---

<!-- ==================== HERO ==================== -->
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
<!-- ==================== EXECUTIVE SUMMARY ==================== -->
<!-- TÚ ESCRIBES: Los 3 insights más importantes del partido -->
<div class="executive-summary">
	<h2>🎯 Executive Summary</h2>
	<ul class="key-insights">
		<li>Celta generated 1.61 xG from 7 shots, overperforming with 2 goals (124% conversion rate)</li>
		<li>100% of shots came from foot/other (0 headers), indicating low cross dependency</li>
		<li>Shot locations concentrated in central zones and edge of box (long-range threat)</li>
	</ul>
</div>
<!-- ==================== CONTENT ==================== -->
<div class="report-content">
	<!-- CONTEXTO DEL PARTIDO -->
	<!-- TÚ ESCRIBES: 2 párrafos sobre el contexto -->
	<div class="content-section">
		<h2>Match Context</h2>
		<p>
			Celta Vigo's offensive performance in Premier League 24/25 
			showed efficiency despite low shot volume. With only 7 total 
			shots, they managed to score 2 goals, beating their expected 
			goals by 0.39.
		</p>
		<p>
			This analysis focuses on shot positioning, quality, and the 
			team's ability to generate high-value chances from central areas.
		</p>
	</div>
	<!-- ==================== GRÁFICO PRINCIPAL ==================== -->
	<!-- TÚ DECIDES: Shot map, heatmap, pass network, etc. -->
	<!-- ESTE ES TU GRÁFICO MÁS IMPORTANTE -->
	<div class="visualization">
		<img src="{{ site.baseurl }}/assets/images/celta-vigo-shot-map.png" alt="Celta Vigo Shot Map">
			<p class="viz-caption">
				<strong>Figure 1:</strong> Shot map showing Celta's 7 shots (2 goals in red). 
			Shots concentrated in central zones with xG of 1.61. No aerial attempts recorded.
        </p>
		</div>
		<!-- ANÁLISIS DEL GRÁFICO PRINCIPAL -->
		<!-- TÚ ESCRIBES: Qué muestra el gráfico y qué significa -->
		<div class="content-section">
			<h2>Shot Quality Analysis</h2>
			<p>
			Celta's 1.61 xG from 7 shots represents an average of 0.23 xG per shot, 
			which is above Premier League average (typically 0.10-0.15). The two goals 
			came from high-quality positions inside the box, both from foot.
		</p>
			<p>
			The absence of headed attempts (0 headers) suggests Celta prioritized 
			ground-based attacks rather than crossing. The concentration of shots 
			in central zones indicates effective ball progression through the middle.
		</p>
		</div>
		<!-- ==================== STATS COMPARISON ==================== -->
		<!-- TÚ LLENAS: Los 4-5 números clave de cada equipo -->
		<div class="stats-comparison">
			<div class="team-stats">
				<div class="team-name">CELTA VIGO</div>
				<div class="stat-row">
					<span class="stat-value">1.61</span>
					<span class="stat-label">Total xG</span>
				</div>
				<div class="stat-row">
					<span class="stat-value">7</span>
					<span class="stat-label">Total Shots</span>
				</div>
				<div class="stat-row">
					<span class="stat-value">2</span>
					<span class="stat-label">Goals</span>
				</div>
				<div class="stat-row">
					<span class="stat-value">0</span>
					<span class="stat-label">Headers</span>
				</div>
			</div>
		</div>
		<!-- ==================== TACTICAL PATTERNS ==================== -->
		<!-- TÚ ESCRIBES: Análisis táctico por equipo -->
		<div class="content-section">
			<h2>Tactical Patterns Identified</h2>
			<h3>Central Progression Dominance</h3>
			<p>
            The shot map reveals Celta's preference for central attacks. 
			With 5 of 7 shots coming from the central corridor (71%), 
			the team clearly avoided wide play in favor of through-balls 
			and penetrations between lines.
        </p>
			<p>
			The long-range shots from outside the box (3 attempts) suggest 
			opportunistic shooting when defenses dropped deep, creating 
			space for edge-of-box strikes.
		</p>
			<h3>High Conversion Efficiency</h3>
			<p>
            Converting 2 goals from 1.61 xG demonstrates clinical finishing. 
			Both goals came from positions with xG values above 0.25, 
			indicating patience to wait for high-quality chances rather 
			than forcing low-percentage shots.
        </p>
		</div>
		<!-- ==================== CONCLUSIÓN ==================== -->
		<!-- TÚ ESCRIBES: Conclusión táctica y recomendaciones -->
		<div class="conclusion-box">
			<h3>💡 Tactical Conclusion</h3>
			<p>
            Celta Vigo demonstrated efficient offense with quality over quantity. 
			Their 7 shots generated above-average xG (0.23 per shot) and clinical 
			finishing (124% conversion rate vs xG). The absence of aerial attempts 
			suggests a ground-based tactical approach.
        </p>
			<p style="margin-top: 16px;">
				<strong>Key Recommendation:</strong> Opponents should compress central 
			spaces to force Celta wide, where they showed less comfort. Preventing 
			through-balls in the central corridor will limit their high-xG chances.
        </p>
		</div>
	</div>
<!-- ==================== METADATA ==================== -->
	<div class="report-metadata">
		<div class="metadata-row">
			<div class="metadata-item">
				<span class="metadata-label">Data Source</span>
				<span>[FUENTE - ej: StatsBomb Open Data, FBref, Wyscout]</span>
			</div>
			<div class="metadata-item">
				<span class="metadata-label">Model</span>
				<span>[MODELO - ej: Custom xG + 15s Threat Window]</span>
			</div>
			<div class="metadata-item">
				<span class="metadata-label">Tools</span>
				<span>[HERRAMIENTAS - ej: Python, mplsoccer, pandas]</span>
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
