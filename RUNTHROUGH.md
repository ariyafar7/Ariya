# Michael the Microbe: prototype run-through (v4)

A concept 8-bit Doodle game for **World IBS Day (19 April)**. It opens outside the body: Michael, a green gut microbe, stands beside a person's silhouette with a faint outline of their gut showing. The player chooses who to follow, **Sam** (a uni student) or **Alex** (a new graduate starting work). The scene then zooms smoothly into the person's mouth, and Michael dives about 8.9 m through the gut. Each stop shows a moment from the chosen person's stressful fortnight and one thing stress is doing inside them.

- **Playable prototype:** `index.html` (also published as an Artifact)
- **Question text and follow-up content:** `CONTENT.md` (the live text for both characters is in the `STOPS`, `MEET` and `CHARS` data near the top of the `<script>` in `index.html`)
- **Sources and fact-check list:** `EVIDENCE.md`
- **Audience:** mainly people moving into university or work; secondarily the general public
- **Length:** 9 stops, 2 mini-games, a breathing break, a sorting bonus and a results screen. About 6 minutes, with no timer.
- **Not affiliated with any search engine.** The Doodle placement is a concept mock-up, and the prototype uses no real logos.

## 1. How people reach it
The page is a clean parody homepage spelled **"elgoog"** (Google backwards), so no real logo or name is used.

1. **The Doodle:** a pixel artwork with a pink pixel frame around a starry navy sky. It spells "elgoog" in colourful microbe dots, with **Michael (green) and Bifi (purple) as the two o's**, and **WORLD IBS DAY** underneath in large pixel capitals ("IBS" in pink). The stars twinkle, and Michael and Bifi bob and grin when hovered.
2. **Under the Doodle:** a search bar (a mock: searching just points back to the Doodle) and two buttons, "elgoog Search" and "I'm Feeling Gutsy".
3. **Opening the game:** clicking the Doodle, or "I'm Feeling Gutsy", slides the logo aside and grows the game window out of the Doodle as a popup next to the logo. The gut map fades in beside it.
4. **Closing the game:** the game's × button shrinks the game back into the Doodle. Progress is kept, and the caption changes to "Tap Michael & Bifi to keep playing".
5. **Layout:** on phones the game opens below the Doodle and the search bar is hidden while playing. A footer line says it's a concept Doodle for a university project and not affiliated with any search engine. "Prototype notes" (top right) opens the run-through drawer.

## 2. Flow

| # | Screen | Depth | Interaction | Takeaway |
|---|---|---|---|---|
| 0 | Title: Michael beside the silhouette | outside | Michael introduces himself; "Did you know?" fact card | IBS affects about 1 in 25 people, and it's real |
| 0b | Choose who to follow | outside | Sam (uni student) or Alex (new graduate at work), then a pixel zoom into the mouth | Stress looks different for everyone |
| 1 | Mouth | 0.00 m | Scenario multiple choice | A dry mouth and clenched jaw are stress signs |
| 2 | Oesophagus | 0.25 m | True/false quick-fire (3 statements) | The brain and gut talk both ways |
| 3 | Stomach | 0.45 m | Put the stress chain in order | Stress hormones slow the stomach, so eat small rather than skip |
| 🎮 | **Mini-game 1: pop the stress bubbles** | 0.60 m | Tap 6 bubbles labelled with the person's stressors. Each pop reveals one step of the stress chain, from the brain to the gut bacteria. | Stress travels all the way to the gut |
| ☁ | Breathing break | 0.60 m | 3 slow breaths (skippable) | You can turn down how strongly your body reacts |
| 4 | Small intestine | 1.20 m | Scenario: a presentation (class or team) | Stress can make the gut lining let more through, so build in rest |
| 5 | Ileum | 4.50 m | Fill the gap | Most serotonin is made in the gut, and it sets gut speed |
| 6 | Colon | 7.20 m | Myth-buster: "just take a probiotic" | Probiotics are an optional extra, not a fix |
| 🎮 | **Mini-game 2: meet another microbe** | 7.80 m | Michael meets Bifi, his purple twin, a fibre-loving bacterium (*Bifidobacterium*). The player picks at least 2 of 4 questions, then Bifi joins the colony. | Stress changes the microbes' world; fibre feeds them; microbes talk back to the brain |
| 7 | Sigmoid colon | 8.40 m | Tap the alarm cell next to the nerve (true/false fallback) | Gut nerves get turned up, and the pain is real |
| 8 | Rectum | 8.75 m | Choose the person's path: 3 decisions moving a stress meter and gut meter (different decisions for Sam and Alex) | Sleep, regular meals and a walk with a friend help |
| 9 | Exit | 8.90 m | Poo chart: tap at least 3 of the 7 Bristol poo types, then a question on which IBS type a pattern of mushy or watery poo points to. A cute pixel poo appears beside Michael. | Poo type can show how IBS is affecting the gut: hard lumps lean IBS-C, mushy or watery lean IBS-D, both is IBS-M |
| ★ | Gut kit | 8.90 m | Swipe to sort 8 cards (buttons and arrow keys work too) | What actually helps IBS |
| ★ | Pick one | 8.90 m | Choose one thing to try this week | Small changes stick |
| ★ | Finale | toilet | Michael fades and glides into the poo (which sprouts his green tails), the scene fades to a pixel bathroom, and the poo drops into a toilet, splashes and is flushed. | |
| ★ | THE END | toilet | "THE END" over the toilet, a big Dive again button, then score, pledge, 4 takeaways, when to see a doctor, share, Read more | |

