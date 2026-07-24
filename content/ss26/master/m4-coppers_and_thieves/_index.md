+++


project_id = "M4"
title = "Coppers&thieves"

# subtitle erscheint auf Übersichtsseite und Projektseite direkt unter dem Titel.
# kurzer 2. titel, der klar über den Inhalt des Projektes informiert
subtitle = "Online Multiplayer Stealth Game"

# der claim oder auch teaser erscheint auf Übersichtsseite und Projektseite nach Titel und Subtitle
claim = "Pull off the perfect museum heist, or hunt down the thieves before they escape in this 3–6 player Unity multiplayer stealth game."

# Properties for displaying the project in the project list
card_image = "icon.png"

# Names are optional, team size is sufficient
team = ["Billy", "David", "Erik", "Frederick", "Jana", "Matthis", "My"]
# this can be just one or a list as with team:
supervisor = "Finley Baguio"
draft = false


# e.g. github
source_link = ""
# link to a demo site / where your project is available.
# it's ok if it's temporary / just for the showtime, 
# just send a pr when you take the demo site down.
demo_link = ""
# website: if you have another project website (not demo)
website_link = ""
+++

{{<section title="Our Goal">}}
Our goal was to create a fun and easy-to-play 2D online multiplayer game where players can experience the thrill of a heist. This project was developed in cooperation with the game studio GaHa Games, who came up with the initial concept for the game.

The game is played by two teams: the Coppers and the Thieves. The Thieves must steal artifacts from a museum, while the Coppers try to stop them by finding and capturing the Thieves.

To emphasize the stealth aspect of a heist, we wanted to incorporate both a line-of-sight vision system and proximity voice chat. The line-of-sight vision system is a custom lighting mechanic where players and objects are only visible when they are within the player's direct field of view or illuminated by light sources.

These goals resulted in the following main technical challenges:

- **Listen-server multiplayer**
- **Custom lighting and shadow system**
- **Proximity voice chat with a custom audio system**

{{</section>}}


{{<section title="Process and Outcome">}}
* **Process**

We worked according to the Scrum methodology in weekly sprints. As students, we focused primarily on technical development while also contributing to selected design tasks. GaHa Games provided continuous feedback during our sprint reviews and supplied all art assets for the project.

Task management was handled through HacknPlan, where we tracked weekly assignments, marked completed tasks, and redistributed unfinished work. During each sprint meeting, we ensured that every team member had clearly defined responsibilities. Although each person concentrated on specific areas of the game, we intentionally rotated tasks to maintain variety and broaden our skill sets.

Throughout development, we conducted regular internal play sessions to evaluate the current game state. These tests were particularly valuable for identifying networking issues, assessing the impact of design decisions on gameplay enjoyment, and generating new design ideas. In the final weeks of the project, we organized external playtests to determine whether the game was intuitive for new players and to gather independent feedback on key design choices.

* **Outcome**

We developed a 2D game using the Unity engine. The multiplayer functionality was implemented with Unity's Netcode for GameObjects, while the low-level networking was handled using Steam's peer-to-peer solution. For in-game voice chat, we integrated Unity's Vivox service. We also used FMOD and developed custom audio systems to dynamically adapt both game audio and voice chat. The light and vision system was created using a combination of raycasts, mesh generation, and custom shaders, inspired by the 2013 game Monaco.
{{</section>}} 


{{<section title="Team">}}

{{</section>}} 



{{<gallery>}}
{{<team-member image="icon.png" name="Billy">}}
{{<team-member image="icon.png" name="David">}}
{{<team-member image="icon.png" name="Erik">}}
{{<team-member image="icon.png" name="Frederick">}}
{{<team-member image="icon.png" name="Jana">}}
{{<team-member image="icon.png" name="Matthis">}}
{{<team-member image="icon.png" name="My">}}
{{</gallery>}}

