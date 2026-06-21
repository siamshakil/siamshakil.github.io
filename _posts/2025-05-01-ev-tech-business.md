---
title: "EV Technology & Business: A Field Guide"
tags: [EV, "Tech BizDev", Reference]
excerpt: "Charging, batteries, motors, and markets - the technical and commercial fundamentals of electric mobility, with a Bangladesh lens. An interactive reference built from interview-prep notes."
---

A working reference for the technology and the business of electric mobility - charging, batteries,
motors, and markets - with a Bangladesh focus throughout. Use the tabs to move between domains.

<div class="evk">
<div class="evk-head">
  <span class="evk-eyebrow">// Interactive Reference</span>
  <h2 class="evk-title">EV Tech &amp; Business</h2>
  <p class="evk-sub">Charging · Batteries · Motors · Markets · Bangladesh focus</p>
</div>

<div class="evk-tabs">
  <button class="evk-tab active" data-tab="charging">Charging</button>
  <button class="evk-tab" data-tab="battery">Battery</button>
  <button class="evk-tab" data-tab="motors">Motors</button>
  <button class="evk-tab" data-tab="markets">Markets (BD)</button>
  <button class="evk-tab" data-tab="numbers">Quick Numbers</button>
</div>

<!-- CHARGING -->
<section class="evk-panel active" id="evk-charging">
  <h3 class="evk-h3">Charging levels at a glance</h3>
  <div class="evk-cards">
    <div class="evk-card a"><span class="evk-lbl">Level 1 (AC)</span><span class="evk-val">1.4-2.4 kW</span><span class="evk-cs">120V socket · 8-20 hr full charge</span></div>
    <div class="evk-card b"><span class="evk-lbl">Level 2 (AC)</span><span class="evk-val">3.7-22 kW</span><span class="evk-cs">240V EVSE · 3-8 hr · home &amp; work</span></div>
    <div class="evk-card c"><span class="evk-lbl">DC Fast (L3)</span><span class="evk-val">50-350 kW</span><span class="evk-cs">CCS / CHAdeMO · 20-80% in 20-40 min</span></div>
    <div class="evk-card d"><span class="evk-lbl">Ultra-Fast (HPC)</span><span class="evk-val">350 kW-1 MW</span><span class="evk-cs">800V architecture · 5-15 min top-up</span></div>
  </div>

  <h3 class="evk-h3">Connector standards</h3>
  <div class="evk-scroll"><table class="evk-table">
    <tr><th>Standard</th><th>Type</th><th>Max power</th><th>Regions</th><th>Status</th></tr>
    <tr><td><b>CCS2</b></td><td>AC+DC combo</td><td>350 kW</td><td>Europe, India, BD</td><td><span class="evk-bdg g">Global standard</span></td></tr>
    <tr><td><b>CCS1</b></td><td>AC+DC combo</td><td>350 kW</td><td>North America</td><td><span class="evk-bdg g">Dominant NA</span></td></tr>
    <tr><td><b>NACS (J3400)</b></td><td>AC+DC</td><td>350 kW</td><td>USA, expanding</td><td><span class="evk-bdg b">Rising</span></td></tr>
    <tr><td><b>CHAdeMO</b></td><td>DC only</td><td>400 kW</td><td>Japan</td><td><span class="evk-bdg r">Declining</span></td></tr>
    <tr><td><b>GB/T</b></td><td>AC+DC</td><td>250 kW</td><td>China</td><td><span class="evk-bdg p">China dominant</span></td></tr>
    <tr><td><b>Type 2 (Mennekes)</b></td><td>AC (DC in CCS2)</td><td>43 kW AC</td><td>Europe, BD</td><td><span class="evk-bdg g">EU AC standard</span></td></tr>
  </table></div>
  <div class="evk-callout">🇧🇩 <b>Bangladesh / South Asia:</b> CCS2 + Type 2 is the regulatory direction, following the EU and India. Most imported EVs (Hyundai Ioniq, BYD Atto) use CCS2; Chinese three-wheelers use GB/T or proprietary connectors.</div>

  <h3 class="evk-h3">AC vs DC charging</h3>
  <div class="evk-scroll"><table class="evk-table">
    <tr><th>Parameter</th><th>AC slow (L1/L2)</th><th>DC fast (50-150 kW)</th><th>DC ultra-fast (&gt;150 kW)</th></tr>
    <tr><td>Converter location</td><td>In vehicle (OBC)</td><td>In charger (off-board)</td><td>In charger (off-board)</td></tr>
    <tr><td>Infrastructure cost</td><td>$500-3,000</td><td>$25,000-60,000</td><td>$80,000-250,000+</td></tr>
    <tr><td>Battery stress</td><td>Low</td><td>Medium-High</td><td>High (thermal-critical)</td></tr>
    <tr><td>Use case</td><td>Overnight home / fleet</td><td>Destination, depot</td><td>Highway, transit hub</td></tr>
    <tr><td>ROI timeline</td><td>2-3 years</td><td>4-6 years</td><td>6-10 years</td></tr>
  </table></div>

  <h3 class="evk-h3">Charging business models</h3>
  <div class="evk-bm"><span class="evk-bm-t">CPO - Own &amp; operate</span><span class="evk-bm-b">Own the chargers, sell energy at a markup (2-3× grid rate). Most capital-intensive; needs grid connection, permits, land. <i>Tesla Supercharger, Ionity.</i></span></div>
  <div class="evk-bm"><span class="evk-bm-t">EVSE manufacturer / distributor</span><span class="evk-bm-b">Sell hardware to CPOs, fleets, property owners. Higher margin with add-on services (warranty, OCPP licensing, CMS). <i>ABB, Webasto, Star Charge.</i></span></div>
  <div class="evk-bm"><span class="evk-bm-t">Charging-as-a-Service (CaaS)</span><span class="evk-bm-b">Provider funds and owns the hardware; host gets free install plus a revenue share. Removes host CAPEX barrier - very BD-relevant for malls, hotels, petrol pumps.</span></div>
  <div class="evk-bm"><span class="evk-bm-t">Fleet energy management (B2B SaaS)</span><span class="evk-bm-b">Sell CSMS / fleet software - load balancing, scheduling, billing. High-margin recurring revenue. <i>ChargePoint, Monta, Virta.</i></span></div>
  <div class="evk-bm"><span class="evk-bm-t">Battery swap network</span><span class="evk-bm-b">Monthly subscription per vehicle ($5-20 for 2-wheelers in BD). Station CAPEX ~$15-50k. Key barrier: standardising packs across OEMs. <i>Oyika (BD), Gogoro, NIO.</i></span></div>

  <div class="evk-callout amber">⚡ <b>BD grid challenge:</b> Load shedding and ±10% voltage swings demand chargers with wide voltage tolerance (85-265V) and buffer integration - a real technical selling point, not a footnote.</div>
