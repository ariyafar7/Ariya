# Michael the Microbe: prototype run-through (v9)

A concept 8-bit Doodle game for **World IBS Day (19 April)**. It opens outside the body: Michael, a green gut microbe, stands beside a person's silhouette with a faint outline of their gut showing. The player taps a "Click here to play" bubble to play as **Sam** (a uni student) or **Alex** (a new graduate starting work). The scene then zooms smoothly into the person's mouth, and Michael dives about 8.9 m through the gut. Each stop shows a moment from the chosen person's stressful fortnight and one thing stress is doing inside them.

- **Playable prototype:** `index.html` (also published as an Artifact)
- **Question text and follow-up content:** `CONTENT.md` (the live text for both characters is in the `STOPS`, `MEET` and `CHARS` data near the top of the `<script>` in `index.html`)
- **Sources and fact-check list:** `EVIDENCE.md`
- **Audience:** mainly people moving into university or work; secondarily the general public
- **Not affiliated with any search engine.** The Doodle placement is a concept mock-up, and the prototype uses no real logos.

## 1. How people reach it
The page is a clean parody homepage spelled **"elgoog"** (Google backwards), so no real logo or name is used.

1. **The logo:** a clean wordmark in the same layout as the familiar search-engine logo, spelled **"Elgoog"** (capital E, lowercase final g) in its four colours reversed: E red, l green, g blue, then **Michael and Bifi as the two o's** in pixel art, coloured yellow and red on the logo to match the o colours (they're green and purple inside the game), and a blue g. Above it sits a "World IBS Day" label with a pale blue awareness ribbon (a looped band whose tails cross, the back tail darker). When the game opens, only Michael (the yellow left microbe) zooms in; Bifi and the letters stay put. The font is Poppins, a free look-alike, since the real logo typeface isn't freely available. Michael and Bifi bob, and grin when hovered.
2. **Under the Doodle:** a search bar (a mock: searching just points back to the Doodle) and two buttons, "elgoog Search" and "I'm Feeling Gutsy".
3. **Opening the game:** the caption under the Doodle says "▶ Tap on the microbes to play". Clicking the Doodle, or "I'm Feeling Gutsy", first plays a moment on the homepage itself: the caption changes to "Say ahh!", Bifi gets excited, and Michael opens his mouth in three steps (a small "o", then open, then a wide "ahh") while a rising chirp plays. Then it zooms into **Michael's open mouth**: the pixels grow until his mouth fills the screen and goes dark, and the game fades in **full screen**.
4. **Closing the game:** the game's × button (or Esc) zooms back out of Michael's mouth to the Doodle, and he closes his mouth again. Progress is kept, and the caption changes to "Tap on the microbes to keep playing".
5. **Full-screen layout:** on desktop, the gut map is on the left, the big pixel scene in the middle and the story panel on the right. In narrower windows (900 px and below: half-screen browser tabs, tablets and phones) it switches to a compact layout that still fills the whole window: the scene sits above the story panel and the gut map is hidden. The pixel size adapts to both the width and height of the scene, so wide, short windows don't squash it. There are **no scores or counters** (no colony count, depth, stop number or progress gauge), so the focus stays on the story. A footer line says it's a concept Doodle for a university project and not affiliated with any search engine. "Prototype notes" (top right) opens the run-through drawer.

## 2. Flow

