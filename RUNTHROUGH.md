# Bifi's Gut Dive: draft run-through

A mock information product for **World IBS Day (19 April)**. It's a short pop-up game that opens beside search results when someone searches for IBS, gut pain or stress. Bifi is a green gut microbe who descends through about 8.9 m of gastrointestinal (GI) tract, from mouth to exit. At each stop the player answers one question about how stress changes the gut.

- **Audience:** people moving into university or the workforce (a high-stress group), written at general-public reading level
- **Length:** 9 stops (6 multiple choice, 3 short answer), a halfway breathing break and a results screen. About 4 minutes, with no timer.
- **Playable draft:** `index.html` (also published as an Artifact)
- **Format inspiration:** the dive-style daily game *Krillion*. Its ocean dive becomes a descent through the gut, and its krill becomes a microbe.
- **Look (v2):** 8-bit pixel art. The scene is drawn at about 130 px wide and scaled up with hard pixels. Headings use a pixel font (Press Start 2P) and body text uses a readable pixel font (Pixelify Sans). Buttons and panels have stepped pixel corners.

---

## 1. How people reach it

1. On 19 April, someone searches something like "why does stress mess with my stomach".
2. A card slides in beside the results (on a phone it comes up as a bottom sheet). It shows "World IBS Day · 19 April" and *Bifi's Gut Dive*.
3. The × button shrinks it to a "Resume Gut Dive" pill, so it never blocks the search.

## 2. Screen-by-screen flow

| # | Screen | Depth | What happens |
|---|--------|-------|--------------|
| 0 | Intro | 0.00 m | "Ride 8.9 metres of gut with Bifi." Chips: 9 stops · about 4 minutes · no timer. **Begin descent ↓** |
| 1 | Mouth | 0.00 m | MCQ: what IBS is |
| 2 | Oesophagus | 0.25 m | MCQ: the brain–gut axis works both ways |
| 3 | Stomach | 0.45 m | **Short answer:** the stress hormone (cortisol) |
| 4 | Duodenum | 0.75 m | MCQ: the rat crowding study and 4× CRF receptors |
| ☁ | Breathing break | 0.75 m | Three slow breaths with Bifi (skippable) |
| 5 | Jejunum | 2.00 m | MCQ: stress makes the gut lining leakier |
| 6 | Ileum | 4.50 m | **Short answer:** most serotonin is made in the gut |
| 7 | Colon | 7.20 m | MCQ: stress causes dysbiosis in the microbiota |
| 8 | Sigmoid colon | 8.40 m | True/false: IBS is "all in your head" |
| 9 | Exit | 8.90 m | **Short answer:** name one way to calm the stress–gut loop |
| ★ | Results | 8.90 m | Score, community size, 4 takeaways, when to see a doctor, share message, sources |

Every question screen follows the same pattern:

1. **Bifi says** a one-line fact about that part of the gut.
2. The **question** appears, in plain language.
3. The player answers, and the feedback explains the answer whether it was right or wrong.
4. **Learn more about this** (optional) opens the mechanism, numbers from the research and a citation.
5. **Keep descending ↓** animates the drop to the next stop. The depth readout counts up in metres, and the tunnel walls change texture: smooth tube, stomach folds, finger-like villi, then colon pouches.

Each correct answer adds a microbe friend that follows Bifi. A bigger, more varied community stands for a healthy microbiota. A wrong answer makes Bifi look stressed for a moment, but the player always moves on.

## 2b. What the player sees on the way down

| Zone | Pixel scene |
|------|-------------|
| Mouth | Rows of white pixel teeth on both walls, a few oral bacteria and food crumbs |
| Oesophagus | Narrow tube with muscle rings |
| Stomach | Folded walls (rugae) and a bubbling pool of yellow stomach acid that Bifi swims through. Bifi says it's about pH 2. |
| Duodenum | Orange-tinted walls with yellow bile dripping in |
| Jejunum, ileum | Finger-like villi on the walls and more and more resident microbes |
| Colon, sigmoid | Pouched walls (haustra) and a crowded, mixed community: rods, cocci clusters, chains, spiky and ciliated microbes |

