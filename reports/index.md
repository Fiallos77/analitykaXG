---
layout: default
title: All Reports
lang: en
---

<!-- REPORTS PAGE HERO -->
<div style="padding: 60px 20px 40px; text-align: center; border-bottom: 1px solid var(--border-color); background: var(--bg-secondary);">
    <h1 style="font-family: 'Montserrat', sans-serif; font-size: 48px; font-weight: 900; margin-bottom: 16px;">All Reports</h1>
    <p style="color: var(--text-secondary); font-size: 18px; max-width: 600px; margin: 0 auto;">
        Full archive of tactical analysis, match breakdowns and player scouting reports.
    </p>
</div>

<!-- FILTROS -->
<div style="padding: 40px 20px 0; max-width: 1200px; margin: 0 auto;">
    <div style="display:flex; gap:12px; flex-wrap:wrap; margin-bottom:40px;">
        <button onclick="filterReports('all')" id="filter-all" style="padding:10px 24px; border-radius:999px; border:none; background:var(--accent-cyan); color:var(--bg-primary); font-weight:700; cursor:pointer; font-size:14px; transition: all 0.3s;">All</button>
        <button onclick="filterReports('team')" id="filter-team" style="padding:10px 24px; border-radius:999px; border:1px solid var(--border-color); background:transparent; color:var(--text-secondary); font-weight:600; cursor:pointer; font-size:14px; transition: all 0.3s;">Teams</button>
        <button onclick="filterReports('match')" id="filter-match" style="padding:10px 24px; border-radius:999px; border:1px solid var(--border-color); background:transparent; color:var(--text-secondary); font-weight:600; cursor:pointer; font-size:14px; transition: all 0.3s;">Matches</button>
        <button onclick="filterReports('player')" id="filter-player" style="padding:10px 24px; border-radius:999px; border:1px solid var(--border-color); background:transparent; color:var(--text-secondary); font-weight:600; cursor:pointer; font-size:14px; transition: all 0.3s;">Players</button>
    </div>

    <!-- GRID -->
    <div class="reports-grid" id="reports-grid" style="display: grid; grid-template-columns: repeat(3, 320px); gap: 32px; justify-content: start;">

        <!-- Card: Celta Vigo -->
        <a href="{{ site.baseurl }}/reports/BayerLeverkusenPassNetwork" class="report-card" data-category="team">
            <div class="report-thumbnail" style="height: 140px;">
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

        <!-- Card: Bayer Leverkusen -->
        <a href="{{ site.baseurl }}/reports/BayerLeverkusenvsBayernMunich" class="report-card" data-category="match">
            <div class="report-thumbnail" style="height: 140px;">
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

        <!-- Card: Coming Soon - Players -->
        <a href="#" class="report-card" data-category="player">
            <div class="report-thumbnail" style="height: 140px;">
                <div style="font-size: 64px; color: var(--accent-cyan); opacity: 0.3;">⚽</div>
            </div>
            <div class="report-content">
                <span class="report-tag">Player Scouting</span>
                <h3>Coming Soon</h3>
                <div class="report-meta"><span>Individual Analysis</span></div>
                <p class="report-excerpt">Upcoming player analysis with comparative radar and heatmaps.</p>
                <span class="report-link">Coming soon <span>→</span></span>
            </div>
        </a>

    </div>
</div>

<script>
function filterReports(category) {
    const cards = document.querySelectorAll('.report-card');
    const buttons = document.querySelectorAll('[id^="filter-"]');

    buttons.forEach(btn => {
        btn.style.background = 'transparent';
        btn.style.color = 'var(--text-secondary)';
        btn.style.border = '1px solid var(--border-color)';
    });

    const active = document.getElementById('filter-' + category);
    active.style.background = 'var(--accent-cyan)';
    active.style.color = 'var(--bg-primary)';
    active.style.border = '1px solid var(--accent-cyan)';

    cards.forEach(card => {
        if (category === 'all' || card.dataset.category === category) {
            card.style.display = 'block';
        } else {
            card.style.display = 'none';
        }
    });
}
</script>