| # | Screen | Depth | Interaction | Takeaway |
|---|---|---|---|---|
| 0 | Title: Michael beside the silhouette | outside | Michael introduces himself; a speech bubble says "Click here to play" | Stress travels from your head to your gut |
| 0b | Play as Sam or Alex | outside | Two short cards, each with a "Click here to play" bubble, then a "Click here to dive in" bubble and a pixel zoom into the mouth | Stress looks different for everyone |
| 0c | Quick check: what is IBS? | outside | Michael asks "have you heard of IBS?"; one multiple-choice question (what IBS stands for), feedback and a Did you know, then Michael explains that stress changes how the gut works, and the dive button | IBS is irritable bowel syndrome, and stress can contribute to its symptoms |
| 1 | Mouth | 0.00 m | A warm-up true/false statement (stress only affects the mind?) with instant feedback, then a scenario multiple choice that differs for Sam (1am before the exam) and Alex (night before the new job) | A dry mouth and clenched jaw are stress signs |
| 2 | Oesophagus | 0.25 m | Michael narrates the scenario; group chat: tap to reveal three messages between the brain and gut, then a multiple-choice question on what the chat shows | The brain and gut talk both ways, and each can influence the other |
| 3 | Stomach | 0.45 m | Put the stress chain in order: steps go into the slots in any order (tap a placed step to take it back out), then it checks | Stress hormones slow the stomach, so eat small rather than skip |
| 🎮 | **Mini-game 1: pop the stress bubbles** | 0.60 m | Tap 6 bubbles labelled with the person's stressors. Each one bursts with a pixel pop; once all are popped, Michael says "Woah! Lots of stressors!" and leads into breathing. | Stress travels all the way to the gut |
| ☁ | Breathing break | 0.60 m | 3 slow breaths (skippable) | You can turn down how strongly your body reacts |
| 4 | Small intestine | 1.20 m | Select all that apply (6 options): the gut lining becoming more permeable and the microbiome changing are both right; check, with one more try | Stress can make the gut lining leakier and shift the gut bacteria |
| 5 | Ileum | 4.50 m | Connect the dots | Stress changes gut signals like serotonin, so food can move through faster |
| 6 | Colon | 7.20 m | Myth-buster: "just take a probiotic" | Probiotics are an optional extra, not a fix |
| 🎮 | **Mini-game 2: meet another microbe** | 7.80 m | Michael meets Bifi, his purple twin, a fibre-loving bacterium (*Bifidobacterium*). The player picks at least 2 of 4 questions, then Bifi joins the colony. | Stress changes the microbes' world; fibre feeds them; microbes talk back to the brain |
| 7 | Sigmoid colon | 8.40 m | GP check-in: tap everything that could help the GP understand what's going on (7 notes, 6 helpful, 1 unhelpful), then check the notes, each with a why | The pain is real, and a GP diagnoses IBS from the symptom pattern, so describe it clearly and never play it down |
| 8 | Rectum | 8.75 m | Finding balance: 3 decisions moving a stress meter and gut meter (different decisions for Sam and Alex) | Sleep, regular meals and a walk with a friend help |
| 9 | Exit | 8.90 m | Poo chart: tap at least 3 of the 7 Bristol poo types, then a question on which IBS type a pattern of mushy or watery poo points to. A cute pixel poo appears beside Michael. | Poo type can show how IBS is affecting the gut: hard lumps lean IBS-C, mushy or watery lean IBS-D, both is IBS-M |
| ★ | Gut kit | 8.90 m | Swipe to sort 8 cards (buttons and arrow keys work too) | What actually helps IBS |
| ★ | Pick one | 8.90 m | Choose one thing to try this week | Small changes stick |
| ★ | Finale | toilet | Michael dissolves into the poo, the scene fades to a pixel bathroom, and the poo drops into a toilet, splashes and is flushed. | |
| ★ | THE END | toilet | "THE END" over the toilet, a big Dive again button, the pledge, then **Your gut toolkit**: six drop-down groups of practical fixes (closed by default, except the urgent-support group), every item with at least one web link so it all works online, each linking to a trusted (mostly Australian) resource: calm the stress response (Smiling Mind, THIS WAY UP, MindSpot, headspace); retrain the gut–brain connection (Mind over Gut, the Nerva hypnotherapy app); feed your gut (healthdirect fibre and gut health, Monash FODMAP, find a dietitian, probiotics); move and sleep (movement guidelines, Sleep Health Foundation); get checked (Bristol chart, find a GP, healthdirect IBS, The IBS Network); and need to talk now (Lifeline, Beyond Blue, tap-to-call). Then when to see a doctor, share, Digest the evidence | Practical tools to act on |

**Every stop has the same parts, kept short so there's little scrolling:**
1. The organ's name in large pixel letters, centred at the bottom of the gut scene. As soon as Michael sets off for the next organ, the last organ's name fades out and the next one fades in, so you see each change on the way down (skipping ahead steps through every organ passed). The two mini-games sit between stops, so they show the organ Michael is heading to (Small intestine for the stress bubbles, Sigmoid colon for Meet Bifi). It's hidden outside the body and in the toilet finale.
2. Michael's speech bubble, typed out RPG-style, telling the person's scenario (one sentence)
3. The question and interaction
4. A verdict ("Correct! +1 microbe" or "Not quite") and **one "Did you know?" sentence** about that stop
5. An optional **Digest the evidence** section, closed by default, holding everything else: the full explanation of the answer, a **Try this** tip, a plain-language summary, then the papers as further reading. No ratings or badges.

The Rome IV criteria and how common IBS is (about 4 in 100 worldwide) now sit in the exit stop's Digest the evidence, beside the poo chart, instead of on the title screen. The end screen keeps the results, the pledge and the "see a doctor" box visible; the four takeaways and all the papers are in its Digest the evidence.

**One more try:** a first wrong answer on any question shows "Not quite", a short nudge and a **One more try** button. The answer is only revealed after the second go. Multiple choice crosses out the option already tried; put-in-order keeps the steps already in the right place; Tell the GP lets the player change their picks; choose-the-path replays the three choices. Wrong answers still move Michael on. Verdicts are words, not scores ("Correct!", "Nice work!", "Not quite").

**What changes between Sam and Alex:** every scenario line, the stress bubble labels, Bifi's opening line, the three end decisions, and the results heading. The science, questions and answers stay the same.

## 2b. Skip menu
A yellow **Skip to ▲** button sits in the bottom-right corner of the game. It opens a list of every section: Start, the 9 stops, the two mini-games (tagged GAME), Gut kit and The end. The current section is highlighted. Picking one makes Michael zoom quickly through the gut to that section, so a viewer (or a marker) can jump straight to the part they want to see. It closes with Esc or a click outside.

## 2c. Gut map (beside the game)

A pixel person stands beside the game window with their whole digestive tract drawn in: mouth, oesophagus, stomach, small intestine coils, colon frame, sigmoid, rectum and exit.