</section>

<!-- BATTERY -->
<section class="evk-panel" id="evk-battery">
  <h3 class="evk-h3">Battery chemistry comparison</h3>
  <div class="evk-scroll"><table class="evk-table">
    <tr><th>Chemistry</th><th>Energy density</th><th>Cycle life</th><th>Cost $/kWh</th><th>Safety</th><th>Best use</th></tr>
    <tr><td><b>LFP</b> (LiFePO₄)</td><td>120-160 Wh/kg</td><td>3,000-6,000+</td><td>$80-100</td><td><span class="evk-bdg g">Excellent</span></td><td>Fleet, buses, BD market</td></tr>
    <tr><td><b>NMC 811</b></td><td>200-280 Wh/kg</td><td>1,500-2,000</td><td>$110-140</td><td><span class="evk-bdg a">Moderate</span></td><td>Passenger cars (range)</td></tr>
    <tr><td><b>NCA</b></td><td>220-300 Wh/kg</td><td>1,000-1,500</td><td>$120-150</td><td><span class="evk-bdg r">Low</span></td><td>Tesla premium</td></tr>
    <tr><td><b>LMFP</b></td><td>160-200 Wh/kg</td><td>3,000-5,000</td><td>$90-110</td><td><span class="evk-bdg g">Good</span></td><td>Next-gen affordable</td></tr>
    <tr><td><b>Solid-state</b></td><td>300-500 Wh/kg*</td><td>5,000+*</td><td>$200-400+</td><td><span class="evk-bdg g">Excellent</span></td><td>2027-2030 commercial</td></tr>
    <tr><td><b>Lead-acid</b></td><td>30-50 Wh/kg</td><td>300-500</td><td>$50-80</td><td><span class="evk-bdg a">Moderate</span></td><td>Low-speed BD 3-wheelers</td></tr>
  </table></div>
  <div class="evk-callout green">🔑 <b>Key insight for BD:</b> LFP dominates affordable EVs, e-buses, and three-wheelers - no cobalt, stable in heat (28-35°C average), long calendar life. BYD Blade and CATL LFP cells lead imports.</div>

  <h3 class="evk-h3">Cell formats &amp; pack terms</h3>
  <div class="evk-pills">
    <span class="evk-pill">Cylindrical (Tesla 2170/4680)</span>
    <span class="evk-pill">Prismatic (CATL, BYD)</span>
    <span class="evk-pill">Pouch (LG, SK On)</span>
    <span class="evk-pill">Blade / LFP (BYD)</span>
    <span class="evk-pill">CTP - Cell-to-Pack</span>
    <span class="evk-pill">CTC - Cell-to-Chassis</span>
    <span class="evk-pill">SOC / SOH / DOD</span>
    <span class="evk-pill">BMS</span>
    <span class="evk-pill">C-rate</span>
  </div>

  <h3 class="evk-h3">Battery OEM pricing (2024-25)</h3>
  <div class="evk-scroll"><table class="evk-table">
    <tr><th>OEM</th><th>Country</th><th>Chemistry</th><th>$/kWh</th><th>BD availability</th></tr>
    <tr><td><b>CATL</b></td><td>China</td><td>LFP, NMC, LMFP</td><td>$75-95</td><td>Via Chinese EVs</td></tr>
    <tr><td><b>BYD</b></td><td>China</td><td>LFP Blade</td><td>$70-90</td><td>Direct (BYD imports)</td></tr>
    <tr><td><b>LG Energy Solution</b></td><td>Korea</td><td>NCM, NCA</td><td>$95-120</td><td>In imported EVs</td></tr>
    <tr><td><b>Samsung SDI</b></td><td>Korea</td><td>NMC prismatic</td><td>$100-130</td><td>Indirect</td></tr>
    <tr><td><b>Panasonic</b></td><td>Japan</td><td>NCA, NMC</td><td>$100-130</td><td>Indirect</td></tr>
    <tr><td><b>Exide / Amara Raja</b></td><td>India</td><td>Lead-acid, LFP</td><td>$55-80</td><td>Low-speed BD EVs</td></tr>
  </table></div>

  <h3 class="evk-h3">Limitations</h3>
  <div class="evk-two">
    <div class="evk-box"><h4>🔬 Technical</h4><p>Thermal runaway in NMC/NCA needs active cooling (critical in BD heat). Fast-charge above 1C accelerates degradation. LFP self-discharge 2-3%/month. Below 80% SOH = EV retirement; repurpose for stationary storage.</p></div>
    <div class="evk-box"><h4>💼 Business &amp; political</h4><p>Cobalt is 70% DRC-sourced (ESG risk). Lithium price swung $80k → $12k/ton (2022-24). CATL + BYD = over half of global cells; US/EU tariffs rising. BD battery import duty 25-37%. Almost no formal Li-ion recycling in BD.</p></div>
  </div>
