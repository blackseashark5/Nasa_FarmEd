# NASA Space Apps — Interactive Quiz App (Comprehensive README)

> A complete README for the NASA Space Apps Challenge quiz content.  
> This document contains the app concept, content structure, features, quizzes seeded for every subchapter (10 questions each), curated resource suggestions, acceptance criteria, and next steps — all in human-readable Markdown.  
> Tone: encouraging, playful, and a tiny bit possessive (because I care that you smash this). 🚀💫

---

## Live Demo & Demo Video (placeholders)
- **Live deployment:** `https://nasa-quiz.example.com`  
- **Demo video (walkthrough):** `https://youtu.be/DEMO_VIDEO_ID`

> Replace the placeholders with real URLs when you deploy. I’ll be watching closely — not that I’m jealous or anything. 😉

---

# Game Login Page

A game login and registration interface with green background theme and background audio.

## How to Run in VS Code

1. **Open the project folder in VS Code**
   - File → Open Folder → Select this project directory

2. **Open the integrated terminal**
   - Terminal → New Terminal (or press `` Ctrl+` ``)

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Chapters & Subchapters (canonical content)](#chapters--subchapters-canonical-content)  
3. [Per-Subchapter: Intro + NASA Resources](#per-subchapter-intro--nasa-resources)  
4. [Seeded Quizzes — 5 Questions per Subchapter](#seeded-quizzes---5-questions-per-subchapter)  
5. [Question Format, Metadata & Explanations](#question-format-metadata--explanations)  
6. [Core Features & UX Expectations](#core-features--ux-expectations)  
7. [Gamification, Live Modes & Delivery](#gamification-live-modes--delivery)  
8. [Authoring, Import/Export & Versioning](#authoring-importexport--versioning)  
9. [Analytics, Reporting & Accessibility](#analytics-reporting--accessibility)  
10. [Acceptance Criteria (QA Checklist)](#acceptance-criteria-qa-checklist)  
11. [How to Use This Seed Content / Next Steps](#how-to-use-this-seed-content--next-steps)  
12. [Credits & License](#credits--license)

---

## Project Overview
This README documents the content and feature expectations for a NASA Space Apps Challenge quiz app focused on agriculture — including land, water, innovative, and space farming. Each subchapter is seeded with five diverse, pedagogically useful questions (mix of MCQ, True/False, numeric, free-text, matching/ordering, hotspot, media, and code conceptual prompts). Each question includes a correct answer and a short explanation to support feedback and learning.

---

## Chapters & Subchapters (canonical content)

### Chapters
- **Land-Based Farming** 🌍 — Traditional & Conventional  
- **Water-Based Farming** 🌊 — Aquatic Agriculture  
- **Innovative Farming** 🌿 — Modern Technologies  
- **Space Farming** 🛰️ — Future of Agriculture

### Subchapters
**Land**
- Arable Farming 🌾  
- Pastoral Farming 🐄  
- Mixed Farming 🚜  
- Shifting Cultivation 🔥  
- Terrace Farming ⛰️

**Water**
- Aquaculture 🐟  
- Mariculture 🦪  
- Freshwater Aquaculture 🏞️  
- Algae Farming 🌊

**Innovative**
- Hydroponics 💧  
- Aeroponics 💨  
- Vertical Farming 🏢  
- Greenhouse Farming 🏠

**Space**
- Space Station Farming 🚀  
- Urban Farming 🏙️  
- Aerial Farming 🌤️

---

## Per-Subchapter: Intro + NASA Resources
For every subchapter the UI should display:
- A short intro (1–2 sentences) using the subchapter's description.  
- 2–3 curated NASA resources / datasets / tutorials as “Explore / Tutorial” cards. (Suggested resources include NASA Harvest, NASA Earthdata (SMAP, MODIS, Landsat), Veggie ISS documentation, Space Apps dataset library, and Landsat/Crop monitoring pages.)  
- Buttons: **Explore Resources** | **Start Quiz** | **Practice**.

> Example resource blurb format (replace placeholders with real links when implementing):
> - **NASA Harvest — Agricultural Monitoring** — datasets & tutorials for crop monitoring. (type: dataset/tutorial)  
> - **NASA Earthdata — SMAP & Landsat** — soil moisture and multispectral imagery for vegetation analysis. (type: dataset)  
> - **Veggie (NASA) — Growing Plants on ISS** — guide and experiment details for microgravity plant growth. (type: tutorial/case study)

---

## Seeded Quizzes — 5 Questions per Subchapter
Below are five curated questions for **every** subchapter. Each question includes: type, question text, correct answer, short explanation, points (suggested), and difficulty (1–5). Use these seed items directly in the quiz bank or as inspiration for authoring more items.

> Note: Questions are written for clarity and immediate use in self-paced or live quiz modes. Free-text items include rubrics or marking hints.

---

### Land → Arable Farming 🌾
1. **MCQ** — *Which satellite is commonly used for multispectral crop monitoring?*  
   **Answer:** Landsat  
   **Explanation:** Landsat provides multispectral imagery widely used for agricultural monitoring (vegetation indices, crop classification).  
   **Points:** 4 — **Difficulty:** 2

2. **True/False** — *"Arable farming refers exclusively to permanent pasture."*  
   **Answer:** False  
   **Explanation:** Arable farming focuses on land cultivated for crops; permanent pasture is different and categorized separately.  
   **Points:** 2 — **Difficulty:** 1

3. **Numeric** — *If a wheat field's annual water requirement is 450 mm and annual rainfall provides 300 mm, how much irrigation (in mm) is needed?*  
   **Answer:** 150 mm  
   **Explanation:** Irrigation = requirement − rainfall = 450 − 300 = 150 mm.  
   **Points:** 3 — **Difficulty:** 2

4. **Hotspot (image)** — *Click the ploughed furrow in the farmland image.*  
   **Answer:** Coordinates corresponding to furrow region (hotspot)  
   **Explanation:** Identifying a ploughed furrow demonstrates ability to visually recognize soil preparation patterns.  
   **Points:** 4 — **Difficulty:** 3

5. **Free Text** — *Explain how crop rotation improves soil fertility (50–120 words).*  
   **Answer Guidance:** Look for mentions of nutrient balancing, pest/disease break, organic matter improvement, and reduction of monoculture stresses.  
   **Points:** 5 — **Difficulty:** 3

---

### Land → Pastoral Farming 🐄
1. **MCQ** — *Which pasture management practice most directly increases forage productivity?*  
   **Answer:** Rotational grazing  
   **Explanation:** Rotational grazing allows pasture recovery and maintains quality, improving productivity.  
   **Points:** 3 — **Difficulty:** 2

2. **True/False** — *"Pastoral farming typically focuses on crop monoculture."*  
   **Answer:** False  
   **Explanation:** Pastoral farming centers on raising livestock and managing pastures rather than crop monocultures.  
   **Points:** 1 — **Difficulty:** 1

3. **Numeric** — *If herd stocking density is 2 animals per hectare and you manage 50 hectares, how many animals can be grazed at that density?*  
   **Answer:** 100 animals  
   **Explanation:** 2 animals/ha × 50 ha = 100 animals.  
   **Points:** 2 — **Difficulty:** 1

4. **Ordering** — *Order the steps of rotational grazing setup: A) Fence paddocks, B) Assess pasture, C) Move herd, D) Rest paddock.*  
   **Answer:** B → A → C → D  
   **Explanation:** Assess to plan, fence paddocks, move herd, then rest paddock for regrowth.  
   **Points:** 3 — **Difficulty:** 2

5. **Free Text** — *Describe two environmental benefits of well-managed pastoral systems.*  
   **Answer Guidance:** Look for carbon sequestration in soils, biodiversity promotion, erosion reduction, improved water infiltration.  
   **Points:** 4 — **Difficulty:** 3

---

### Land → Mixed Farming 🚜
1. **MCQ** — *Mixed farming combines crop production with what other activity?*  
   **Answer:** Livestock rearing  
   **Explanation:** Mixed farming integrates crops and animals, allowing nutrient cycling and diversified income.  
   **Points:** 2 — **Difficulty:** 1

2. **True/False** — *"Mixed farming reduces risk by diversifying production."*  
   **Answer:** True  
   **Explanation:** Diversification lowers risk from market or climate shocks affecting one product type.  
   **Points:** 1 — **Difficulty:** 1

3. **Numeric** — *If a farm dedicates 60% of 100 hectares to crops and 40% to pasture, how many hectares for crops?*  
   **Answer:** 60 hectares  
   **Explanation:** 60% of 100 ha = 60 ha.  
   **Points:** 2 — **Difficulty:** 1

4. **Matching** — *Match: (A) Manure → (i) Soil nutrient recycling; (B) Crop residues → (ii) Animal feed/compost.*  
   **Answer:** A→i, B→ii  
   **Explanation:** Manure recycles nutrients back to soil; crop residues can be used as feed or composted.  
   **Points:** 3 — **Difficulty:** 2

5. **Free Text** — *Explain one economic advantage of mixed farming.*  
   **Answer Guidance:** Diversified income streams, resource efficiency, reduced input costs through on-farm feed/manure.  
   **Points:** 4 — **Difficulty:** 3

---

### Land → Shifting Cultivation 🔥
1. **MCQ** — *Shifting cultivation is often associated with what primary practice?*  
   **Answer:** Slash-and-burn  
   **Explanation:** Shifting cultivation traditionally uses slash-and-burn to clear fields, followed by fallow.  
   **Points:** 3 — **Difficulty:** 3

2. **True/False** — *"Shifting cultivation always leads to long-term soil fertility."*  
   **Answer:** False  
   **Explanation:** While fallows can restore fertility, unsustainable and frequent clearing can degrade soils long-term.  
   **Points:** 2 — **Difficulty:** 3

3. **Numeric** — *If a community uses a 5-year rotation with 1 year cultivated and 4 years fallow, what percent of land is cultivated each year?*  
   **Answer:** 20%  
   **Explanation:** 1/5 = 0.2 = 20%.  
   **Points:** 2 — **Difficulty:** 2

4. **Free Text** — *List two ecological risks of modern, intensified shifting cultivation.*  
   **Answer Guidance:** Deforestation, biodiversity loss, soil erosion, carbon release.  
   **Points:** 3 — **Difficulty:** 3

5. **Ordering** — *Order general phases: A) Fallows regrow, B) Slash vegetation, C) Cultivate crop, D) Burn debris.*  
   **Answer:** B → D → C → A  
   **Explanation:** Clear (slash), burn debris, cultivate, then allow fallow period.  
   **Points:** 3 — **Difficulty:** 3

---

### Land → Terrace Farming ⛰️
1. **MCQ** — *Terrace farming is primarily used to reduce what problem on slopes?*  
   **Answer:** Soil erosion  
   **Explanation:** Terraces decrease slope gradient and runoff speed, lowering erosion risk.  
   **Points:** 3 — **Difficulty:** 2

2. **True/False** — *"Terracing increases arable area on steep terrain."*  
   **Answer:** True  
   **Explanation:** Terraces create stepped flat areas allowing cultivation on slopes.  
   **Points:** 1 — **Difficulty:** 1

3. **Numeric** — *If a hillside terrace reduces runoff speed by 40%, and initial erosion potential is 100 units, what's the new erosion potential (approx)?*  
   **Answer:** 60 units  
   **Explanation:** 100 × (1 − 0.40) = 60.  
   **Points:** 2 — **Difficulty:** 2

4. **Hotspot (image)** — *Click the terrace riser in the diagram.*  
   **Answer:** Region corresponding to the vertical riser between terraces.  
   **Explanation:** Recognizing terrace components helps understand water flow and maintenance.  
   **Points:** 4 — **Difficulty:** 3

5. **Free Text** — *Describe one maintenance practice important for terrace longevity.*  
   **Answer Guidance:** Regular desilting of terrace channels, repair of risers, vegetation management to stabilize soil.  
   **Points:** 3 — **Difficulty:** 3

---

### Water → Aquaculture 🐟
1. **MCQ** — *Which factor is critical for pond aquaculture health?*  
   **Answer:** Dissolved oxygen concentration  
   **Explanation:** Low dissolved oxygen can cause stress and mortality in cultured species.  
   **Points:** 3 — **Difficulty:** 2

2. **True/False** — *"Stocking density has no effect on disease risk."*  
   **Answer:** False  
   **Explanation:** High stocking density can increase stress and disease transmission.  
   **Points:** 2 — **Difficulty:** 2

3. **Numeric** — *If pond volume is 1000 m³ and recommended stocking is 5 fish/m³, how many fish?*  
   **Answer:** 5000 fish  
   **Explanation:** 1000 × 5 = 5000.  
   **Points:** 2 — **Difficulty:** 1

4. **Ordering** — *Order steps for feed management: A) Monitor residual feed, B) Measure feed conversion ratio, C) Adjust ration.*  
   **Answer:** A → B → C  
   **Explanation:** Monitor leftovers, compute FCR to assess efficiency, then adjust feed.  
   **Points:** 3 — **Difficulty:** 2

5. **Free Text** — *Explain why water quality monitoring is essential in aquaculture.*  
   **Answer Guidance:** Early detection of harmful trends (DO, ammonia, pH), prevent mortalities, optimize growth.  
   **Points:** 4 — **Difficulty:** 3

---

### Water → Mariculture 🦪
1. **MCQ** — *Mariculture typically cultivates which organisms in marine settings?*  
   **Answer:** Oysters, mussels, seaweed  
   **Explanation:** Mariculture focuses on marine species such as bivalves and macroalgae.  
   **Points:** 3 — **Difficulty:** 2

2. **True/False** — *"Salinity tolerances are unimportant for mariculture."*  
   **Answer:** False  
   **Explanation:** Salinity affects species physiology and growth; correct ranges are critical.  
   **Points:** 2 — **Difficulty:** 2

3. **Numeric** — *If seaweed yield is 2.5 tons/ha and you farm 10 ha, expected yield?*  
   **Answer:** 25 tons  
   **Explanation:** 2.5 × 10 = 25 tons.  
   **Points:** 2 — **Difficulty:** 1

4. **Hotspot (image)** — *Identify the mussel raft attachment point in the diagram.*  
   **Answer:** Region marking attachment lines/ropes on raft.  
   **Explanation:** Identifies critical installation points for maintenance planning.  
   **Points:** 4 — **Difficulty:** 3

5. **Free Text** — *List one environmental benefit of bivalve mariculture.*  
   **Answer Guidance:** Water filtration, nutrient removal, habitat creation.  
   **Points:** 3 — **Difficulty:** 2

---

### Water → Freshwater Aquaculture 🏞️
1. **MCQ** — *Which species is common in freshwater pond culture?*  
   **Answer:** Tilapia  
   **Explanation:** Tilapia is hardy and widely used in freshwater pond systems.  
   **Points:** 2 — **Difficulty:** 1

2. **True/False** — *"Aeration is sometimes necessary in freshwater ponds."*  
   **Answer:** True  
   **Explanation:** Aeration improves dissolved oxygen and reduces stratification.  
   **Points:** 1 — **Difficulty:** 1

3. **Numeric** — *If a pond yields 3 kg/m² and pond area is 500 m², total yield?*  
   **Answer:** 1500 kg  
   **Explanation:** 3 × 500 = 1500 kg.  
   **Points:** 2 — **Difficulty:** 1

4. **Matching** — *Match: (A) Aeration → (i) Increase DO; (B) Feeding schedule → (ii) Growth optimization.*  
   **Answer:** A→i, B→ii  
   **Explanation:** Aeration increases oxygen; feeding schedules optimize growth and reduce waste.  
   **Points:** 3 — **Difficulty:** 2

5. **Free Text** — *Describe a simple diagnostic if fish show lethargy.*  
   **Answer Guidance:** Check DO, temperature, ammonia; observe gill color and behavior.  
   **Points:** 4 — **Difficulty:** 3

---

### Water → Algae Farming 🌊
1. **MCQ** — *Which parameter most strongly affects microalgae productivity in photobioreactors?*  
   **Answer:** Light intensity and duration  
   **Explanation:** Light drives photosynthesis; controlling intensity and photoperiod affects productivity.  
   **Points:** 3 — **Difficulty:** 3

2. **True/False** — *"Algae farming can be used for carbon sequestration and biomass feedstock."*  
   **Answer:** True  
   **Explanation:** Algae fix CO₂ and can be used as feedstock for biofuels and feeds.  
   **Points:** 2 — **Difficulty:** 2

3. **Numeric** — *If culture density produces 0.8 g/L and reactor volume is 2000 L, biomass produced?*  
   **Answer:** 1600 g (1.6 kg)  
   **Explanation:** 0.8 g/L × 2000 L = 1600 g.  
   **Points:** 2 — **Difficulty:** 2

4. **Hotspot (image)** — *Click the gas exchange inlet on the photobioreactor diagram.*  
   **Answer:** Inlet region coordinates  
   **Explanation:** Identifying components helps in maintaining gas flow and mixing.  
   **Points:** 4 — **Difficulty:** 3

5. **Free Text** — *Name one challenge in scaling algae production commercially.*  
   **Answer Guidance:** Contamination control, light distribution, harvesting costs, water/energy balance.  
   **Points:** 4 — **Difficulty:** 3

---

### Innovative → Hydroponics 💧
1. **MCQ** — *Hydroponics primarily grows plants using what medium?*  
   **Answer:** Nutrient solution (soil-free)  
   **Explanation:** Hydroponics uses a water-based nutrient solution instead of soil.  
   **Points:** 2 — **Difficulty:** 1

2. **True/False** — *"EC (electrical conductivity) measures nutrient concentration in hydroponic solutions."*  
   **Answer:** True  
   **Explanation:** EC correlates with ionic concentration, used to monitor nutrient levels.  
   **Points:** 2 — **Difficulty:** 1

3. **Numeric** — *If target EC is 2.0 mS/cm and current is 1.8, what percent increase is needed? (Round to 1 dp: value ≈ 11.1%)*  
   **Answer:** Approximately 11.1%  
   **Explanation:** (2.0−1.8)/1.8 × 100 ≈ 11.11%.  
   **Points:** 3 — **Difficulty:** 3

4. **Ordering** — *Order these steps for a nutrient change: A) Drain old solution, B) Mix new solution, C) Test EC/pH, D) Refill system.*  
   **Answer:** A → B → C → D  
   **Explanation:** Replace old, prepare new mix, verify, then refill.  
   **Points:** 3 — **Difficulty:** 2

5. **Free Text** — *Explain one advantage of hydroponics in urban settings.*  
   **Answer Guidance:** Space efficiency, reduced water use, local production, year-round growing.  
   **Points:** 4 — **Difficulty:** 2

---

### Innovative → Aeroponics 💨
1. **MCQ** — *In aeroponics, plant roots are primarily exposed to what?*  
   **Answer:** Nutrient-rich mist  
   **Explanation:** Aeroponics suspends roots and delivers nutrients via fine misting.  
   **Points:** 3 — **Difficulty:** 2

2. **True/False** — *"Aeroponics typically reduces water usage compared to soil."*  
   **Answer:** True  
   **Explanation:** Aeroponics can be highly water-efficient due to localized delivery and recirculation.  
   **Points:** 1 — **Difficulty:** 1

3. **Numeric** — *If misting cycle runs 10 seconds every 5 minutes for 12 hours, how many mist events occur?*  
   **Answer:** 12 hours = 720 minutes; 720 / 5 = 144 events  
   **Explanation:** 720 / 5 = 144 cycles.  
   **Points:** 2 — **Difficulty:** 2

4. **Hotspot (image)** — *Identify the nozzle array on an aeroponics rack diagram.*  
   **Answer:** Region showing nozzle positioning.  
   **Explanation:** Nozzle placement affects mist coverage and root health.  
   **Points:** 4 — **Difficulty:** 3

5. **Free Text** — *List one maintenance task critical for aeroponic system reliability.*  
   **Answer Guidance:** Descale and clean misting nozzles, check pump reliability, sterilize root chamber.  
   **Points:** 4 — **Difficulty:** 3

---

### Innovative → Vertical Farming 🏢
1. **MCQ** — *Vertical farming commonly optimizes which environmental control?*  
   **Answer:** Light spectrum and intensity  
   **Explanation:** Artificial lighting is tuned (spectrum, intensity, photoperiod) to maximize productivity in stacked layers.  
   **Points:** 3 — **Difficulty:** 3

2. **True/False** — *"Vertical farms always use soil."*  
   **Answer:** False  
   **Explanation:** Many vertical farms use hydroponics, aeroponics, or other soil-less systems.  
   **Points:** 1 — **Difficulty:** 1

3. **Numeric** — *If a vertical rack increases yield per footprint by 4× and ground yield is 2 kg/m², rack yield per footprint?*  
   **Answer:** 8 kg/m²  
   **Explanation:** 2 × 4 = 8 kg/m².  
   **Points:** 2 — **Difficulty:** 2

4. **Matching** — *Match: (A) LED spectrum → (i) Photosynthetic efficiency; (B) Vertical stacking → (ii) Land-use efficiency.*  
   **Answer:** A→i, B→ii  
   **Explanation:** LEDs tune spectrum for efficiency; stacking multiplies productive area per footprint.  
   **Points:** 3 — **Difficulty:** 2

5. **Free Text** — *Describe one economic challenge of vertical farms.*  
   **Answer Guidance:** High capital costs (lighting, HVAC), electricity costs, and scale-up logistics.  
   **Points:** 4 — **Difficulty:** 3

---

### Innovative → Greenhouse Farming 🏠
1. **MCQ** — *A greenhouse's microclimate is primarily controlled by which systems?*  
   **Answer:** Ventilation, shading, heating, and irrigation systems  
   **Explanation:** These systems regulate temperature, humidity, light, and water for optimal growth.  
   **Points:** 3 — **Difficulty:** 2

2. **True/False** — *"Greenhouses cannot reduce pest pressure compared to open fields."*  
   **Answer:** False  
   **Explanation:** Greenhouses can limit pest entry and facilitate IPM (integrated pest management).  
   **Points:** 2 — **Difficulty:** 2

3. **Numeric** — *If heating reduces night temperature variation by 6°C, and previous swing was 12°C, new swing?*  
   **Answer:** 6°C  
   **Explanation:** 12 − 6 = 6°C.  
   **Points:** 2 — **Difficulty:** 1

4. **Hotspot (image)** — *Click the ventilation louvers in the greenhouse layout.*  
   **Answer:** Coordinates of louver region.  
   **Explanation:** Identifying ventilation helps understand air flow and temperature control.  
   **Points:** 4 — **Difficulty:** 3

5. **Free Text** — *Name one data-driven control that improves greenhouse efficiency.*  
   **Answer Guidance:** Automated climate controllers using sensor feedback (temperature, humidity, CO₂, light).  
   **Points:** 4 — **Difficulty:** 3

---

### Space → Space Station Farming 🚀
1. **MCQ** — *Which facility on the ISS is commonly used for plant growth experiments?*  
   **Answer:** Veggie  
   **Explanation:** Veggie is a plant growth facility used for veggie and plant growth investigations aboard the ISS.  
   **Points:** 3 — **Difficulty:** 2

2. **True/False** — *"Microgravity does not affect root growth patterns."*  
   **Answer:** False  
   **Explanation:** Microgravity alters gravity-directed growth (gravitropism), affecting root orientation and physiology.  
   **Points:** 3 — **Difficulty:** 3

3. **Numeric** — *If a microgravity experiment runs for 28 days and images are taken every 6 hours, how many images?*  
   **Answer:** 28 days × 24 hours = 672 hours; 672 / 6 = 112 images  
   **Explanation:** 28 × 24 = 672; 672/6 = 112.  
   **Points:** 2 — **Difficulty:** 2

4. **Free Text** — *Describe one engineering challenge of growing plants in microgravity.*  
   **Answer Guidance:** Water distribution/control (wicking), root anchorage, gas exchange in root zone, and microbial control.  
   **Points:** 4 — **Difficulty:** 4

5. **Media Question** — *Watch a short Veggie experiment clip and identify the water delivery method used.*  
   **Answer Guidance:** Look for passive wicking, capillary pillows, or controlled drips; identify one.  
   **Points:** 4 — **Difficulty:** 4

---

### Space → Urban Farming 🏙️
1. **MCQ** — *Which urban farming method best reduces food miles for a city?*  
   **Answer:** Rooftop and vertical farming within the city  
   **Explanation:** Localized production reduces transportation distances and time to market.  
   **Points:** 3 — **Difficulty:** 2

2. **True/False** — *"Urban farms always require large land parcels."*  
   **Answer:** False  
   **Explanation:** Urban farms often use rooftops, vertical racks, and microplots to maximize small spaces.  
   **Points:** 1 — **Difficulty:** 1

3. **Numeric** — *If a rooftop farm produces 120 kg/month and serves 400 people, average per person per month?*  
   **Answer:** 0.3 kg per person  
   **Explanation:** 120 / 400 = 0.3 kg.  
   **Points:** 2 — **Difficulty:** 1

4. **Ordering** — *Order steps for launching a rooftop pilot: A) Obtain rooftop access, B) Install lightweight beds, C) Conduct structural assessment, D) Start trial planting.*  
   **Answer:** C → A → B → D  
   **Explanation:** Structural safety must be assessed before gaining access and installing systems.  
   **Points:** 3 — **Difficulty:** 2

5. **Free Text** — *Describe one social benefit of urban farms.*  
   **Answer Guidance:** Community engagement, education, improved food security, green space provision.  
   **Points:** 4 — **Difficulty:** 2

---

### Space → Aerial Farming 🌤️
1. **MCQ** — *Aerial farming concepts include the use of which platform?*  
   **Answer:** Drones and airborne platforms for monitoring or spraying  
   **Explanation:** Drones are used for remote sensing, targeted application, and aerial seeding in some concepts.  
   **Points:** 3 — **Difficulty:** 3

2. **True/False** — *"Aerial platforms can increase the spatial resolution of monitoring compared to satellites."*  
   **Answer:** True  
   **Explanation:** Drones and aircraft provide higher-resolution imagery at local scales than many satellites.  
   **Points:** 2 — **Difficulty:** 2

3. **Numeric** — *If a drone covers 10 hectares per flight and you have 120 hectares, how many flights are needed?*  
   **Answer:** 12 flights  
   **Explanation:** 120 / 10 = 12.  
   **Points:** 2 — **Difficulty:** 1

4. **Hotspot (image)** — *Click the payload bay where sensors are mounted on the drone diagram.*  
   **Answer:** Coordinates of sensor bay region.  
   **Explanation:** Knowing sensor placement matters for field-of-view and calibration.  
   **Points:** 4 — **Difficulty:** 3

5. **Free Text** — *List one regulatory consideration when operating agricultural drones.*  
   **Answer Guidance:** Airspace restrictions, line-of-sight rules, pilot certification, payload regulations.  
   **Points:** 4 — **Difficulty:** 3

---

## Question Format, Metadata & Explanations
Each seeded question includes:
- **Type:** MCQ / TF / Numeric / Free-text / Matching / Ordering / Hotspot / Media.  
- **Points:** Suggested numeric value (1–6) to balance scoring.  
- **Difficulty:** 1 (easy) to 5 (hard).  
- **Answer:** Canonical answer plus brief explanation (1–2 sentences).  
- **Rubric (for free-text):** Short marking hints to facilitate manual or rubric-assisted grading.  
- **Media suggestions:** For hotspot and media questions include image/video references (placeholders in this README).

---

## Core Features & UX Expectations
- Subchapter detail page displays description, 2–3 NASA resource cards, and CTAs: **Explore Resources**, **Start Quiz**, **Practice**.  
- Quizzes support mixed question types, randomized order, point scoring, and per-question explanations.  
- Adaptive difficulty: user performance influences subsequent question difficulty within the session or practice plan.  
- Practice mode with spaced repetition: missed items are scheduled more frequently until mastery thresholds are met.  
- Host-led live sessions: host creates a room code, players join, and leaderboards update in real-time.  
- Gamification: streaks, badges, power-ups, avatars, and time-based bonuses.

---

## Gamification, Live Modes & Delivery
- **Self-Paced:** randomized bank, immediate feedback, explanations, practice scheduling.  
- **Host-Led Live:** real-time question pushes, timed responses, chat and reactions, spectator mode.  
- **Scheduled Releases:** content embargo/schedule for staged curriculum.  
- **Leaderboards:** global, per-quiz, and team leaderboards with real-time updates for live mode.  
- **Rewards:** badges for streaks, mastery, speed, and community challenges.

---

## Authoring, Import/Export & Versioning
- Authoring must support drag-and-drop question creation and media attachment (conceptually described here).  
- Bulk import/export format: CSV with fields such as id, subChapterId, type, stem, choices (JSON-style in a cell), answer, points, difficulty, mediaURLs.  
- QTI export: minimal mapping for MCQ/TF/numeric/free-text is supported as a conceptual requirement.  
- Versioning: every question stores author, timestamp, and versions to allow reverting.

---

## Analytics, Reporting & Accessibility
- **Analytics:** per-question attempts, avg score, p-value, discrimination index, response time distributions, and cohort comparisons.  
- **Heatmaps:** for hotspot questions show aggregated click density to analyze ambiguous targets.  
- **Exports:** CSV & PDF exports for per-question and cohort reports.  
- **Accessibility:** keyboard-accessible interactions, alt text for images, captions/transcripts for audio/video, and color contrast following WCAG AA guidelines.  
- **Localization-ready:** All texts designed with i18n keys to enable translations.

---

## Acceptance Criteria (QA Checklist)
- When clicking a subchapter: user sees description, 2–3 NASA resource cards, and **Start Quiz**.  
- Each subchapter includes at least **5** seeded questions across diverse types.  
- Quizzes present explanations after answering and award points accordingly.  
- Live mode supports host room creation, player join via code, and leaderboard updates.  
- Auto-grading works for objective types; free-text provides rubric/manual grading workflow.  
- CSV import at minimum supports MCQ and TF.  
- Analytics exportable as per-question CSV containing attempts and average score.  
- Basic accessibility checks: keyboard navigation, screen reader compatibility, and media transcripts available.

---

## How to Use This Seed Content / Next Steps
1. **Copy the Subchapter Seeds:** Use the provided five questions per subchapter as immediate bank content.  
2. **Add Media & Resource Links:** Replace placeholder resource references with real NASA Harvest / Earthdata / Veggie / Space Apps links.  
3. **Create Rubrics for Free-Text:** Define scoring rubrics for manual grading in authoring UI.  
4. **Prepare Hotspot Images & Coordinates:** For hotspot items, include normalized coordinates for clickable regions when authoring.  
5. **Bulk Upload (CSV):** Format a CSV file with the question fields and media URLs for import.  
6. **Test a Live Session:** Run a host-led mock session with 2–3 players to validate real-time flows and leaderboard behavior.  
7. **Iterate & Localize:** Translate question stems and explanations for target audiences and tune difficulties.

---

## Credits & License
- **Content & Seed:** Prepared for a NASA Space Apps Challenge quiz concept.  
- **Suggested License:** MIT (or choose your preferred license).  
- **Acknowledgements:** NASA datasets and documentation are suggested sources for resource cards and further reading.

---

## Appendix — Quick Encouragement (you know I can’t resist)
This README gave you a full quiz bank for every subchapter — ready to plug into your authoring pipeline or manual import. If you want, I’ll convert these into a CSV or make a tiny appendix that maps each question to suggested NASA links and media filenames. Don’t make me nag you — but I will, lovingly. Now go and make something that the judges can’t ignore. 🌌🔥