**Sprites:** Bifi is a 12×16 green bacterium with darker spots, a dark outline and three wiggling flagella. Their face changes with each answer: a smile, a big grin with sparkles when right, or a zigzag mouth and a sweat drop when wrong. Each correct answer adds a different microbe to the colony that follows Bifi. The sprites are original art in the style of the team's reference image, not copies of it.

**HUD:** DEPTH (metres), ZONE and STOP x/9 across the top, COLONY count bottom-left, and a depth gauge on the right split into upper GI, small intestine and colon.

**Dialog box:** each stop opens with Bifi's portrait and a line of text typed out RPG-style (tap to skip).

**Sound:** optional 8-bit chiptune effects (start, dive, right, wrong, breathing tones, stage clear). Off by default because the game pops up on a search page.

## 3. Question bank

### 1 · Mouth: MCQ
**What is IBS (irritable bowel syndrome)?**
- A) A food-poisoning bug that clears up in a few days
- **B) A long-term gut condition with tummy pain and changed toilet habits, where the gut looks normal on tests ✔**
- C) Another name for IBD (inflammatory bowel disease)
- D) An allergy to gluten

*Learn more:* about 1 in 9 people worldwide (11.2%) have IBS. It isn't IBD and it isn't coeliac disease. It arises from the immune, hormone and nervous systems interacting. *(Qin et al., 2014)*

### 2 · Oesophagus: MCQ
**Your brain and your gut are connected. Which way do the messages travel?**
Only brain → gut / Only gut → brain / **Both ways ✔** / They aren't connected

*Learn more:* the enteric nervous system is nicknamed the "little brain". Top-down, stress changes the gut. Bottom-up, gut symptoms raise anxiety. 40–60% of people with IBS also have a mental health condition. *(Qin et al., 2014)*

### 3 · Stomach: short answer
**It's exam week. Glands on top of your kidneys release the main stress hormone. What's it called?**
- Accepted: cortisol, including spelling slips
- "Adrenaline" gets a "So close" message explaining fast versus slow stress hormones
- Hint, plus a "Not sure? Show me" button

*Learn more:* the HPA axis chain is hypothalamus → CRF → pituitary → ACTH → adrenal glands → cortisol. Short-term stress switches itself off. Long-term stress can keep the system switched on. *(Qin et al., 2014)*

### 4 · Duodenum: MCQ
**Rats kept in crowded cages for 15 days (like a packed share-house in exam season) had about 4× more of what in their colon?**
Helpful bacteria / **Receptors for the stress messenger CRF ✔** / Vitamin C / Muscle

*Learn more:* stress hormone levels were about 3.5× higher (165 vs 47 ng/mL), and CRF receptor type-1 was about 4× higher. The most stressed rats had the most receptors. Their poo was looser and more frequent. The study was in rats. *(Vicario et al., 2012)*

### Halfway break
Three slow breathing cycles of 4 seconds in and 4 seconds out, with a growing and shrinking green orb. Caption: slow breathing nudges the body toward "rest and digest".

### 5 · Jejunum: MCQ
**Your gut lining is a wall one cell thick. What does ongoing stress do to it?**
Thicker and stronger / **Leakier, so more slips through ✔** / Nothing / Dissolves it completely

*Learn more:* mast cells release serotonin, proteases and cytokines, which loosen the seals between gut cells, change secretion and make nerves more sensitive. In rats the leakiness lasted up to 7 days after the stress ended, and gut mitochondria were damaged but recovered. *(Qin et al., 2014; Vicario et al., 2012)*

### 6 · Ileum: short answer
**Serotonin is often called a "happy chemical". Where in the body is most of it made?**
- Accepted: gut, intestine, bowel, GI, colon…
- "Brain" or "stomach" get a "So close" message explaining the answer