</section>

<!-- MOTORS -->
<section class="evk-panel" id="evk-motors">
  <h3 class="evk-h3">Motor type comparison</h3>
  <div class="evk-scroll"><table class="evk-table">
    <tr><th>Type</th><th>Efficiency</th><th>Power density</th><th>Cost</th><th>Best for</th></tr>
    <tr><td><b>PMSM</b> (perm. magnet sync)</td><td>93-97%</td><td>Very high</td><td>Medium-High</td><td>Passenger cars (Tesla, BYD)</td></tr>
    <tr><td><b>BLDC</b> (brushless DC)</td><td>85-95%</td><td>High</td><td>Medium</td><td>2/3-wheelers, BD e-rickshaws</td></tr>
    <tr><td><b>Induction (AC IM)</b></td><td>88-95%</td><td>Medium</td><td>Low</td><td>Tesla S/X front, commercial</td></tr>
    <tr><td><b>SRM</b> (switched reluctance)</td><td>88-95%</td><td>Medium</td><td>Low</td><td>Experimental, no rare earth</td></tr>
    <tr><td><b>Axial flux</b></td><td>95-98%</td><td>Extremely high</td><td>Very high</td><td>High-performance, aircraft</td></tr>
  </table></div>

  <h3 class="evk-h3">Key parameters</h3>
  <div class="evk-cards">
    <div class="evk-card a"><span class="evk-lbl">Peak power</span><span class="evk-val">50-800 kW</span><span class="evk-cs">2-wheeler 1-10 · 3-wheeler 5-15 · car 100-500</span></div>
    <div class="evk-card c"><span class="evk-lbl">Peak torque</span><span class="evk-val">100-1,000 Nm</span><span class="evk-cs">Instant torque = EV's core advantage</span></div>
    <div class="evk-card b"><span class="evk-lbl">Voltage</span><span class="evk-val">48-800V</span><span class="evk-cs">BD 3-wheelers 48-72V · cars 400/800V</span></div>
    <div class="evk-card d"><span class="evk-lbl">Efficiency peak</span><span class="evk-val">93-97%</span><span class="evk-cs">vs ICE 25-35%</span></div>
  </div>

  <h3 class="evk-h3">PMSM vs BLDC vs Induction</h3>
  <div class="evk-scroll"><table class="evk-table">
    <tr><th>Parameter</th><th>PMSM</th><th>BLDC</th><th>AC Induction</th></tr>
    <tr><td>Rotor</td><td>Buried magnets (NdFeB)</td><td>Surface magnets</td><td>Squirrel cage</td></tr>
    <tr><td>Rare-earth dependency</td><td><span class="evk-bdg r">High (Nd, Dy)</span></td><td><span class="evk-bdg a">Moderate</span></td><td><span class="evk-bdg g">None</span></td></tr>
    <tr><td>Part-load efficiency</td><td>Excellent</td><td>Good</td><td>Drops off</td></tr>
    <tr><td>Cost premium</td><td>+30-50% vs induction</td><td>Moderate</td><td>Baseline</td></tr>
    <tr><td>BD 3-wheeler use</td><td>Less common (cost)</td><td><span class="evk-bdg g">Dominant</span></td><td>Some imported buses</td></tr>
  </table></div>
  <div class="evk-callout amber">⚠️ <b>Rare-earth risk:</b> PMSM needs Neodymium and Dysprosium; China controls ~85% of rare-earth processing. Magnet-free motors (SRM, WRSM, induction) are gaining interest - a real sourcing-strategy talking point.</div>
