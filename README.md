Soccer Player Grading (raw and per90) + Archetype Allignment

Description: 

This evaluation leverages raw match statistics and Per-90 scaled metrics to accurately measure a player’s contributions and impact across offensive, defensive, passing, and duel-related actions. The Per90 scaling ensures fair comparison regardless of minutes played, which can show efficiency and impact in restricted minutes.

Players are further placed into position-specific archetypes based on their statistical strengths and percentile rankings. Archetypes describe their tactical role and style of play, from goal-scoring specialists (Poacher) to creative playmakers (Regista) or defensive anchors (Stopper).

Following this, component grades summarize performance across five key areas - Offense, Passing, Defense, Duels, and Discipline - culminating in a weighted Player Rating (Player_Rating_FIFA) tailored to position-specific responsibilities.

Raw Player Rating

These grades are made using the player’s total in-game contributions, including goals, assists, passes, duels, recoveries, and defensive actions. Raw stats give a direct view of output but can be biased by playing time or total actions.

Per90 Player Rating

Per90 metrics normalize performance to a full match (90 minutes), allowing fair comparisons between players with different amounts of playing time. They highlight efficiency and impact, showing who consistently performs well when on the field. 

Player Archetypes

Archetypes classify players into position-specific tactical roles based on their statistical strengths. They describe how a player typically operates on the pitch - for example, a striker could be a Poacher (goal-focused) or a Mobile 9 (pace-based transitional attacker), while a central midfielder could be a Box-to-Box or Regista type player, reflecting their defensive and creative balance. Archetypes provide a quick understanding of a player’s style and role beyond raw numbers. These archetypes are found and assigned using the player's Per90 stats as opposed to their raw total stats. 

Player Synergy

Synergy is used to make lineup predictions using past game data. This model will give a fairly accurate estimate of how n players play together if they were to play on the field at the same time for a full 90 minutes. You can make a complete 11 man lineup, or you can just put two players. The synergy_mult (right now is a random number ranging from 0.9 - 1.1) will be a multiplier that wil either benefit or harm predicted numbers based on the amount of actual time players spent on the field together. For example, if Liscum and Sheridan play togther often, their synergy would be high, resulting in better estimated numbers. Eventually, when we get game data for other teams, we will be able to adjust these predictions accordingly based on how the opposing teams play. 
