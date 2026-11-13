# Quiz Akademie

A quizmaster's app: pick question types, teams and questions per type, record each team's answers and keep the score.

Static site, no build step. Host with GitHub Pages (Settings > Pages > Deploy from a branch > main, root).

Fresh questions use the Anthropic API from the browser. Enter the key in the app's Settings; it is stored in that browser only and is never part of this repository. Without a key the app uses its built-in question bank.