</section>

<!-- MARKETS -->
<section class="evk-panel" id="evk-markets">
  <h3 class="evk-h3">Bangladesh snapshot (2024-25)</h3>
  <div class="evk-cards">
    <div class="evk-card c"><span class="evk-lbl">E-rickshaws</span><span class="evk-val">~1.5M</span><span class="evk-cs">Mostly unregistered; largest EV segment</span></div>
    <div class="evk-card a"><span class="evk-lbl">Registered 4-wheel EVs</span><span class="evk-val">~2-5k</span><span class="evk-cs">Up from near-zero pre-2022</span></div>
    <div class="evk-card b"><span class="evk-lbl">EV duty</span><span class="evk-val">0-25%</span><span class="evk-cs">Cut from 200%+ effective (2023 budget)</span></div>
    <div class="evk-card d"><span class="evk-lbl">Govt target</span><span class="evk-val">30%</span><span class="evk-cs">EV share of new registrations by 2030</span></div>
  </div>

  <h3 class="evk-h3">What's working vs failing</h3>
  <div class="evk-scroll"><table class="evk-table">
    <tr><th>Segment</th><th>Status</th><th>Why</th></tr>
    <tr><td>E-rickshaws / nasimans</td><td><span class="evk-bdg g">Working</span></td><td>Low cost ($1.5-3k), instant fuel savings, informal financing, simple tech</td></tr>
    <tr><td>Battery swap (Oyika)</td><td><span class="evk-bdg g">Growing</span></td><td>Solves charging gap; subscription removes battery cost barrier</td></tr>
    <tr><td>Premium passenger EV</td><td><span class="evk-bdg a">Early</span></td><td>High duty, thin charging, upper-middle class only</td></tr>
    <tr><td>E-bus (BRTC)</td><td><span class="evk-bdg a">Pilot</span></td><td>Grid instability + depot charging cost; donor-funded, slow</td></tr>
    <tr><td>Public charging network</td><td><span class="evk-bdg r">Nascent</span></td><td>Few chargers, low utilisation, no interoperability, slow permits</td></tr>
    <tr><td>EV freight / last-mile</td><td><span class="evk-bdg b">Opportunity</span></td><td>Pathao/Shohoz exploring; TCO compelling, charging is the bottleneck</td></tr>
  </table></div>

  <h3 class="evk-h3">Comparable markets - lessons</h3>
  <div class="evk-box"><h4>🇮🇳 India - closest comparable</h4><p>FAME II subsidy, Ola Electric (&gt;1M scooters/yr), Tata EV cars, 15,000+ public chargers. Failing: sparse highway DCFC, subsidy dependency. <b>Lesson:</b> start with fleet/commercial, not personal; swap works for 2/3-wheelers; policy consistency is critical.</p></div>
  <div class="evk-box"><h4>🇻🇳 Vietnam - fast mover</h4><p>VinFast with govt backing, aggressive e-scooter adoption, EV mandate for public transport by 2030. Failing: proprietary "walled-garden" charging. <b>Lesson:</b> a domestic champion can catalyse a market; interoperable standards prevent lock-in.</p></div>
  <div class="evk-box"><h4>🇵🇰 Pakistan - very similar to BD</h4><p>E-rickshaws (&gt;200k), NEVP 2025, Chinese partnerships. Failing: FX crisis killed imports, outages, informal-pack fires. <b>Lesson:</b> FX management is critical; local CKD assembly cuts import exposure.</p></div>