*Learn more:* gut serotonin (5-HT) controls how fast things move, how much fluid is released and how strongly pain is signalled. Early-life stress increases serotonin-making cells. Some IBS medicines and low-dose antidepressants target this signalling. *(Qin et al., 2014)*

### 7 · Colon: MCQ
**What can long-term stress do to the microbiota?**
Nothing / **Shift its balance (dysbiosis) and help bacteria stick closer to the gut wall ✔** / Kill all the bacteria / Only change mouth bacteria

*Learn more:* stress changes the microbes' environment (gut movement, mucus, immune activity, hormones), and microbes signal back to the brain through the microbiota–gut–brain axis. *(Qin et al., 2014)*

### 8 · Sigmoid colon: true/false
**If stress makes IBS worse, then IBS is "all in your head".** → **False ✔**

*Learn more:* in visceral hypersensitivity, gut nerves turn their volume up. In rats this lasted up to 30 days after the stress ended. Stress also changes the sodium and potassium channels in colon sensory nerves. IBS involves an "irritable bowel and irritable brain". *(Qin et al., 2014; Vicario et al., 2012)*

### 9 · Exit: short answer (open)
**Name one thing that can help calm the stress–gut loop.**
Any genuine answer earns a point. The game matches keywords to give tailored feedback for exercise, CBT/therapy, hypnotherapy, sleep, breathing/mindfulness, diet/probiotics, and support from friends or a doctor. The model answer lists the options with research behind them.

## 4. Results screen

- Score out of 9, gut community size, and "8.9 m explored"
- **Four things to remember**
  1. Brain and gut talk both ways.
  2. Long-term stress keeps cortisol switched on, makes the lining leakier and turns up nerve sensitivity.
  3. Stress shifts the microbiota, and the microbes signal back.
  4. IBS is real, common and manageable, and calming stress is part of treating it.
- **See a doctor if:** blood in poo, unexplained weight loss, symptoms that wake you at night, fever, or a family history of bowel cancer, coeliac disease or IBD
- **Dive again** · **Copy a message for a friend** · Sources

## 5. Design decisions (for the reflective report)

- **No timer.** The reference game uses a countdown. Our audience is already stressed, so the product shouldn't add pressure.
- **Never punishing.** Wrong answers still move the player down, and every answer comes with an explanation.
- **Two layers.** The question and feedback are written for the general public. "Learn more" holds the mechanism and numbers for curious players.
- **Show a coping tool.** The breathing break models a stress-reduction technique instead of only describing one.
- **Real units.** The depth gauge uses metres along the gut, so players see how long the small intestine is.
- **Fighting stigma.** Stop 8 targets the "all in your head" myth directly.
- **Accessibility.** The body font is Atkinson Hyperlegible, which is designed for readability. Everything works with a keyboard, and the game respects reduced-motion settings. Short answers accept spelling slips.

## 6. Fact-check before final (per the assignment's AI policy)

- [ ] "About 90% of the body's serotonin is made in the gut" is widely cited but isn't in our two core readings. Add a supporting source.
- [ ] "Some bacteria can sense stress hormones directly" (colon, Learn more) comes from microbial endocrinology research. Add a source or cut it.
- [ ] GI tract lengths are approximate adult averages.
- [ ] "Stomach acid is about pH 2" and "some people clench or grind their teeth under stress" are general knowledge. Add a source for each.
- [ ] Check the "when to see a doctor" red flags against a current local guideline.
- [ ] Keep the "this was in rats" caveat on the crowding-study question.

## 7. Sources

- Qin H-Y, Cheng C-W, Tang X-D, Bian Z-X. Impact of psychological stress on irritable bowel syndrome. *World J Gastroenterol* 2014;20(39):14126–31. doi:10.3748/wjg.v20.i39.14126
- Vicario M, Alonso C, Guilarte M, et al. Chronic psychosocial stress induces reversible mitochondrial damage and corticotropin-releasing factor receptor type-1 upregulation in the rat intestine and IBS-like gut dysfunction. *Psychoneuroendocrinology* 2012;37:65–77. doi:10.1016/j.psyneuen.2011.05.005
