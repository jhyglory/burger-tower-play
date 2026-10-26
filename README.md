# Burger Tower

Play free: https://jhyglory.github.io/burger-tower-play/

This repository contains the compiled browser game (v0.31.0). The original development project and its history are maintained in a separate private repository.

Music: Countertop Stroll, an original arrangement using FreePats Electric Guitar FSBS Clean #1 (CC0-1.0): https://freepats.zenvoid.org/ElectricGuitar/clean-electric-guitar.html

Physics: a custom 2D material-point solver. Older hashed runtime assets are retained for cached game pages; see THIRD_PARTY_NOTICES.txt for legacy asset notices.

The game uses Google Analytics 4 for visit and gameplay metrics. Game nicknames, player UUIDs and raw share text are excluded from analytics events.

Result rankings use an interactive diner-style board: compact Top 3, expandable Top 10, and a highlighted confirmed player row. Standings come from the live Supabase service; no sample scores are bundled.

The supplied portrait diner artwork decorates the result scene only. Rankings, nicknames, scores and controls remain live HTML/CSS/JavaScript. Saved result cards keep their existing design.
