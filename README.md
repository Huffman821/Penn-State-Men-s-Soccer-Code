# Penn-State-Men-s-Soccer-Code

#Player Grades
Description of the player rating code:

This code basically creates a match rating (and cumulative rating) for each player, kind of like how FIFA rates players after a game (hopefully). It looks at everything a player does on the field, weighs it based on importance, and adjusts for position and how much they were actually involved in the game.

1. What We’re Looking At

The rating takes into account all the actions a player makes:

Offense: Goals, assists, shots on target, key passes or chances created, dribbles, and touches in the box.

Defense: Tackles won, interceptions, clearances, and sliding tackles.

Passing and possession: How accurate their passes were, including forward, backward, and sideways passes, plus turnovers.

Duels and recoveries: Success in one-on-one battles, aerial duels, and loose-ball recoveries.

Discipline: Yellow and red cards, plus fouls.

2. Making It Fair

We don’t just count numbers—there are a few adjustments to keep the ratings realistic:

Sample size matters: Players who do more stuff on the field get more credit. A defender who only touches the ball a few times won’t outrank a forward who’s constantly involved and scores.

Position matters: Defenders aren’t penalized for not scoring, and midfielders get more credit for passing and controlling the game.

Mistakes count: Turnovers, missed tackles, and fouls reduce your score.

3. Weighted Grades

We break the performance into a few grades:

Offensive Grade: Goals, shots, key passes, dribbles, and touches in the box.

Passing Grade: Pass accuracy, crosses, forward passes, key passes, and turnovers.

Defensive Grade: Tackles, interceptions, clearances, and recoveries.

Duel Grade: Success in duels—offensive, aerial, and loose-ball.

Discipline Grade: Cards and fouls.

Each grade is weighted by importance and adjusted for how many actions a player had, so we balance quality and activity.

4. Position-Adjusted Rating

Finally, all the grades are combined into a single Player Rating, with different weights depending on the player’s position:

Forwards get more points for offense.

Midfielders get a mix of offense, passing, and defense.

Defenders focus mostly on defense and duels.

Goalkeepers (if included) are mostly measured on saves, goals allowed, and clean sheets.

5. Standardization and Per90

Standardizing the grades make theme more compareable from one player to another

Also, adjusting the grades by Per90 will allo us to make assumptions about players as if they were playing 90 minutes per making comparison fair

The final rating is scaled to a 0–10 range, deviating from 6.5, so you can easily compare players and see who had the best game.
