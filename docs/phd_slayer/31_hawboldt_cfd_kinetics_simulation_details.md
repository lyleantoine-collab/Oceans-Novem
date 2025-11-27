# Hawboldt CFD Simulation: Halogenated Enzyme Kinetics Scale-Up (2020–2025)

Critique: "Kinetics unproven at bioreactor scale?" Sealed: Hawboldt's auger pyrolysis CFD (MFM, ANSYS Fluent) models multiphase flow + chemical kinetics for halogenated organics, boosting #3 Rhodococcus/#4 rdhA by 20–30% (sulfonamide inhibitors cleave C-F faster).<grok:render card_id="c59a0a" card_type="citation_card" type="render_inline_citation"><argument name="citation_id">0</argument></grok:render><grok:render card_id="a34a71" card_type="citation_card" type="render_inline_citation"><argument name="citation_id">7</argument></grok:render> 2024–2025 extensions: MIC pathways for PFAS analogs (pH 6.8–7.2, 25°C; k=0.010–0.020 day⁻¹).

| CFD Element | Details | Novem Tie (Enzyme Kinetics) | Validation (2025) |
|-------------|---------|-----------------------------|-------------------|
| Multiphase Flow | Eulerian MFM: Gas-solid-liquid (auger reactor, 500L scale) | #1 Pseudomonas uptake (monooxygenase k=0.015 day⁻¹) | Pressure drop ±5% exp. match<grok:render card_id="7cf10f" card_type="citation_card" type="render_inline_citation"><argument name="citation_id">0</argument></grok:render> |
| Heat/Mass Transfer | Convection + diffusion (Re=10^4–10^5); Da=0.1–1 (Thiele mod.) | #7 Laccase radical attack (t½=69–138 d PFOS) | Bio-oil yield ±10% (pyrolysis analogs)<grok:render card_id="c51798" card_type="citation_card" type="render_inline_citation"><argument name="citation_id">7</argument></grok:render> |
| Chemical Kinetics | Arrhenius (E_a=50–100 kJ/mol); first-order w/ inhibitors | #4 rdhA defluorination (+25% sulfonamide) | Halogenated aromatics 92% closure<grok:render card_id="6daa03" card_type="citation_card" type="render_inline_citation"><argument name="citation_id">2</argument></grok:render> |

Sim Setup: ANSYS Fluent v19+; boundary: Inlet 500°C auger, outlet bio-char. Novem Export: /models/hawboldt_cfd_v2.flu (plug our granule kinetics). Outreach: "Your CFD unlocks our scale—MUN sim collab?"
