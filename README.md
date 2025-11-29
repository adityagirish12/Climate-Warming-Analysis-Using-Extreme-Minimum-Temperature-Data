# Climate Warming Analysis Using Extreme Minimum Temperature Data (1941–2025)

A summarized explanation of how each step of the climate-warming analysis was done, which formulas were used (only mentioned by name), and what results were obtained.  
Source: Climate Warming Report PDF :contentReference[oaicite:1]{index=1}

## Descriptive Statistics Summary
**How it was done:**  
- Basic summary statistics were recomputed using the *sample mean* and *sample standard deviation* formulas.  
- USDA Plant Hardiness Zones were verified by converting Fahrenheit to Celsius using the *temperature conversion formula*.

**Result:**  
- **Period B** (1970–1990) had the coldest average: about **–2.14°F**, fitting **Zone 6b**.  
- **Period C** (1991–2020) had the warmest average: **4.12°F**, fitting **Zone 7a**.  
- **Period A** (full history) was between them, showing a gradual warming trend.  
(Verified on pages 2–5 of the report) :contentReference[oaicite:2]{index=2}

---

## Inferential Hypothesis Testing Summary
**How it was done:**  
- Each comparison was tested statistically using the *Welch two-sample t-test*.  
- The *Welch–Satterthwaite degrees-of-freedom formula* and *p-value from t-distribution* were used.  
- Three comparisons were tested: C vs B, C vs A, and B vs A.  
(Shown on pages 6–8) :contentReference[oaicite:3]{index=3}

**Results:**  
- **Period C vs Period B:** Highly significant warming (**difference = 6.26°F**, p ≈ 0.0012).  
- **Period C vs Period A:** Significant warming (**difference = 3.02°F**, p ≈ 0.035).  
- **Period B vs Period A:** Not statistically significant (p ≈ 0.061).  

**Interpretation:**  
Most warming occurred between mid-century and the present period.

---

## Confidence Interval Summary
**How it was done:**  
- For each period, the *t-based confidence interval formula* was used.  
- The *standard error formula* and *margin-of-error formula* were applied.  
- CIs were calculated for Periods A, B, and C.  
(Pages 9–12) :contentReference[oaicite:4]{index=4}

**Results:**  
- **Period C:** CI = **(1.88°F, 6.36°F)** → Entirely above 0°F → firmly in **Zone 7a**, slight overlap into **7b**.  
- **Period B:** CI = **(–5.13°F, 0.85°F)** → Mostly **Zone 6b** with slight 6a/7a overlap.  
- **Period A:** CI = **(–0.65°F, 2.85°F)** → Straddles **Zone 6b–7a** boundary.  

**Interpretation:**  
Confidence intervals show a clear warming progression:  
B (coldest) → A → C (warmest).

---

## Normality & Distribution Checks Summary
**How it was done:**  
- The *Q-Q plot method* was used to visually compare data to a normal distribution.  
- Additional checks included *histograms* and *stem-and-leaf plots*.  
(Shown on pages 13–15) :contentReference[oaicite:5]{index=5}

**Result:**  
- All periods showed approximate normality.  
- Period B had slightly more extremes, but still acceptable.  
- Histograms and stem-and-leaf clearly show the distribution shifting warmer from Period B → A → C.

**Interpretation:**  
Using parametric tests (like the t-test) was justified.

---

## Time-Series Trend Summary
**How it was done:**  
- A *time-series plot* of annual extreme minimum temperature from 1941–2025 was generated.  
(Page 15–16) :contentReference[oaicite:6]{index=6}

**Result:**  
- Clear upward movement in extreme minimum temperatures over the decades.  
- Early years show consistently colder extremes; recent years show much warmer minima.

---

## Final Climate Classification
**How it was derived:**  
- Based on all results combined: descriptive means, t-tests, confidence intervals, and USDA zone thresholds.  
- Classification used the *USDA PHZ criteria* applied to mean and CI results.  

**Final Result:**  
- The current climate (Period C: 1991–2020) is best classified as **USDA Zone 7a**,  
with slight movement toward **Zone 7b**.

This is strongly supported by statistical, visual, and contextual evidence.  