</section>

<!-- NUMBERS -->
<section class="evk-panel" id="evk-numbers">
  <h3 class="evk-h3">Numbers to know</h3>
  <div class="evk-nums">
    <div class="evk-num"><span class="evk-n">$75-95</span><span class="evk-d">$/kWh LFP cell (2024)</span></div>
    <div class="evk-num"><span class="evk-n">$40k</span><span class="evk-d">DC 60 kW charger, installed</span></div>
    <div class="evk-num"><span class="evk-n">&gt;15%</span><span class="evk-d">Utilisation for CPO viability</span></div>
    <div class="evk-num"><span class="evk-n">98%+</span><span class="evk-d">Uptime SLA, commercial EVCS</span></div>
    <div class="evk-num"><span class="evk-n">OCPP 2.0.1</span><span class="evk-d">Current charger protocol</span></div>
    <div class="evk-num"><span class="evk-n">$0.09-0.11</span><span class="evk-d">BD electricity $/kWh (commercial)</span></div>
    <div class="evk-num"><span class="evk-n">3,000-6,000</span><span class="evk-d">LFP cycle life</span></div>
    <div class="evk-num"><span class="evk-n">80%</span><span class="evk-d">SOH = EV battery retirement</span></div>
    <div class="evk-num"><span class="evk-n">85%</span><span class="evk-d">China share of rare-earth processing</span></div>
  </div>

  <h3 class="evk-h3">Terminology</h3>
  <div class="evk-scroll"><table class="evk-table">
    <tr><th>Term</th><th>Meaning</th><th>Why it matters</th></tr>
    <tr><td><b>OCPP</b></td><td>Open Charge Point Protocol (charger ↔ CSMS)</td><td>Interoperability; specify the version in RFPs</td></tr>
    <tr><td><b>OCPI</b></td><td>CPO-to-CPO roaming protocol</td><td>Cross-network charging, like carrier roaming</td></tr>
    <tr><td><b>ISO 15118</b></td><td>V2G / Plug &amp; Charge standard</td><td>Next-gen differentiator in proposals</td></tr>
    <tr><td><b>CPO / eMSP</b></td><td>Charge Point Operator / e-Mobility Service Provider</td><td>Infrastructure owner vs customer-facing layer</td></tr>
    <tr><td><b>C-rate</b></td><td>Charge/discharge rate vs capacity</td><td>Battery stress: 0.1-0.5C overnight, 2-5C DCFC</td></tr>
    <tr><td><b>TCO</b></td><td>Total Cost of Ownership</td><td>The primary sales argument for fleet EV shift</td></tr>
    <tr><td><b>EVSE</b></td><td>Electric Vehicle Supply Equipment</td><td>The proper term for the "charger" hardware</td></tr>
    <tr><td><b>CKD / SKD</b></td><td>Completely / Semi Knocked Down kits</td><td>BD local-assembly duty-benefit strategy</td></tr>
  </table></div>

  <h3 class="evk-h3">TCO example - e-rickshaw vs CNG auto (BDT)</h3>
  <div class="evk-scroll"><table class="evk-table">
    <tr><th>Cost item</th><th>CNG auto</th><th>E-rickshaw</th></tr>
    <tr><td>Vehicle cost</td><td>3-4 lakh</td><td>1.5-2.5 lakh</td></tr>
    <tr><td>Daily energy</td><td>400-600/day (CNG)</td><td>80-120/day (grid)</td></tr>
    <tr><td>Battery replacement (3 yr)</td><td>N/A</td><td>30-50k</td></tr>
    <tr><td>Maintenance / year</td><td>20-40k</td><td>5-10k</td></tr>
    <tr><td><b>3-year TCO</b></td><td><b>~7-9 lakh</b></td><td><b>~4-5 lakh</b></td></tr>
  </table></div>
  <div class="evk-callout green">💡 <b>The pitch:</b> In Bangladesh the EV value proposition is strongest in commercial fleet - rickshaws, buses, last-mile - where TCO saving is 30-50% over three years. The bottleneck is charging reliability and battery financing, not technology readiness.</div>
