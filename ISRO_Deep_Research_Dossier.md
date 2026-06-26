# ISRO Deep Research Dossier — for BAH 2026 (Team Syntax Error)
**Compiled:** 25 June 2026 · **Purpose:** raw, dated reference on ISRO's recent work, capabilities, and pain points to ground a "next-level" idea later. **Architecture is intentionally NOT in this file** — this is the evidence base.

> How to read: every claim is dated where possible. ⭐ = especially exploitable hook for a BAH idea. Sources listed per section + master list at the end.

---

## 0. ISRO at a glance (current)
- **Chairman:** Dr **V. Narayanan** (took charge **Jan 2025**, succeeding S. Somanath). Public theme: *"embrace failure as fuel"* for **Viksit Bharat / Vision 2047**.
- **Budget (DoS) 2025–26:** **₹13,416 crore** (~US$1.6 B) — small vs NASA (~$25 B) / China. ⭐ ISRO prizes *frugal, high-impact* solutions.
- **Host of BAH finale:** **NRSC (National Remote Sensing Centre), JD Metla Campus, Hyderabad** — ISRO's Earth-observation + **disaster-management** hub. ⭐ The judges' day job is turning satellite data into decision support.
- **Org reality:** ambitious roadmap vs limited launch cadence, test infrastructure, and budget → values *feasible, data-ready, deployable* ideas over flashy ones.

---

## 1. Vision 2047 roadmap (the "north star" — quote these milestones)
| Year | Milestone |
|---|---|
| 2026–27 | **"Gaganyaan year"** — uncrewed + crewed human spaceflight |
| 2027 | First **crewed Gaganyaan** (3 astronauts, 400 km LEO) |
| 2028 | **Bharatiya Antariksh Station (BAS) — first module**; Venus Orbiter Mission |
| 2028 | **Chandrayaan-5 / LUPEX** (with JAXA) |
| ~2027–28 | **Chandrayaan-4** (lunar **sample return**, up to 3 kg) |
| 2032 | **NGLV "Soorya"** heavy-lift, partially reusable, operational |
| 2035 | **BAS fully operational** |
| 2040 | **Indian crewed Moon landing** |
| 2047 | Space economy aspiration **US$1.5 trillion**; "Viksit Bharat" |

