# Michael the Microbe: prototype run-through (v3)

A concept 8-bit Doodle game for **World IBS Day (19 April)**. Michael, a green gut microbe, dives about 8.9 m through the gut, following **Sam**, a first-year student with a part-time job, through one stressful exam fortnight. Each part of the gut shows one moment in Sam's fortnight and one thing stress is doing inside them.

- **Playable prototype:** `index.html` (also published as an Artifact)
- **Question text and follow-up content:** `CONTENT.md`
- **Sources, evidence badges and fact-check list:** `EVIDENCE.md`
- **Audience:** mainly people moving into university or work; secondarily the general public
- **Length:** 8 stops, a halfway breathing break, a sorting bonus and a results screen. About 5 minutes, with no timer.
- **Not affiliated with any search engine.** The Doodle placement is a concept mock-up, and the prototype uses no real logos.

## 1. How people reach it
1. **On the homepage:** a pixel Michael tile ("Michael the Microbe · World IBS Day") opens the game.
2. **In search results:** searches about IBS, gut pain or stress show the game beside the results. On a phone it opens full-screen.
3. **Minimising:** × shrinks it to a "Resume Michael" pill.

## 2. Flow

| # | Screen | Depth | Interaction | Takeaway |
|---|---|---|---|---|
| 0 | Title + "Did you know?" | 0.00 m | Fact card with research panel | IBS affects about 1 in 25 people, and it's real |
| 1 | Mouth | 0.00 m | Scenario multiple choice | A dry mouth and clenched jaw are stress signs |
| 2 | Oesophagus | 0.25 m | True/false quick-fire (3 statements) | The brain and gut talk both ways |
| 3 | Stomach | 0.45 m | Put the stress chain in order | Stress hormones slow the stomach, so eat small rather than skip |
| 4 | Small intestine | 1.20 m | Scenario: Sam's presentation | Stress can make the gut lining let more through, so build in rest |
| ☁ | Breathing break | 1.20 m | 3 slow breaths (skippable) | A stress-calming tool to try now |
| 5 | Ileum | 4.50 m | Fill the gap | Most serotonin is made in the gut, and it sets gut speed |
| 6 | Colon | 7.20 m | Myth-buster: "just take a probiotic" | Probiotics are an optional extra, not a fix (plus a "Want more?" card on fibre) |
| 7 | Sigmoid colon | 8.40 m | Tap the alarm cell next to the nerve (true/false fallback) | Gut nerves get turned up, and the pain is real |
| 8 | Exit | 8.90 m | Choose Sam's path: 3 decisions moving a stress meter and gut meter | Sleep, regular meals and a walk with a friend help |
| ★ | Gut kit | 8.90 m | Swipe to sort 8 cards: helps or doesn't help (buttons and arrow keys work too) | What actually helps IBS |
| ★ | Pick one | 8.90 m | Choose one thing to try this week | Small changes stick |
| ★ | Results | 8.90 m | Score, colony size, pledge, 4 takeaways, when to see a doctor, share, sources | |

**Every stop has the same parts:**
1. Michael's line, typed out RPG-style
2. Sam's scenario
3. The interaction
4. Feedback for right and wrong answers
5. A **Try this** tip
6. An optional **Read the research** panel: a plain-language summary under 100 words, with links and a strength badge (●●● strong, ●●○ good, ●○○ early)

Each stop cleared adds a different microbe to the colony that follows Michael. Wrong answers still move Michael on.

## 3. The pixel scene
- **Mouth:** rows of teeth
- **Oesophagus:** muscle rings
- **Stomach:** folded walls and a bubbling stomach-acid pool
- **Small intestine:** bile drips and finger-like villi
- **Ileum:** more villi and more resident microbes
- **Colon:** pouched walls and a crowded mixed community of rods, coccus clusters, bead chains, spiky and hairy microbes
- **Sigmoid colon:** red alarm cells (mast cells) and a nerve appear for the tap activity

## 4. Design decisions (for the reflective report)
- **Practical first.** Each stop starts with something the player recognises and ends with one thing to do. Scientific terms are kept for "Read the research".
- **Evidence badges.** Every source shows its strength in words as well as dots, so colour is never the only cue.
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