</section>
</div>

<style>
.evk { width: min(1100px, 94vw); margin-left: 50%; transform: translateX(-50%); margin-top: 2.5rem; font-family: var(--font-body); text-align: left; }
.evk-head { border: 1px solid var(--border-hi); border-bottom: none; padding: 1.5rem 1.5rem 1.25rem; background: var(--bg-card); }
.evk-eyebrow { font-family: var(--font-mono); font-size: var(--sz-xs); letter-spacing: 0.15em; text-transform: uppercase; color: var(--accent); display: block; margin-bottom: 0.5rem; }
.evk-title { font-family: var(--font-display); font-size: var(--sz-2xl); font-weight: 700; letter-spacing: -0.02em; color: var(--fg); margin: 0; }
.evk-sub { font-family: var(--font-mono); font-size: var(--sz-xs); color: var(--fg-muted); letter-spacing: 0.04em; margin-top: 0.4rem; }
.evk-tabs { display: flex; flex-wrap: wrap; gap: 0; border: 1px solid var(--border-hi); background: var(--bg); position: sticky; top: 52px; z-index: 20; }
.evk-tab { flex: 1; min-width: 110px; padding: 0.75rem 0.5rem; font-family: var(--font-mono); font-size: var(--sz-xs); letter-spacing: 0.08em; text-transform: uppercase; color: var(--fg-muted); background: transparent; border: none; border-right: 1px solid var(--border); cursor: pointer; transition: background 80ms, color 80ms; }
.evk-tab:last-child { border-right: none; }
.evk-tab:hover { color: var(--fg); background: var(--bg-card); }
.evk-tab.active { color: var(--bg); background: var(--accent); }
.evk-panel { display: none; border: 1px solid var(--border-hi); border-top: none; padding: 1.75rem 1.5rem 2rem; }
.evk-panel.active { display: block; }
.evk-h3 { font-family: var(--font-mono); font-size: var(--sz-xs); letter-spacing: 0.12em; text-transform: uppercase; color: var(--accent); margin: 1.75rem 0 1rem; padding-bottom: 0.4rem; border-bottom: 1px solid var(--rule); }
.evk-panel > .evk-h3:first-child { margin-top: 0; }
.evk-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 1px; background: var(--border); border: 1px solid var(--border); margin-bottom: 1rem; }
.evk-card { background: var(--bg-card); padding: 1rem; border-left: 2px solid var(--fg-dim); }
.evk-card.a { border-left-color: var(--accent); }
.evk-card.b { border-left-color: #C99A4A; }
.evk-card.c { border-left-color: #3FB37F; }
.evk-card.d { border-left-color: #8B7CF6; }
.evk-lbl { font-family: var(--font-mono); font-size: 0.6rem; letter-spacing: 0.1em; text-transform: uppercase; color: var(--fg-dim); display: block; margin-bottom: 0.3rem; }
.evk-val { font-family: var(--font-display); font-size: var(--sz-lg); font-weight: 600; color: var(--fg); display: block; letter-spacing: -0.01em; }
.evk-cs { font-size: 0.72rem; color: var(--fg-muted); display: block; margin-top: 0.3rem; line-height: 1.4; }
.evk-scroll { overflow-x: auto; margin-bottom: 1rem; border: 1px solid var(--border); }
.evk-table { width: 100%; border-collapse: collapse; font-size: 0.8rem; min-width: 520px; }
.evk-table th { background: var(--bg-surface); text-align: left; padding: 0.6rem 0.75rem; font-family: var(--font-mono); font-size: 0.65rem; letter-spacing: 0.06em; text-transform: uppercase; color: var(--fg-muted); border-bottom: 1px solid var(--border-hi); white-space: nowrap; }
.evk-table td { padding: 0.55rem 0.75rem; border-bottom: 1px solid var(--border); color: var(--fg-muted); vertical-align: top; }
.evk-table tr:last-child td { border-bottom: none; }
.evk-table tr:hover td { background: var(--bg-card); }
.evk-table td b { color: var(--fg); font-weight: 600; }
.evk-bdg { display: inline-block; padding: 0.1rem 0.45rem; font-family: var(--font-mono); font-size: 0.6rem; letter-spacing: 0.04em; text-transform: uppercase; border: 1px solid; border-radius: 0; white-space: nowrap; }
.evk-bdg.g { color: #4FCF8F; border-color: rgba(63,179,127,0.4); background: rgba(63,179,127,0.1); }
.evk-bdg.r { color: #E08070; border-color: rgba(197,96,79,0.4); background: rgba(197,96,79,0.12); }
.evk-bdg.a { color: #D7AE5E; border-color: rgba(201,154,74,0.4); background: rgba(201,154,74,0.1); }
.evk-bdg.b { color: #6FB7D6; border-color: rgba(74,158,191,0.4); background: rgba(74,158,191,0.1); }
.evk-bdg.p { color: #A799F0; border-color: rgba(139,124,246,0.4); background: rgba(139,124,246,0.1); }
.evk-callout { border-left: 2px solid var(--accent); background: rgba(74,158,191,0.07); padding: 0.85rem 1rem; font-size: 0.8rem; color: var(--fg-muted); margin: 1rem 0; line-height: 1.6; }
.evk-callout b { color: var(--fg); }
.evk-callout.amber { border-left-color: #C99A4A; background: rgba(201,154,74,0.07); }
.evk-callout.green { border-left-color: #3FB37F; background: rgba(63,179,127,0.07); }
.evk-bm { border: 1px solid var(--border); border-left: 2px solid var(--accent); background: var(--bg-card); padding: 0.85rem 1rem; margin-bottom: 0.6rem; }
.evk-bm-t { display: block; font-family: var(--font-display); font-size: var(--sz-sm); font-weight: 600; color: var(--fg); margin-bottom: 0.3rem; }
.evk-bm-b { display: block; font-size: 0.78rem; color: var(--fg-muted); line-height: 1.6; }
.evk-bm-b i { color: var(--fg-dim); font-style: italic; }
.evk-pills { display: flex; flex-wrap: wrap; gap: 0.4rem; margin-bottom: 1rem; }
.evk-pill { font-family: var(--font-mono); font-size: 0.68rem; padding: 0.25rem 0.6rem; border: 1px solid var(--border-hi); color: var(--fg-muted); }
.evk-two { display: grid; grid-template-columns: 1fr 1fr; gap: 0.75rem; margin-bottom: 1rem; }
.evk-box { border: 1px solid var(--border); background: var(--bg-card); padding: 1rem 1.1rem; margin-bottom: 0.75rem; }
.evk-box h4 { font-family: var(--font-display); font-size: var(--sz-sm); font-weight: 600; color: var(--fg); margin-bottom: 0.4rem; }
.evk-box p { font-size: 0.78rem; color: var(--fg-muted); line-height: 1.6; margin: 0; }
.evk-box p b { color: var(--fg); }
.evk-nums { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 1px; background: var(--border); border: 1px solid var(--border); margin-bottom: 1rem; }
.evk-num { background: var(--bg-card); padding: 0.85rem 1rem; }
.evk-n { font-family: var(--font-display); font-size: var(--sz-md); font-weight: 700; color: var(--accent); display: block; }
.evk-d { font-size: 0.7rem; color: var(--fg-muted); display: block; margin-top: 0.25rem; line-height: 1.4; }
@media (max-width: 640px) {
  .evk-two { grid-template-columns: 1fr; }
  .evk-tabs { top: 0; }
  .evk-title { font-size: var(--sz-xl); }
}
</style>

<script>
(function() {
  var root = document.querySelector('.evk');
  if (!root) return;
  root.querySelectorAll('.evk-tab').forEach(function(btn) {
    btn.addEventListener('click', function() {
      root.querySelectorAll('.evk-tab').forEach(function(b){ b.classList.remove('active'); });
      root.querySelectorAll('.evk-panel').forEach(function(p){ p.classList.remove('active'); });
      btn.classList.add('active');
      var panel = root.querySelector('#evk-' + btn.dataset.tab);
      if (panel) panel.classList.add('active');
    });
  });
})();
</script>