- **Magnifier:** a square magnifying glass follows Michael along the tract in real time, showing a zoomed-in view with Michael inside.
- **Route:** a green trail shows the route he has travelled so far. Yellow dots mark the stops.
- **Gut microbes:** tiny coloured dots along the tract, one more per section going down (few near the mouth, most in the colon), matching the background microbes in the game.
- **Label:** under the figure, the current place (for example "Stomach"), with no distances or stop numbers. Before the dive it says "Waiting to dive in" and Michael waits beside the person's feet. After the flush the map shows the poo outside the body and "Flushed away!".
- **Layout:** on desktop it's the left column of the full-screen game, with no legend: the figure is scaled up to fill the column. In the compact layout (900 px and below) it's hidden to save space.

## 3. The pixel scene
The tunnel is kept calm so players can focus on the question.
- **Background:** small, faded Michael-style and Bifi-style microbes, far behind the action, scrolling slower than the walls so they read as distant. One more appears each section going down: 1 in the mouth, 2 in the oesophagus, 3 in the stomach, 4 in the small intestine, 5 in the ileum, and 6 in the colon, sigmoid colon, rectum and exit. There are no food crumbs or mixed microbe shapes.
- **No pets and no counters:** nothing follows Michael around, and nothing overlays the scene.
- **Mouth:** rows of teeth
- **Oesophagus:** muscle rings
- **Stomach:** folded walls and a stomach-acid pool with a few bubbles
- **Small intestine:** a few bile drips and finger-like villi
- **Ileum:** more villi
- **Colon:** pouched walls
- **Sigmoid colon:** red alarm cells (mast cells) float near a yellow nerve line; the one on the nerve pulses (decoration for the Tell the GP activity)
- **Rectum:** pouched walls
- **Exit:** ringed walls (the sphincter muscles) and a pixel-art poo drawn like the 💩 emoji (curled tip, three glossy tiers, big eyes, wide smile), which stays for the gut kit and pledge screens
- **Finale:** Michael slides into the poo and breaks up in an 8-bit dither while sparkles circle it. With a sparkle burst, the poo does two happy hops. The scene fades to a tiled pixel bathroom: the poo falls into the toilet and lands floating in the water (face still showing) with a splash. The handle dips, the water turns into a whirlpool, and the poo spins round, shrinks and is flushed away. "THE END" drops in above the toilet, and a little sparkle twinkles over the clean bowl.
- **Opening:** a plain dark backdrop (no twinkling lights) with a person's silhouette, a faint pink outline of the GI tract inside them, and Michael at double size beside them. Sam holds a stack of three pixel textbooks (red, green and purple); Alex holds a large brown briefcase with a handle and two gold clasps. The dive starts with a smooth zoom: the mouth opens, Michael glides in and shrinks, and the open mouth crossfades into the teeth tunnel.
- **Mini-games:** pixel stress bubbles float over the scene (kept clear of the organ name, and they fade out the instant they are tapped); Bifi, Michael's purple twin, fades in and swims beside him during the chat. The poo fades in at the exit too.

## 4. Design decisions (for the reflective report)
- **Practical first.** Each stop starts with something the player recognises and ends with one thing to do. Scientific terms are kept for "Digest the evidence".
- **Digest the evidence, not ratings.** Papers are offered as optional further reading after a plain summary, so the main game stays free of scientific clutter.
- **Personal stories.** Choosing Sam or Alex ties each mechanism to a realistic study or work moment.
- **Science through characters.** The mini-games and Bifi's conversation explain biology through story, not extra quiz questions.
- **IBS-specific advice.** Diet tips follow the 2021 UK IBS guideline (soluble fibre added slowly, a dietitian before strict diets), not general "gut health" advice, which can trigger IBS symptoms.
- **No timer, and never punishing.** The audience is already stressed.
- **Tap-only interactions.** There's no typing on phones. Swiping also works with buttons and arrow keys.
- **The breathing break** models a coping tool instead of only describing it.
- **Soundtrack:** the team's own track (`soundtrack.mp3`, re-encoded to 128 kbps from the 320 kbps original to fit the publishing limit) starts when the player taps into the game from the Doodle, fades in, and loops. Browsers only allow sound after a tap, which is why it starts there. Closing the game fades it out, and reopening picks up where it left off. A MUSIC ON/OFF button sits in the game header.
- **No sound effects:** the SFX button was removed; the soundtrack is the only audio (MUSIC ON/OFF in the header).
- **Readable pixel fonts.** Body text uses Jersey 15 and labels and buttons use Silkscreen: both are pixel fonts but much clearer at small sizes than the wide Press Start 2P, which is kept only for big display text (the title and THE END).
- **Original sprites,** drawn in the style of the team's reference image. The reference itself is a stock image and is not used.

## 5. Before final submission
- Resolve the ⚠ items in `EVIDENCE.md` and `CONTENT.md`: the serotonin source, the dry-mouth source, "regular meals" and the "see a doctor" list.
- Check every quoted number against the full papers.
- The team rewrites `CONTENT.md` in its own words, and the design team replaces the placeholder sprites. Record both in the AI-use log.