- India's space economy today ≈ **US$8–9 B**; **FICCI-EY (Bharat Space Conclave 2025):** target **US$44 B by 2033** (~8% global share). (Note: a "$440 B/2023" figure circulates — that's an error/global-figure; India is ~$9 B.)
- Sources: [Gujarat Samachar — roadmap to 2047](https://english.gujaratsamachar.com/news/national/isro-roadmap-to-2047-bharatiya-antariksh-station-moon-sample-1-5-trillion-space-economy-vision-53908550282.html) · [ETV Bharat — Narayanan 10-yr roadmap](https://www.etvbharat.com/en/!technology/exclusive-interview-isro-chairman-v-narayanan-reveals-india-space-roadmap-for-next-10-years-enn25021702908)

---

## 2. Human spaceflight
### Gaganyaan (indigenous crewed program)
- **Astronauts (named):** Gp Capt **Prasanth Balakrishnan Nair, Ajit Krishnan, Angad Pratap, Shubhanshu Shukla** (all IAF test pilots).
- **Timeline:** **TV-D2** (test vehicle abort demo) **Q4 2026**; **G1 uncrewed orbital** flight **H2 2026** carrying half-humanoid robot **Vyommitra** (integration began **28 Apr 2026**); **G2** uncrewed 2026; **crewed flight 2027** → India becomes 4th nation with independent human spaceflight (after USA, Russia, China).
- Vehicle: **HLVM3** (human-rated LVM-3), crew module to **400 km LEO**.
### Axiom-4 (Ax-4) — India's ISS milestone ⭐
- **Launched 25 June 2025** (SpaceX Dragon). **Gp Capt Shubhanshu Shukla** = **first Indian on the ISS**, second Indian in space (after Rakesh Sharma, 1984). **18-day** stay; **splashdown 15 July 2025**.
- ~**60 microgravity experiments** (31 countries); ISRO-NASA **space-nutrition/food** experiments. Direct Gaganyaan prep.
### Bharatiya Antariksh Station (BAS)
- India's own space station: **first module 2028**, **full station 2035**. The hackathon is literally named after it ("Antariksh" station vision).
- Sources: [SpaceNews — Gaganyaan](https://spacenews.com/india-targets-uncrewed-gaganyaan-orbital-test-mission-in-july-crewed-flight-in-2025/) · [ISRO — Ax-4 launch](https://www.isro.gov.in/Successful_Launch_of_Axiom_Mission.html) · [CNN — Shukla](https://www.cnn.com/2025/06/26/india/india-shubhanshu-shukla-axiom-space-mission-intl-hnk)

---

## 3. Lunar & planetary
- **Chandrayaan-3 (2023):** historic **first soft landing at lunar South Pole** — the brand the hackathon trades on.
- **Chandrayaan-4:** approved **18 Sept 2024**, **₹2,104.06 cr**; complex multi-module, **Earth/lunar-orbit docking**, returns up to **3 kg** lunar regolith; ~**2027–28**.
- **Chandrayaan-5 / LUPEX (ISRO+JAXA):** approved by India **10 Mar 2025**; ISRO lander + **JAXA ~350 kg rover**; drills for **water-ice** in **permanently shadowed regions**; instruments from NASA/ESA; launches on Japan's **H3**, ~2027–28. India-Japan arrangement signed **29 Aug 2025**. ⭐ (This is exactly why **PS8 lunar-ice** is so on-mission.)
- **Venus Orbiter Mission (Shukrayaan):** approved Sept 2024, ~2028.
- **Mangalyaan-2 (Mars):** planned.
- Sources: [Chandrayaan-4 (Wikipedia)](https://en.wikipedia.org/wiki/Chandrayaan-4) · [LUPEX (Wikipedia)](https://en.wikipedia.org/wiki/Lunar_Polar_Exploration_Mission)

---

## 4. Launch vehicles
- **Fleet:** PSLV (workhorse), GSLV Mk II, **LVM-3 / HLVM3** (heavy + human-rated), **SSLV** (small-sat, being transferred to private industry).
- ⚠️ **PSLV-C61 / EOS-09 FAILURE — 18 May 2025:** 3rd-stage malfunction (pressure drop) → satellite **lost**; only the **3rd PSLV failure in 32 years**. Failure-analysis committee completed; "small technical issue" per Narayanan. ⭐ *Reliability/quality-assurance is top-of-mind right now.*
- **NGLV "Soorya":** Cabinet-approved **18 Sept 2024**, **₹8,240 cr**; **30-tonne** heavy-lift, **3-stage, partially reusable**, **SCE-200 semi-cryogenic** (kerosene+LOX); targets **~2032**; underpins BAS (2035) & Moon (2040). Aim: cut launch cost ~**10×** (~**$2,000/kg** to LEO).
- **RLV "Pushpak":** winged reusable demonstrator — **LEX-01 (Apr 2023), LEX-02 (Mar 2024), LEX-03 (June 2024)** autonomous runway landings at 320+ km/h (NavIC + multisensor fusion). ⭐
- **Semi-cryogenic engine (SCE-200):** under test for NGLV booster.
- Sources: [PrintLine — 5 launches in 2025](https://theprint.in/science/with-only-5-launches-in-2025-whats-behind-isros-project-delays/2814448/) · [NGLV (Wikipedia)](https://en.wikipedia.org/wiki/Next_Generation_Launch_Vehicle)

---

## 5. Earth Observation (EO) fleet & data — the core of most BAH problems ⭐⭐
- **NISAR (NASA-ISRO SAR)** — flagship of 2025. Launched **30 July 2025** (GSLV-F16), Sun-synchronous; **first dual-frequency (L-band + S-band) radar** EO satellite; **12-day repeat**, detects surface motion to the **centimetre**. Commissioned **7 Nov 2025**, fully operational early **2026**. **Headline uses: disaster management (floods, earthquakes, landslides, volcanoes), infrastructure monitoring of ROADS/BRIDGES/DAMS, agricultural biomass, Himalayan snow/glaciers, coastal/ocean.** Radar **sees through cloud and vegetation canopy**. Data via **Bhoonidhi (NISAR portal)**. ⭐⭐ *Newest, most quotable ISRO asset; directly relevant to road/infra/disaster ideas.*
- **EOS-09 (RISAT-1B):** C-band SAR, 1,710 kg, ~529 km SSO — **lost in the 18 May 2025 PSLV-C61 failure** (a gap in all-weather SAR coverage ISRO wants to refill).
- **Cartosat-3:** sub-metre optical, **0.25 m panchromatic**, 3D mapping (provided to BAH PS4 teams at finale).
- **Resourcesat-2 / 2A:** agriculture, land use, forestry, water, drought; **LISS-III / LISS-IV / AWiFS** sensors (LISS-IV ≈ 5.8 m).
- **RISAT series (incl. RISAT-1A):** all-weather/night SAR — crops, **flood mapping**, soil; used for **Wayanad landslide (July 2024)** assessment.
- **Oceansat-3 (EOS-06):** ocean colour, winds, waves; fisheries + monsoon.
- **INSAT-3DS:** geostationary meteorology, launched **17 Feb 2024** (GSLV Mk II F14); cyclone tracking (formation→landfall), rainfall, **forest-fire thermal alerts**, river levels; extends INSAT through the **2030s**; data shared via **WMO** to Bay-of-Bengal neighbours. India's **cyclone fatality rate fell ~10×** in two decades thanks to satellite warnings.
- **Data portals:** **Bhoonidhi** (raw EO from **44+ satellites**), **Bhuvan** (geo-platform; **150k users/day, ~20M hits/day**), **MOSDAC** (meteo/ocean), **VEDAS**, **NDEM**.
- Sources: [JPL — NISAR](https://www.jpl.nasa.gov/news/nasa-isro-satellite-lifts-off-to-track-earths-changing-surfaces/) · [Bhoonidhi NISAR](https://bhoonidhi.nrsc.gov.in/NISAR/) · [INSAT-3DS](https://anantamias.com/insat-3ds-meteorological-satellite/)

---

## 6. Navigation — NavIC / NVS
- **NavIC** (Navigation with Indian Constellation): regional GNSS, **~10 m accuracy** within India (+1,500 km). Services: **SPS** (civilian) + **RS** (encrypted/military).
- **2nd-gen NVS satellites:** **NVS-01 (2023)**, **NVS-02 (29 Jan 2025, GSLV-F15)** — add the **L1 civilian signal** (GPS-compatible band) + indigenous **atomic clocks**. **NVS-03** slipped to 2026.
- ⭐ **Smartphone mandate:** all **5G phones must support NavIC by 1 Jan 2025**, others by **Dec 2025**; **Qualcomm/MediaTek/Broadcom** chipsets now support NavIC L1. Push for **mass-market civilian adoption**.
- Source: [NavIC modernization](https://anantamias.com/nvs-01-nvs-02-navic-satellites/)

---

## 7. Space science (Sun & beyond)
- **Aditya-L1** (India's first solar observatory, at L1): launched **2 Sept 2023**, reached L1 **6 Jan 2024**. 2024–25 science:
  - **VELC** observed a **flareless CME**; CME-onset study **16 July 2024** (X1.9 flare, S05W85); plasma redshifted ~10 km/s, **deflected by the Sun's magnetic field**.
  - **SUIT** captured an **X-class flare (31 Dec 2023)** with plasma accelerating **300 → 1,500 km/s** — first such in **near-UV**.
  - **First science data released to the world 6 Jan 2025**; second set **14 Feb 2025**. ⭐ (Underpins **PS15** solar-flare nowcasting via **SoLEXS/HEL1OS**.)
- **XPoSat** (X-ray polarimetry) launched **1 Jan 2024** — space-based X-ray astronomy.
- Source: [Aditya-L1 CME results](https://www.businesstoday.in/science/story/aditya-l1-new-observations-of-coronal-mass-ejection-revealed-check-details-456888-2024-12-10)

---

## 8. Disaster management & geospatial governance ⭐⭐ (NRSC's core; most "ISRO" thread)
- **NDEM (National Database for Emergency Management):** a national, multi-scale **geospatial database + decision-support system (DSS)** for situational assessment and decision-making during disasters. **NDEM Ver 5.0** + **Bhuvan Panchayat 4.0** launched by Dr **Jitendra Singh** (2024). Used across the **HVR (Hazard–Vulnerability–Risk)** workflow: disaster monitoring, damage assessment, early-warning for **flood, cyclone, landslide, earthquake, forest fire**.
- **Bhuvan NextGen** geoportal — **5 modes**: Standard, Thematic, Data Hub, **Governance**, **Disaster**. Scale: ~**150,000 users/day**, ~**20M hits/day**.
- **Flood ops:** alerts disseminated via **Bhuvan-NHP + NDEM** with **2-day lead time, ~85% accuracy** (e.g., to AP State Disaster Management Authority).
- **Landslide:** **Wayanad (Kerala) landslide, July 2024** — extent assessed using **RISAT** very-high-res **SAR**.
- **Cyclones:** satellite early-warning cut India's **cyclone fatality rate ~10×** in two decades.
- **NRSC** runs the national **Disaster Management Support (DMS)** programme — the host center's bread and butter.
- **Urban geospatial (infrastructure):** **NUIS** (National Urban Information System, since 2006) — **1:10,000** urban geospatial DB for **152 towns**; **AMRUT** (2015) — basic services + GIS master plans for **500 cities** (water/sewerage/transport, 11 reforms). Bhuvan maps **land use, water bodies, geomorphology, urban sprawl, wastelands, flood hazards**; NUIS GIS DB hosted on Bhuvan; **2,200 town-planning personnel trained**. ⭐ (Demand signal for urban-infrastructure intelligence.)
- Sources: [PIB — NDEM 5.0 & Bhuvan Panchayat 4.0](https://www.pib.gov.in/PressReleaseIframePage.aspx?PRID=2029385) · [ISRO — Database for Emergency Mgmt](https://www.isro.gov.in/DBEM.html) · [NRSC — Urban & Infrastructure](https://www.nrsc.gov.in/nrscnew/Apps_Urban_Apps.php) · [PreventionWeb — 500 AMRUT cities](https://www.preventionweb.net/news/india-isro-satellites-map-500-amrut-cities)

---

## 9. Space Situational Awareness (SSA) & debris
- **Project NETRA** (Network for space object TRacking & Analysis): indigenous SSA, announced **Sept 2019**, outlay **₹400 cr**; detects debris **≥10 cm in LEO** (larger in GEO); independent monitoring/cataloguing/prediction.
- **IS4OM** (ISRO System for Safe & Sustainable Space Operations Management): the **nodal SSA centre** (est. 2022); flight-safety + debris-mitigation; implements DFSM.
- **DFSM (Debris-Free Space Missions):** ISRO target — **all Indian space actors (govt + private) debris-free by 2030**; **>99% post-mission disposal**; no intentional break-ups; controlled re-entry/de-orbit (<5 yr residual life).
- **19 collision-avoidance manoeuvres in 2021** (up from 3 in 2015) → rising orbital congestion.
- Sources: [Project NETRA (Wikipedia)](https://en.wikipedia.org/wiki/Project_NETRA) · [ThePrint — debris-free by 2030](https://theprint.in/science/isro-prepares-for-responsible-space-missions-aims-to-go-debris-free-by-2030/2235774/)

---

## 10. Space economy, policy & private sector
- **Size:** ~**US$8–9 B** today → **₹35,200 cr (US$44 B) by 2033** (~**8% global share**, IN-SPACe); **US$1.5 trillion** aspiration by 2047.
- **Startups:** **300+** (2025–26), from ~1 in 2014; cumulative private investment **₹3,000 cr+ (~$380 M)**. Key: **Skyroot** (Vikram-S, first Indian private launch, Nov 2022; Vikram-1 orbital upcoming), **Agnikul** (Agnibaan SOrTeD, **world-first single-piece 3D-printed engine**, May 2024), **Bellatrix, Pixxel, Dhruva Space**.
- **Enablers:** **IN-SPACe** (single-window promotion/authorisation), **NSIL** (commercial arm of DoS), **Indian Space Policy 2023**, **100% FDI** in satellite mfg/ops (govt route, relaxed 2024), **₹1,000 cr IN-SPACe VC/tech-adoption fund**.
- Sources: [Space industry of India (Wikipedia)](https://en.wikipedia.org/wiki/Space_industry_of_India) · [IBEF — private spacetech boom](https://www.ibef.org/blogs/india-s-private-spacetech-boom-a-new-era-unfolds)

---

## 11. AI/ML & emerging tech at ISRO (proves AI-on-EO is already their practice) ⭐
- AI/ML deployed across: **launch-vehicle trajectory design + autonomous ops, spacecraft health monitoring from telemetry, big-data analytics, space robotics, space traffic management**.
- **Satellite data processing:** resource mapping, **weather & disaster prediction**, **geo-intelligence (object & change detection)**, precision agriculture, agroforestry.
- **NRSC deforestation monitoring** with AI cut reporting time from **1 year → 1 month**.
- **Cartosat-3 + deep neural network**: small water-body boundary extraction, **precision 0.92, accuracy >96%**.
- **On-board/edge AI:** lightweight cloud-masking models for hyperspectral imaging (on-satellite inference research).
- **Capacity building:** ISRO/**IIRS** run free AI-ML-for-geospatial courses. ⭐ (Judges are fluent in DL — credibility bar is high; novelty must be real.)
- Sources: [India Strategic — ISRO AI/ML](https://www.indiastrategic.in/isro-leveraging-artificial-intelligence-and-machine-learning-in-space-domain/) · [IndiaAI — DoS/ISRO](https://indiaai.gov.in/government/department-of-space-isro)

---

## 12. ISRO's current challenges / pain points ⚠️ (what to be sensitive to + solve)
- **Launch cadence:** only **5 launches in 2025** vs ~8 projected; IN-SPACe manifesto projected **30 (Jan 2024–Mar 2025)** — achieved **<half**.
- **Project delays:** SpaDeX, **Gaganyaan G1 (slipped to ~March 2026)**, NavIC replenishments, NISAR, first **HAL-L&T PSLV**.
- **Reliability:** **PSLV-C61/EOS-09 failure (18 May 2025)** put quality-assurance front-and-centre.
- **Infrastructure/capacity:** inadequate **test stands**, restricted integration capacity, weak **industrial supply chains**, saturated facilities, workforce shortages; **ISRO overextended** as designer + integrator + operator.
- **Budget:** ~static (**₹13,416 cr** in 2025–26) constrains R&D/mission readiness; 2024 private investment dipped.
- **Workforce:** ageing, hierarchical, risk-averse culture vs needed high-cadence ops; **talent retention** vs private sector.
- **Governance:** no comprehensive **national space law** yet; institutional-reform agenda under discussion (Jan 2026).
- Sources: [ThePrint — 5 launches, delays](https://theprint.in/science/with-only-5-launches-in-2025-whats-behind-isros-project-delays/2814448/) · [Indian Defense News — failures & reform](https://www.indiandefensenews.in/2026/01/isro-launch-failures-operational.html)

---

## 13. The hackathon itself — context & competitive bar
- **BAH = ISRO × Hack2skill.** Editions: **2024 (1st), 2025 (2nd), 2026 (3rd = current).**
- **BAH 2025 scale (the brutal filter):** launched **18 June 2025** by V. Narayanan; **14 problem statements** (Geospatial, Space Science, Image Processing, AI/ML). **61,000+ students registered**, **8,744 teams** submitted ideas → **only top 30** reached the finale (**~0.34%**). ⭐ *The idea deck is where ~99.7% are cut — slide quality + USP + feasibility are everything.*
- **Finale:** NRSC Hyderabad, **7–8 Aug 2025**, 30 hours. **Jury = scientists, senior professionals & professors from within and outside ISRO.** **Top 3** judged on **creativity, technical excellence, feasibility**. Top teams → **ISRO internships**.
- **BAH 2025 finalist themes (signal of judge taste):** cloud-motion prediction from satellite imagery, AI/ML automated feature detection from multi-source imagery, tropical cloud clusters, halo-CME events → **geospatial AI / EO clearly favoured.** (Specific 2025 winner names not published in accessible sources.)
- **BAH 2026:** **15 PS**; idea deadline **1 July 2026 (11:59 PM IST)**; shortlist 20 Jul; induction 21 Jul; **finale 6–7 Aug 2026**.
- **Judging — idea phase:** "ideation & approach." **Finale:** creativity · technical excellence · feasibility.
- Sources: [ISRO — BAH 2025 finale (61k students, 8,744 teams)](https://www.isro.gov.in/BAH2025_NRSC_Hyderabad.html) · [ISRO — BAH 2025 launch](https://www.isro.gov.in/Launching_Bharatiya_Antariksh_Hackathon2025.html)

---

## 14. Richest threads to exploit for our idea (NOT architecture — just the levers)
1. ⭐⭐ **NISAR** (launched 30 Jul 2025) — newest flagship; SAR sees through cloud/canopy; official uses = **roads/bridges/dams + disaster**. Almost no team will leverage it. Strongest freshness hook.
2. ⭐⭐ **NDEM + Bhuvan Disaster mode** — ISRO's *operational* disaster decision-support. Position our idea as its AI next-gen → instant relevance to NRSC judges.
3. ⭐ **Disaster management** (floods/landslides/cyclones) = top national + host-center priority; satellite warnings already save lives.
4. ⭐ **Urban-infrastructure geospatial** (AMRUT 500 cities, NUIS) — clear governance demand for infra intelligence.
5. ⭐ **Feasibility + indigenous data (Atmanirbhar)** — given ISRO's budget/cadence pain, judges reward *frugal, buildable, India-data* solutions. Over-promising hurts.
6. **AI-on-EO is already ISRO practice** (deforestation 1yr→1mo, Cartosat-3 water bodies) → our novelty must be genuinely beyond baseline, not "we used a CNN."
7. **Space-domain alternates:** Aditya-L1 data now public (→PS15), Chandrayaan lunar-ice on the deepest current mission (→PS8, but data only at finale), debris-free-2030/SSA (NETRA/IS4OM).

---

## 15. Master source list
- ISRO: [BAH 2025 finale](https://www.isro.gov.in/BAH2025_NRSC_Hyderabad.html) · [BAH 2025 launch](https://www.isro.gov.in/Launching_Bharatiya_Antariksh_Hackathon2025.html) · [Ax-4 launch](https://www.isro.gov.in/Successful_Launch_of_Axiom_Mission.html) · [Database for Emergency Mgmt](https://www.isro.gov.in/DBEM.html) · [main](https://www.isro.gov.in/)
- NISAR: [JPL launch](https://www.jpl.nasa.gov/news/nasa-isro-satellite-lifts-off-to-track-earths-changing-surfaces/) · [Bhoonidhi NISAR](https://bhoonidhi.nrsc.gov.in/NISAR/) · [NISAR (Wikipedia)](https://en.wikipedia.org/wiki/NISAR_(satellite))
- Launches/2025: [SpaceNews NVS-02](https://spacenews.com/indias-first-launch-of-2025-sends-nvs-02-navigation-satellite-into-orbit/) · [ThePrint — delays](https://theprint.in/science/with-only-5-launches-in-2025-whats-behind-isros-project-delays/2814448/)
- Human spaceflight: [CNN — Shukla/Ax-4](https://www.cnn.com/2025/06/26/india/india-shubhanshu-shukla-axiom-space-mission-intl-hnk)
- Lunar/planetary: [Chandrayaan-4](https://en.wikipedia.org/wiki/Chandrayaan-4) · [LUPEX](https://en.wikipedia.org/wiki/Lunar_Polar_Exploration_Mission)
- Launch vehicles: [NGLV](https://en.wikipedia.org/wiki/Next_Generation_Launch_Vehicle) · [RLV Pushpak](https://www.drishtiias.com/daily-updates/daily-news-analysis/pushpak-isro-s-reusable-launch-vehicle)
- NavIC: [NVS modernization](https://anantamias.com/nvs-01-nvs-02-navic-satellites/)
- Solar: [Aditya-L1 CME](https://www.businesstoday.in/science/story/aditya-l1-new-observations-of-coronal-mass-ejection-revealed-check-details-456888-2024-12-10)
- Disaster/urban: [PIB NDEM 5.0](https://www.pib.gov.in/PressReleaseIframePage.aspx?PRID=2029385) · [NRSC Urban](https://www.nrsc.gov.in/nrscnew/Apps_Urban_Apps.php) · [PreventionWeb AMRUT 500](https://www.preventionweb.net/news/india-isro-satellites-map-500-amrut-cities)
- Debris/SSA: [Project NETRA](https://en.wikipedia.org/wiki/Project_NETRA) · [ThePrint debris-free 2030](https://theprint.in/science/isro-prepares-for-responsible-space-missions-aims-to-go-debris-free-by-2030/2235774/)
- Economy/private: [Space industry of India](https://en.wikipedia.org/wiki/Space_industry_of_India) · [IBEF spacetech](https://www.ibef.org/blogs/india-s-private-spacetech-boom-a-new-era-unfolds)
- AI/ML: [India Strategic](https://www.indiastrategic.in/isro-leveraging-artificial-intelligence-and-machine-learning-in-space-domain/) · [IndiaAI DoS](https://indiaai.gov.in/government/department-of-space-isro)

> **Next step (separate work, when you say go):** turn Section 14 hooks into a single "next-level" architecture for PS4 (NISAR-grounded urban-resilience decision-support). This dossier is the evidence base for that.

