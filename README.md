# State-Charts

## Statechart Diagrams
While working on the statechart diagrams, use the development folder.
For now, use any file extension you'd like.  In the end they will be named .plantuml or something similar to make it obvious what they are.

## Documentation
Any documentation should go in the documentation folder (e.g. LaTeX files)

## Statechart Status
The parent of each diagram is in parentheses after the name of the state.
Please state who is working on any diagram that is marked in progress.
If, after completing a statechart, there are new children statecharts to be made, add them to the bottom of the unassigned list with their parent in parentheses.
Please try to complete state diagrams whose parents are already completed first before doing ones that are awaiting review in case they are changed.
Focus on statecharts that pertain to the star system game first, then the province game and then finally galactic game.  Statecharts that involve the Star System game are **in bold**.

### Completed & Reviewed

### Awaiting Review
 1.  **ProgramOverview**
 1.  OptionsScreen
 1.  **PlayGame**
 1.  **GalacticTurn**

### In progress

### Unassigned
 1.  DisplayMenu (ProgramOverview)
 1.  GameOptionsScreen (ProgramOverview)
 1.  MatchmakingScreen (ProgramOverview)
 1.  PostGameScreen (ProgramOverview)
 1.  ProgramExit (ProgramOverview)
 1.  **ScenarioSetup (PlayGame)**
 1.  **PlayerTurn (GalacticTurn)**
 1.  **RebelControlCheck (GalacticTurn)**
 1.  GalacticStage (GalacticTurn)