**Every stop has the same parts:**
1. Michael's line, typed out RPG-style
2. The person's scenario
3. The interaction
4. Feedback for right and wrong answers
5. A **Try this** tip
6. An optional **Read more** section: a short plain-language summary, then the papers behind it as further reading. There are no ratings or badges, and it stays closed unless opened.

Each stop cleared and each mini-game completed adds a microbe to the colony that follows Michael. Wrong answers still move Michael on.

**What changes between Sam and Alex:** every scenario line, the stress bubble labels, Bifi's opening line, the three end decisions, and the results heading. The science, questions and answers stay the same.

## 2c. Gut map (beside the game)

A pixel person stands beside the game window with their whole digestive tract drawn in: mouth, oesophagus, stomach, small intestine coils, colon frame, sigmoid, rectum and exit.

- **Magnifier:** a square magnifying glass follows Michael along the tract in real time, showing a zoomed-in view with Michael inside.
- **Route:** a green trail shows the route he has travelled so far. Yellow dots mark the stops.
- **Gut microbes:** tiny coloured dots along the tract, one more per section going down (few near the mouth, most in the colon), matching the background microbes in the game.
- **Label:** under the figure, the current place (for example "Stomach") and "0.45 m in · stop 3 of 9". Before the dive Michael waits beside the person's feet. After the flush the map shows the poo outside the body and "Flushed away!".
- **Layout:** on desktop it sits to the left of the game window. On phones it sits below the game as a compact card.

## 3. The pixel scene
The tunnel is kept calm so players can focus on the question.
- **Background:** small, faded Michael-style and Bifi-style microbes, far behind the action, scrolling slower than the walls so they read as distant. One more appears each section going down: 1 in the mouth, 2 in the oesophagus, 3 in the stomach, 4 in the small intestine, 5 in the ileum, and 6 in the colon, sigmoid colon, rectum and exit. There are no food crumbs or mixed microbe shapes.
- **No pets:** nothing follows Michael around. The "Colony" counter in the corner still counts up as a score.
- **Mouth:** rows of teeth
- **Oesophagus:** muscle rings
- **Stomach:** folded walls and a stomach-acid pool with a few bubbles
- **Small intestine:** a few bile drips and finger-like villi
- **Ileum:** more villi
- **Colon:** pouched walls
- **Sigmoid colon:** red alarm cells (mast cells) and a nerve appear for the tap activity
- **Rectum:** pouched walls
- **Exit:** ringed walls (the sphincter muscles) and a cute pixel poo with a face, which stays for the gut kit and pledge screens
- **Finale:** Michael fades into the poo with sparkles. The poo gains Michael's three green tails, then the scene fades to a tiled pixel bathroom where the poo drops into a toilet, splashes and swirls away. "THE END" drops in above the toilet.
- **Opening:** a night-sky scene with a person's silhouette, a faint pink outline of the GI tract inside them, and Michael at double size beside them. Sam holds a book; Alex holds a briefcase. The dive starts with a smooth zoom: the mouth opens, Michael glides in and shrinks, and the open mouth crossfades into the teeth tunnel.
- **Mini-games:** pixel stress bubbles float over the scene; Bifi, Michael's purple twin, swims beside him during the chat

## 4. Design decisions (for the reflective report)
- **Practical first.** Each stop starts with something the player recognises and ends with one thing to do. Scientific terms are kept for "Read the research".
- **Read more, not ratings.** Papers are offered as optional further reading after a plain summary, so the main game stays free of scientific clutter.
- **Personal stories.** Choosing Sam or Alex ties each mechanism to a realistic study or work moment.
- **Science through characters.** The mini-games and Bifi's conversation explain biology through story, not extra quiz questions.
- **IBS-specific advice.** Diet tips follow the 2021 UK IBS guideline (soluble fibre added slowly, a dietitian before strict diets), not general "gut health" advice, which can trigger IBS symptoms.
- **No timer, and never punishing.** The audience is already stressed.
- **Tap-only interactions.** There's no typing on phones. Swiping also works with buttons and arrow keys, and the tap activity has a true/false fallback.
- **The breathing break** models a coping tool instead of only describing it.
- **Sound is off by default** because it's on a search page.
- **Original sprites,** drawn in the style of the team's reference image. The reference itself is a stock image and is not used.

## 5. Before final submission
- Resolve the ⚠ items in `EVIDENCE.md` and `CONTENT.md`: the serotonin source, the dry-mouth source, "regular meals" and the "see a doctor" list.
- Check every quoted number against the full papers.
- The team rewrites `CONTENT.md` in its own words, and the design team replaces the placeholder sprites. Record both in the AI-use log.
